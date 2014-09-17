---
title: Tessellate: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Bottom Section
-----

![][demo]

:   1. **Text 1** [15%, 5%, se]
    2. **Text 2** [15%, 36%, se]
    3. **Text 3** [15%, 52%, se]
    4. **Text 4** [15%, 68%, se]

Here is the widget breakdown for the Bottom section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h6>Demo Information</h6>

<p>All demo content is for sample purpose only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.</p>

<p>Please use Tessellate RocketLauncher to install a demo equivalent onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Disclaimer`.
* Switch the **Widget Variations** option to **Title 2**.
* Enter `fp-bottom-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul>
	<li><a href="http://(your url)/wordpress/tessellate2/features-overview/">About</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/widget-positions/">Widgets</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/widget-variations/">Variations</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/menu-options/">Menu</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/typography/">Typography</a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Info`.
* Switch the **Widget Variations** option to **Title 2**.
* Enter `fp-bottom-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul>
	<li><a href="http://(your url)/wordpress/tessellate2/the-team/">Team</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/pricing-tables/">Pricing</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/portfolio/">Portfolio</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/category/blog/">Blog</a></li>
	<li><a href="http://(your url)/wordpress/tessellate2/offline-page/">Maintenance</a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Pages`.
* Switch the **Widget Variations** option to **Title 2**.
* Enter `fp-bottom-c` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 4

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Subscribe to our newsletter in order to receive the latest news &amp; articles. We promise we won't spam your inbox!</p>

<form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" class="rt-form-horizontal">
	<input type="text" placeholder="Your Email" class="inputbox" name="email" />
	<input type="hidden" value="rocketthemeblog" name="uri" />
	<input type="hidden" name="loc" value="en_US" />
	<input type="submit" name="Submit" class="readon2" value="Join">
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Newsletter`.
* Switch the **Widget Variations** option to **Title 2**.
* Enter `fp-bottom-d` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_11.jpeg
[roksprocket]: ../../plugins/roksprocket/
