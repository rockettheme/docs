---
title: Graffito: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Graffito Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/graffito:Graffito

---

Extension
-----
![][demo5]

Here's the widget breakdown for the Extension section:

* Text
* Gantry Divider
* RokSprocket

### Text

The Text widget in this section is pretty straightforward. You'll need to enter the following in the main text field.

~~~
<div class="rt-image largemarginbottom">
    <img alt="image" src="http://127.0.0.1/wordpress/graffito/wp-content/rockettheme/rt_graffito_wp/frontpage/general/featured-2.jpg">
</div>

<p class="medmarginbottom"><strong>RocketLauncher</strong> is a customized <strong>WordPress</strong> install, that installs a <strong>replica</strong> of the <strong>demo</strong>.</p>

<p>All sample content images, shown in this demo, will be replaced with blanks in the <a href="http://127.0.0.1/wordpress/graffito/installation/"><strong>RocketLauncher</strong></a> package to avoid any copyright issue.</p>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Graffiti Demo`.
* Switch the **Title Variation** option to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket

![][demo6]

This RokSprocket widget is a **Tabs** widget type. Like other RokSprocket Widgets, you'll need to create it first using the **RokSprocket Admin** menu. We named ours **Popular Features**.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option          |        Setting |  
| :-------------- | -------------: |  
| Theme           |        Default |  
| Tabs Position   |            Top |  
| Display Limit   |              ∞ |  
| Animation       | Slide and Fade |  
| Autoplay        |        Disable |  
| Autoplay Delay  |              5 |  
| Image Resize    |        Disable |  
| Preview Length  |              0 |  
| Strip HTML Tags |             No |  
| Default Link    |           None |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the title to `Popular Features.`
* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Title Variation** option to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo5]: assets/wp_graffito_demo_5.jpeg
[demo6]: assets/wp_graffito_demo_6.jpeg