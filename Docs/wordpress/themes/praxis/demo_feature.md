---
title: Praxis: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Feature Section
-----

![][demo]

Here is the widget breakdown for the Feature section:

* Text

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="rt-block box2 rt-shadow rt-square fp-sidenav-spacing nomarginleft nomarginright">
    <p class="largepaddingall nomarginbottom"><span class="promo2"><strong><a href="#">About Praxis:</a></strong> An elegant visual platform with powerful interactive tools<span class="visible-large"> and versatile features</span>.</span></p>
</div>

<div class="fp-sidenav-spacing">	
	<div class="rt-center">
		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="http://demo.rockettheme.com/wordpress/wp_praxis/wp-content/rockettheme/rt_praxis_wp/frontpage/feature/img1.jpg" /></p>
				<h3 class="rt-dark-text">Dropdown <strong>Menu</strong></h3>
				<p><strong>Dropdown</strong> is a CSS powered dropdown menu system with advanced features such as multiple columns.</p>
			</div>
		</div>

		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="http://demo.rockettheme.com/wordpress/wp_praxis/wp-content/rockettheme/rt_praxis_wp/frontpage/feature/img2.jpg" /></p>
				<h3 class="rt-dark-text">Site <strong>Performance</strong></h3>
				<p><strong>Optimized</strong> images and compressed CSS files, through usage of the LESS, improve overall template performance.</p>
			</div>
		</div>

		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="http://demo.rockettheme.com/wordpress/wp_praxis/wp-content/rockettheme/rt_praxis_wp/frontpage/feature/img3.jpg" /></p>
				<h3 class="rt-dark-text">Addon <strong>Styling</strong></h3>
				<p><strong>Praxis</strong> has styled integration for a variety of RocketTheme plugins such as RokSprocket or RokAjaxSearch.</p>
			</div>
		</div>

		<div class="clear"></div>
	</div>	
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Margin Variation** option to **No Margin Left**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/