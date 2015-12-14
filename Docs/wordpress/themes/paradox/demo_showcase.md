---
title: Paradox: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Paradox Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/paradox:Paradox

---

Showcase Section
-----

![](demo_4.png)

:   1. **Text 1** [20%, 6%, se]
    2. **Text 2** [20%, 65%, se]

</br>

![](demo_5.png)

:   1. **Text 3** [20%, 6%, se]
    2. **Text 4** [20%, 65%, se]

The Showcase section actually includes two separately-displayed panels that are switched with a scroller mechanism. These panels are separated in the backend with a **Gantry Divider** widget. It's this widget that determined where the division is between displayed parts.

Here is the widget breakdown for the Showcase section:

* Text
* Text
* Gantry Divider
* Text
* Text

### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<img src="http://demo.rockettheme.com/live/wordpress/paradox/wp-content/rockettheme/rt_paradox_wp/frontpage/fp1.jpg" alt="image" class="rt-image floatleft" height="150" width="225"/>

<p><strong>Paradox</strong>, the <strong>June</strong> 2011 release, combines an dynamic, <strong>interactive</strong> arsenal with style and <strong>beauty</strong>.</p>

<p>Achieved with the functional <strong>scrolling</strong> widget features, and a <strong>diverse</strong> array of Preset Styles.</p>

<a href="#" class="readon" target="_blank"><span>More Information</span></a>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Introducing Paradox for June 2011`.
* Leaving everything else at its default setting, select **Save**.

### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<a href="http://gantry-framework.org/" target="_blank"><img src="http://demo.rockettheme.com/live/wordpress/paradox/wp-content/rockettheme/rt_paradox_wp/general/tutorial1.jpg" alt="tutorial" class="rt-image floatleft" height="150" width="225"/></a>

<p>The <strong>Gantry Framework</strong> is the foundation of the <strong>features</strong> and functions of the theme.</p> 

<p>Notably, it provides for a rich, friendly <strong>user interface</strong> to control major theme elements.</p>

<a href="http://gantry-framework.org/" class="readon" target="_blank"><span>More Information</span></a>							<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Gantry Framework - GPL, Free and Multi-Platform`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="bullet-monitor">
	<li><strong>Presets:</strong> 8 preset configurations of varying color schemes.</li>
	<li><strong>Background:</strong> 3 levels of detail for the main background: High, Med and Low.</li>
	<li><strong>Body:</strong> 2 levels of detailing for the body of the theme: High and Low</li>	
</ul>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Style Variation`.
* Leaving everything else at its default setting, select **Save**.

### Text 4

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="bullet-star">
	<li><strong>Mobile:</strong> Custom theme support for both iPhone and iPod Touch.</li>
	<li><strong>Positions:</strong> 70 collapsible widgets with 6 Grid Position Rows.</li>
	<li><strong>Fusion:</strong> A Mootools enhanced CSS dropdown menu, with multi-column and subtext support.</li>
</ul><div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `More Theme Features`.
* Leaving everything else at its default setting, select **Save**.
