---
layout: calendar  # required
title: My Calendar

calendar_timezone_offset: -0500   # required
calendar_csv: example/events.csv  # required. Path from base url

calendar_focus_date: 2017-04-15   # optional. YYYY-MM-DD. Without it, the default is today
calendar_caption: Find Community Service Events This Week!   # optional
---

<!-- Learn about this code on MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode -->
<div class="community-header">
  <!-- TOP BAR -->
  <div class="row">
    <div class="top-bar">
      <div class="top-bar-title">
          <a class="masthead" href="/"><img alt="The Pennsylvania State University" src="../assets/img/psu_shield.svg"/></a>
    <span data-responsive-toggle="responsive-menu" data-hide-for="medium" class="menu-button">
      <button class="menu-icon" type="button" data-toggle></button>
    </span>
      </div>
     {% include top-menu.html %}
    </div>
  </div>
  <!-- END TOP BAR -->
  <div class="row quote-row">
    <div class="small-12 columns">
      <h1 class="secondary-page-heading">{{ page.title }}</h1>
    </div>
    <div class="small-12 columns">
      <h2 class="quote">Find an event near you!</h2>
    </div>
  </div>

</div>
<!-- END HEADER -->
