---
title: Syndicate: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Syndicate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/syndicate:Syndicate

---

Bottom Section
-----

![][demo]

:   1. **RokTabs** [12%, 6%, se]
    2. **Text 1** [12%, 51%, se]
    3. **Text 2** [56%, 51%, se]
    4. **Text 3** [12%, 73%, se]

Here is the widget breakdown for the Bottom section:

* RokTabs
* Gantry Divider
* Text
* Text
* Gantry Divider
* Text

#### RokTabs

This area of the demo is a **RokTabs** widget. This plugin is considered legacy and no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><img src="http://demo.rockettheme.com/live/wordpress/syndicate/wp-content/rockettheme/rt_syndicate_wp/frontpage/mainbottom1.jpg" alt="image" /></p>
<p>Contact our website news team via our <em>Online Customer Support Service</em>.</p>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Contact Us` in the **Title** field.
* Switch the **Box Variation** option to **Box 6**.
* Switch the **Title Variation** option to **Title 3**.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for demonstrative purposes only, intended to show a representative example of a live site. All images and materials are the copyright of their respective owners.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Demo Information` in the **Title** field.
* Switch the **Widget Style** option to **Flush**.
* Switch the **Title Variation** option to **Title 5**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p style="line-height: 400px;text-align: center;"><b style="font-size: 18px;">240x400 IMU</b></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Box Variation** option to **AdBox Bg**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
