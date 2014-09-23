---
title: Mercado: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Mercado Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/mercado:Mercado

---

Content Top Section
-----

![][demo]

Here is the widget breakdown for the Content Top section:

* Text
* Text

The two text widgets are separated by the scrolling widgets function of the theme. This means that only one of the text widgets appears at a time, and as the user clicks the **More** button, they rotate. Pictured above is the first **Text** widget, while the second **Text** widget is pictured in its section below.

The **Scrolling Widgets** function can be turned on and off via the **Theme Settings** area of the backend. You can get to this option by navigating to **Admin > Mercado Theme > Gizmos** and turning the **Content Top Position** to **Enabled**. You can do the same for the **Content Bottom** widget position there, if you wish to take advantage of this function there, as well.

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image1-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image1.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image2-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image2.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image3-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image3.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image4-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image4.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image5-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image5.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image6-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image6.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image7-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image7.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image8-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan ??? http://fantasticfunmachine.blogspot.com/"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/scroll-image8.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<div class="clear"></div>
~~~

Leaving everything else at its default setting, select **Save**.

#### Text 2

![][demo2]

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-demo-grid-4">
  <div class="module-title"><h2 class="title">Scrolling Widgets</h2></div>
  <p><strong>Scrolling Positions</strong> is a feature of Gantry, which, when activated, modifies the behaviour of <strong>stacked</strong> widgets. Instead of appearing vertically, the additional widgets assigned to a given position become accessible via a <strong>javascript transition button</strong>, in this case: "More".</p>
  <p>The <a href="#">Content Top</a> and <a href="#">Content Bottom</a> position rows have this feature.</p>
</div>
<div class="rt-demo-grid-4 floatright">
  <div class="module-title"><h2 class="title">Hidden Content</h2></div>
  <p>In this demo, we have disabled the frontpage content from displaying (in the Front Page override), therefore, only widgets will appear. This is achievable via a setting in <strong>Admin Dashboard &rarr; Mercado Theme &rarr; Advanced &rarr; Display Content : On/Off</strong>.</p>
  <p>Additionally, you can disable the entire mainbody area with the <strong>Display Main Body</strong> setting.</p>
</div>
<div class="clear"></div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/
