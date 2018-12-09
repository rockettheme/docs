---
title: Chimera: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Chimera Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Utility Section
-----

![Utility](assets/demo_3.jpeg)

:	1. **Text 1** [13%, 7%, se]
	2. **Text 2** [13%, 70%, se]

Here is the widget breakdown for the Utility section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<span class="rt-icon-left rt-hero-icon wow bounceInLeft">
  <i class="fa fa-laptop"></i>
</span>
<h3><a href="http://demo.rockettheme.com/live/wordpress/chimera/features-overview/">Fully Responsive and Mobile Minded</a></h3>
<p>Chimera features a fully responsive layout and design built from the ground up to ensure perfect presentation of your content from the smallest mobile devices to the largest desktop displays.</p>

<div class="clear"></div><br />

<span class="rt-icon-left rt-hero-icon wow bounceInLeft" data-wow-delay="0.2s">
  <i class="fa fa-tasks"></i>
</span>
<h3><a href="http://demo.rockettheme.com/live/wordpress/chimera/features-overview/">Colorfully Stylish Presets</a></h3>
<p>The perfect blend of whitespace and splashes of contrasting color create a smorgasbord of possibilities for giving your site the look and feel you are after.</p>

<div class="clear"></div><br />

<span class="rt-icon-left rt-hero-icon wow bounceInLeft" data-wow-delay="0.4s">
  <i class="fa fa-text-height"></i>
</span>
<h3><a href="http://demo.rockettheme.com/live/wordpress/chimera/typography/">Rich Typography and Iconic Elements</a></h3>
<p>Chimera helps you say more with less, utilizing clean and subtle fonts that are easy to read with contrasting bold rich titles and icon elements to draw attention to the most important messages.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-utility` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-device-animation" data-animation-step="1">
  <div class="device">
    <div class="phone-home-button"></div>
    <div class="tablet-home-button"></div>
    <div class="screen-stand"><div class="leg"></div><div class="foot"></div></div>
    <div class="display">
      <div class="slide1"><div>Chimera's design is great on <strong>desktops</strong>...</div></div>
      <div class="slide2"><div>...brilliant on <strong>tablets</strong>...</div></div>
      <div class="slide3"><div>and perfect for <strong>mobile!</strong></div></div>
    </div>
  </div>
</div>

<script>

  var duration = 20000, steps = 3, step = 1;

  setInterval( function() {
    document.querySelector( '.rt-device-animation' ).setAttribute( 'data-animation-step', step = ++step > steps ? 1 : step );
  }, duration / steps );

</script>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-utility-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
