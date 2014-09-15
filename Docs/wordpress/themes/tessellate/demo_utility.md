---
title: Tessellate: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Utility Section
-----

![][demo]

Here is the widget breakdown for the Utility section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
	<div class="gantry-width-50">
		<div class="fp-utility-image-block">
			<img src="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/wp-content/rockettheme/rt_tessellate_wp/home/fp-utility/img-01.jpg" alt="image" />
			<div class="rt-image-desc-overlay">
				<div class="rt-image-desc">
					<div class="rt-icon-diagonal"><i class="fa fa-briefcase"></i></div>
					<h3>Quick &amp; Easy Installation</h3>
				</div>
			</div>
		</div>
	</div>
	<div class="gantry-width-50">
		<div class="fp-utility-image-block">
			<img src="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/wp-content/rockettheme/rt_tessellate_wp/home/fp-utility/img-02.jpg" alt="image" />
			<div class="rt-image-desc-overlay">
				<div class="rt-image-desc">
					<div class="rt-icon-diagonal"><i class="fa fa-truck"></i></div>
					<h3>Accessible Resources</h3>
				</div>
			</div>
		</div>
	</div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Using Tessellate`.
* Switch the **Widget Variations** option to **RT-Center**.
* Enter `fp-utility` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
