---
title: Ximenia: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ximenia:Ximenia

---

Copyright Section
-----
![][demo2]

Here's the widget breakdown for the Copyright section:

* Gantry Branding
* Gantry Divider
* Text
* Gantry Divider
* Gantry To Top

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Text
The Text widget in the section is used as a handmade menu. You'll need to enter the following in the main text field.

~~~
<ul class="menu">
	<li><a href="http://demo.rockettheme.com/wordpress/wp_voxel/">Home</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress/wp_voxel/theme-features/">Features</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress/wp_voxel/tutorials/">Tutorials</a></li>
	<li><a href="http://demo.rockettheme.com/wordpress/wp_voxel/preset-styles/">Styles</a></li>
	<li><a href="http://rockettheme.com" target="_blank">RocketTheme</a></li>
</ul>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Margin Variation** to **No Margin Left**.
* Enter `horizmenu rt-floatright` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry To Top
The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it.

[demo2]: assets/wp_Ximenia_demo_7.jpeg