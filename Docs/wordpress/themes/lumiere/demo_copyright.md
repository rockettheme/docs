---
title: Lumiere: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Lumiere Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/lumiere:Lumiere

---

Copyright Section
-----
![][demo]

:   1. **Custom Menu** [58%, 8%, se]
	2. **Text** [58%, 72%, se]

Here's the widget breakdown for the Copyright section:

* Gantry Divider
* Custom Menu
* Gantry Divider
* Text

The Copyright section contains the bottom menu and social links for the front page. You'll find the configuration options for each widget below.

#### Custom Menu
The Custom Menu widget allows us to add an extra menu at the bottom of the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you'll need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Set the **Custom Variations** field to `horizmenu rt-center`.
* Leaving all other options at their default settings, click **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text
You'll need to enter the following in the main text field to create this text widget as it appears in our demo. The title is left blank.

~~~
<div class="rt-social-buttons">
    <span class="boldfont largepaddingright">Follow Us</span>
	<a href="http://www.facebook.com/RocketTheme" class="social-button rt-facebook-btn"><span></span></a>
	<a href="https://twitter.com/rockettheme" class="social-button rt-twitter-btn"><span></span></a>
	<a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-google-btn"><span></span></a>
	<a href="http://www.rockettheme.com/blog?format=feed&amp;type=rss" class="social-button rt-rss-btn"><span></span></a>
	<div class="clear"></div>
</div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg