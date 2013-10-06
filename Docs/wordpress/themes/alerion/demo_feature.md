---
title: Alerion: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/alerion:Alerion

---

Feature Section
-----

![][demo]

:	1. **Text** [30%, 10%, se]

Here's the widget breakdown for the Feature section:

* Text

### Text
You'll need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~
<div class="fp-feature-a">
<div class="gantry-width-60 gantry-width-block">
    <div class="gantry-width-10 gantry-width-block hidden-phone">
      <span class="icon-map-marker rt-large-icon"></span>
  </div>
  <div class="gantry-width-90 gantry-width-block">
    <h4 class="smallmargintop hidden-phone">East 27 Street and Campus Road,</h4>
      <h4>Brooklyn, NY 11210</h4>
  </div>
</div>

<div class="gantry-width-40 gantry-width-block">
  <div class="gantry-width-10 gantry-width-block hidden-phone">
      <span class="icon-mobile-phone rt-large-icon"></span>
  </div>
  <div class="gantry-width-90 gantry-width-block">
    <h4 class="smallmargintop hidden-phone">555.951.5528</h4>
      <h4>555.951.5529</h4>
  </div>
</div>

<div class="clear"></div>

<div class="rt-image fp-image">
  <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/feature/img1.jpg">
  <div class="rt-image-desc hidden-phone">
    <span><strong>Monday, April 1,</strong> 2013 at 1:00 PM</span><br />
    <span><strong>Tuesday, April 30,</strong> 2013 at 4:00 PM (PDT)</span>
  </div>
</div>

<div class="clear"></div>

<p><strong>Alerion</strong> is a visually intense design, focusing on <strong>rich</strong> elements split into distinct sections to add depth to content. Additional design features include configurable <strong>floating</strong> widgets and <strong>quicknav</strong> feature, as well as <strong>parallax</strong> background effects.</p>

<p class="hidden-phone">Click the <strong>Quick Tour</strong> button in the floating widget, titled '<strong>Your Tickets Here</strong>' to the right, to preview the Parallax effect. Parallax will be active when you <strong>scroll</strong> the page, and sections which are configured to show it are published and present.</p>
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Enter `TechnoEvent` as the **Title** of the widget.
* Set the **Title Variation** option to **Title 2**.
* Enter `fp-feature-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg