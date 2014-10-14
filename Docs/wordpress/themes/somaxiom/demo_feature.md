---
title: Somaxiom: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

Feature Section
-----

![][demo]

:   1. **Text 1** [18%, 6%, se]
    2. **Text 2** [18%, 36%, se]
    3. **Text 3** [18%, 66%, se]

Here is the widget breakdown for the Feature section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="fp-feature">
    <img src="http://demo.rockettheme.com/live/wordpress/somaxiom/wp-content/rockettheme/rt_somaxiom_wp/frontpage/feature-a1.jpg" alt="Feature Image" class="floatleft fp-image" height="75" width="80"/>
    <p>
        <strong>Fusion:</strong> advanced mootools / javascript powered CSS dropdown menu system.
        <a class="readon" href="#"><span>Read More</span></a>
        <span class="clear"></span>
    </p>
    
    <img src="http://demo.rockettheme.com/live/wordpress/somaxiom/wp-content/rockettheme/rt_somaxiom_wp/frontpage/feature-a2.jpg" alt="Feature Image" class="floatleft fp-image" height="75" width="80"/>
    <p>
        <strong>Splitmenu:</strong> places children below the main menu bar, then others in the side column.
        <a class="readon" href="#"><span>Read More</span></a>
        <span class="clear"></span>
    </p>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Two Menu Systems`.
* Switch the **Widget Variations** option to **Tab 1**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="caption-surround"><img src="http://demo.rockettheme.com/live/wordpress/somaxiom/wp-content/rockettheme/rt_somaxiom_wp/frontpage/feature-b1.jpg" alt="Feature Image" class="fp-image" height="94" width="260"/><div class="caption-icon">0</div>
<div class="caption-text">This is a caption</div></div>
<p>January sees the release of an updated <strong>RokStories</strong>, with a 5th layout option with <strong>image masking</strong>, as well as <strong>vertical number listing</strong>.</p>
<a class="readon" href="#"><span>More Extension Information</span></a><div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `New RokStories Layout`.
* Switch the **Widget Variations** option to **Bg2 + Tab2**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<em class="rt-typoblock">RokStories - Content Showcase</em>
<p>Functional showcase widget for displaying content items and their accompanying images.</p>

<em class="rt-typoblock">RokNewsPager - Article Previewer</em>
<p>RokNewsPager is an article previewer and rotator in a summarised form and, using Mootools.</p>

<a class="readon" href="#"><span>Read More</span></a>
<div class="clear"></div>                           <div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `rockettheme plugins support`.
* Switch the **Widget Variations** option to **Tab 3**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[menu]: ../../start/menus.md
[faq]: faq.md
