---
title: Cerulean: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Cerulean Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cerulean:Cerulean

---

Sidebar Section
-----
![][sidebar]

:   1. **Text** [20%, 15%, se]
    2. **Search** [10%, 82%, sw]
    3. **Text** [20%, 82%, sw]
    3. **RokSprocket** [45%, 82%, sw]
    3. **Text** [68%, 82%, sw]

Here's the widget breakdown for the Sidebar section:

* Text
* Gantry Divider
* Search
* Text
* RokSprocket
* Text

### Text
The first Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Flexible Layouts.</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img1.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img1-large.jpg" />
</p>
<div class="rt-teaser">Responsive Modes</div>
<span>Adaptable layout for mobile<span class="visible-large"> (portrait / landscape)</span>, tablet and desktop displays.</span>
</div>

<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Gantry 4 Core.</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img2.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img2-large.jpg" />
</p><div class="rt-teaser">Advanced Features</div>
<span>Configure an array of features with the Gantry Framework<span class="visible-large">'s custom interface</span>.</span>
</div>

<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Multiple Styles</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img3.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-a/img3-large.jpg" />
</p><div class="rt-teaser">Configurable Presets</div>
<span>A wide selection of preset<span class="visible-large"> style</span>s and widget <span class="visible-large">variations</span><span class="hidden-large">variations</span> are available.</span>
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Recent [span class=\"hidden-tablet\"]News[/span]`.
* Set the **Title Variation** to **Title 1**.
* Set the **Custom Variation** to `title3 rt-box2-stack nopaddingall nomarginleft nomarginbottom`.
* Leaving everything else at its default setting, select **Save**.

### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Search
The Search widget is fairly straightforward. The most important thing to remember when attempting to recreate the demo is the **Custom Variation** which sets the CSS rules for the widget.

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Search Our Site`.
* Set the **Box Variation** to **Box 4**.
* Set the **Custom Variation** to `rt-suspend`.
* Leaving everything else at its default setting, select **Save**.

### Text
The next Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<div>
<span class="rt-image rt-floatleft">
<img src="http://demo.rockettheme.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/sidebar-b/img1.jpg" alt="image">
</span>
<small class="hidden-tablet">Choose between a static or a <a href="http://demo.rockettheme.com/wordpress/wp_cerulean/plugins/">RokGallery</a> powered slideshow in the theme <strong>header</strong><span class="visible-large">, with its standard configuration options</span>.</small>
<small class="visible-tablet">Choose between a static or a <a href="http://demo.rockettheme.com/wordpress/wp_cerulean/plugins/">RokGallery</a> slideshow header.</small>
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `About Cerulean`.
* Set the **Box Variation** to **Box 5**.
* Leaving everything else at its default setting, select **Save**.

### RokSprocket
The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 
You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option            | Setting |  
| :---------------- | ------: |  
| Theme             | Default |  
| Display Limit     |       ∞ |  
| Preview Length    |      20 |  
| Strip HTML Tags   |     Yes |  
| Previews Per Page |       5 |  
| Arrow Navigation  |    Show |  
| Pagination        |    Show |  
| Autoplay          | Disable |  
| Image Resize      | Disable |  
| Default Link      |    None |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Gantry Extras`
* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Set the Box Variation field to **Box 1**.
* Set the **Custom Variations** field to `rt-flush`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

### Text
The next Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<p>RocketLauncher is a customized WordPress install, that installs a replica of the demo.</p>

<p class="hidden-tablet">All sample content images, shown in this demo, will be replaced with blanks in the RocketLauncher for copyright reasons.</p>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Cerulean[span class=\"hidden-tablet\"] Demo[/span].  [span class=\"icon-chevron-down rt-teaser\"][/span]`.
* Set the **Box Variation** to **Box 3**.
* Leaving everything else at its default setting, select **Save**.

[sidebar]: assets/sidebar.jpg