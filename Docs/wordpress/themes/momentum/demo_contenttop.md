---
title: Momentum: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Momentum Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/momentum:Momentum

---

Content Top Section
-----

![][demo1]

:   1. **Text** [15%, 10%, se]
    2. **Calendar** [15%, 60%, se]

Here is the widget breakdown for the Content Top section:

* Text
* Gantry Divider
* Calendar

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<img src="http://demo.rockettheme.com/live/wordpress/momentum/wp-content/rockettheme/rt_momentum_wp/frontpage/fp-sample-image.jpg" width="350" height="210" alt="Image">
<h3><span>Introducing</span> Momentum the May 2012 RocketTheme WordPress Theme Release</h3>
<p class="nomarginbottom">The theme combines an <em>intricate graphical design</em> with the intuitive dynamics of <strong>RokGallery</strong> or RokStories, providing for a full scale <strong>background image</strong>, rotatable and configurable via the widget, RokGallery and Gantry <strong>administrative</strong> interfaces.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `wide` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Calendar

The **Calendar** widget adds an interactive calendar element to the page. To add this widget, simply click and drag a **Calendar** widget item to the appropriate widget position. The **Title** of the widget is `Calendar` and we entered `ribbon` in the **Custom Variations** field.

[roksprocket]: ../../plugins/roksprocket/
[demo1]: assets/demo_2.jpeg
