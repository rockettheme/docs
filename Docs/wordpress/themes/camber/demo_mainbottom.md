---
title: Camber: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Camber Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/camber:Camber

---

Main Bottom Section
-----

![][demo]

:   1. **RokTabs** [10%, 7%, se]
    2. **Text** [10%, 66%, se]
    3. **Text** [60%, 66%, se]

Here is the widget breakdown for the Main Bottom section:

* RokTabs
* Gantry Divider
* Text
* Text

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Gantry is a powerful framework at the core of the theme, providing a rich array of features:</p>
<ul class="menu">
    <li><a href="#"><span>An advanced and intuitive control panel to easily configure the theme.</span></a></li>
    <li><a href="#"><span>Control Gantry settings for each page with per-override configuration.</span></a></li>
    <li><a href="#"><span>Mobile browsing support for the Android and iOS operating systems.</span></a></li>
    <li><a href="#"><span>Support for Color Chooser for ease of customization.</span></a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Gantry Framework`.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="smallmarginbottom"><strong>Custom Tag-Based Architecture</strong></p>
<div class="rt-articleinfo smallmarginbottom"></div>
<p>RokGallery is an advanced gallery, with non-destructive slice editing, and other features typically associated with native apps.</p>
<a class="readon" href="http://demo.rockettheme.com/live/wordpress/camber/plugins/"><span>Read More</span></a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `RokGallery Plugin`.
* Switch the **Box Variation** option to **Box 1**.
* Switch the **Title Variation** option to **Title 1**.
* Enter `rt-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/
