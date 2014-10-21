---
title: Dominion: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Dominion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/dominion:Dominion

---

Main Top Section
-----

![][demo]

:   1. **Text** [15%, 7%, se]
    2. **RokTabs** [15%, 38%, se]

Here is the widget breakdown for the Main Top section:

* Text
* Gantry Divider
* RokTabs

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="demo-img"><img class="rt-image" alt="Feature Demo Image" src="http://demo.rockettheme.com/live/wordpress/dominion/wp-content/rockettheme/rt_dominion_wp/frontpage/fta-1.jpg"/></div>
<div class="clear"></div>
<h3 class="demo-title" style="visibility: visible;"><span>Gantry</span> has arrived!</h3>

<p>Dominion is sporting the brand new WordPress framework - <span class="demo-title">Gantry Framework</span>, bringing with it many new and powerful tools and features.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Powered by Gantry` in the **Title** field.
* Set the **Widget Variations** option to **Medium**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

[roksprocket]: ../../plugins/roksprocket/
[demo]: assets/demo_4.jpeg
