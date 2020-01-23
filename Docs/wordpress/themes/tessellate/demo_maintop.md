---
title: Tessellate: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Main Top Section
-----

![][demo]

:   1. **Text 1** [9%, 5%, se]
    2. **Text 2** [9%, 51%, se]

Here is the widget breakdown for the Main Top section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
	<div class="gantry-width-50 fp-maintop-col1">
		<img src="http://(your url)/wordpress/tessellate2/wp-content/rockettheme/rt_tessellate_wp/home/fp-maintop/img-01.jpg" alt="image" />
		<div class="fp-maintop-img-desc">
			<h6 class="nomargintop smallmarginbottom">Information</h6>
			<p>Gantry is a theme framework for Joomla and Wordpress<span class="hidden-tablet">, by RocketTheme, providing a standardized product core</span>.</p>
		</div>
	</div>
	<div class="gantry-width-50 fp-maintop-col2">
		<div class="gantry-width-spacer">
			<h3>The <span class="hidden-tablet">Free/GPL </span>Gantry Framework</h3>

			<p>The most noticeable visual feature of Gantry is its custom administrator, providing a user friendly <span class="hidden-tablet">and rich </span>console for theme configuration.</p>
			<p class="hidden-tablet">The framework has many features, such as widget grid controls, that come as standard on all themes.</p>

			<p class="visible-large">Other features include overridable layouts for widgets, positions and mainbody output; several features such as font-sizer; as well as powering the LESS infrastructure.</p>

			<a href="http://(your url)/wordpress/tessellate2/features-overview/" class="readon5">Read More</a>
		</div>
	</div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Widget Variations** option to **Box 3, No Padding All**.
* Enter `fp-maintop-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
	<div class="gantry-width-50 fp-maintop-col1">
		<img src="http://(your url)/wordpress/tessellate2/wp-content/rockettheme/rt_tessellate_wp/home/fp-maintop/img-02.jpg" alt="image" />
		<div class="fp-maintop-img-desc">
			<h6 class="nomargintop smallmarginbottom">Information</h6>
			<p><span>RokSprocket is a content widget <span class="hidden-tablet">for Joomla and Wordpress, </span>by RocketTheme<span class="hidden-tablet">, that offers multiple layouts and themes</span>.</span></p>
		</div>
	</div>
	<div class="gantry-width-50 fp-maintop-col2">
		<div class="gantry-width-spacer">
			<h3>RokSprocket <span class="hidden-tablet">Content </span>Widget</h3>

			<p>RokSprocket has its own, unique, custom administrative interface with intuitive controls and ajax loading to make content setup quick and easy.</p>
			<p class="hidden-tablet">RokSprocket has multiple layouts to choose from with varying themes, such as Features : Showcase.</p>

			<p class="visible-large"> Others include Tabs, Headlines, Mosaic, Strips and Lists. RokSprocket also benefits from multiple content providers, such as WordPress, Types and its own, Simple.</p>

			<a href="http://(your url)/wordpress/tessellate2/features-overview/" class="readon4">Read More</a>
		</div>
	</div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Widget Variations** option to **Box 3, No Padding All**.
* Enter `fp-maintop-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/
