---
title: Voxel: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Voxel Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/voxel:Voxel

---

Copyright Section
-----

![][demo2]

:	1. **Gantry Branding** [40%, 7%, se]
	2. **Text** [40%, 35%, se]
	3. **Gantry To Top** [40%, 90%, se]

Here is the widget breakdown for the Copyright section:

* Gantry Branding
* Gantry Divider
* Text
* Gantry Divider
* Gantry To Top

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Gantry Branding

The Gantry Branding widget does little more than display our logo at the bottom of the page. Simply click and drag the **Gantry Branding** widget into the widget section for this to appear.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

The Text widget in the section is used as a handmade menu. You will need to enter the following in the main text field.

~~~
<ul class="menu">
	<li><a href="http://demo.rockettheme.com/wordpress-themes/wp_voxel/">Home</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress-themes/wp_voxel/theme-features/">Features</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress-themes/wp_voxel/tutorials/">Tutorials</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress-themes/wp_voxel/preset-styles/">Styles</a></li>
	<li><a href="http://www.rockettheme.com" target="_blank">RocketTheme</a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Margin Variation** to **No Margin Left**.
* Enter `horizmenu rt-floatright` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry To Top

The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it.

[demo2]: assets/demo_13.jpeg
