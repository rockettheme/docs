---
title: Halcyon: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Halcyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/halcyon:Halcyon

---

Extension Section
-----

![][demo1]

:   1. **Text 1** [20%, 7%, se]
    2. **Text 2** [20%, 45%, se]
    3. **Text 3** [20%, 68%, se]

Here is the widget breakdown for the Extension section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="customtitle1">
    <div class="fp-side largepaddingbottom largemarginbottom">
    <img src="http://demo.rockettheme.com/live/wordpress/halcyon/wp-content/rockettheme/rt_halcyon_wp/frontpage/ex1.jpg" width="110" height="82" alt="image" class="rt-image floatleft " smartload="15" style="opacity: 1; ">
    <span><strong>SplitMenu</strong></span><br>
    <span>A basic, horizontal <em>dropline</em> menu system, with configurable options such as <em>suffix</em> and position.</span>
    <div class="clear"></div>
</div>
<div>
    <img src="http://demo.rockettheme.com/live/wordpress/halcyon/wp-content/rockettheme/rt_halcyon_wp/frontpage/ex2.jpg" width="110" height="82" alt="image" class="rt-image floatleft " smartload="16" style="opacity: 1; ">
    <span><strong>Fusion with MegaMenu</strong></span><br>
    <span>A <em>Mootools</em> enhanced, CSS <em>dropdown</em> menu, with animated dropdowns, column width/allocation control plus much more.</span>
    <div class="clear"></div>
</div></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Other Menu Options`.
* Set the **Title Variation** to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="customtitle1">
    <p>Instructions on how to <strong>install</strong> RocketLauncher (demo replica) and the standalone/bundled <strong>theme</strong> packages.</p>
<p><a href="http://demo.rockettheme.com/live/wordpress/halcyon/tutorials/installation/" class="readon"><span>How to Install</span></a></p>

<p>Guide on how to customize the logo using the <strong>Adobe&reg; Fireworks</strong> PNG Source images.</p>
<a href="http://demo.rockettheme.com/live/wordpress/halcyon/tutorials/logo-editing/" class="readon"><span>Logo Customization</span></a></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Tutorials`.
* Set the **Title Variation** to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="customtitle1">
    <p><img src="http://demo.rockettheme.com/live/wordpress/halcyon/wp-content/rockettheme/rt_halcyon_wp/frontpage/ex3.jpg" alt="image" width="240" height="180" class="rt-image " smartload="17" style="opacity: 1; "></p>
<span class="rt-upper">Advertisement</span></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Promotion`.
* Set the **Title Variation** to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_9.jpeg
