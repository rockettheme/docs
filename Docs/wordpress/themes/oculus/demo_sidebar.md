---
title: Oculus: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Oculus Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/oculus:Oculus

---

Sidebar
-----

Here's the widget breakdown for the Sidebar section:

* RokSprocket
* RokSprocket
* Gantry Divider
* RokSprocket
* Text
* Text

#### RokSprocket

![][demo]

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | :------ |  
| Theme               | Default |  
| Collapsible Preview | Disable |  
| Display Limit       | ∞       |  
| Preview Length      | 20      |  
| Strip HTML Tags     | No      |  
| Previews Per Page   | 3       |  
| Arrow Navigation    | Show    |  
| Pagination          | Hide    |  
| Autoplay            | 5       |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Popular News`.
* Set the **Box Variation** option to **Box 6**.
* Set the **Title Variation** option to **Title 4**.
* Set the **Other Variations** option to **Horizontal Gradient**.
* Enter `icon-file-alt fp-roksprocket-lists-2` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### RokSprocket

![][demo2]

You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Tabs Position   | Top            |
| Display Limit   | ∞              |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | 0              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `Popular Features` in the **Title** field.
* Enter `fp-roksprocket-tabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. 

#### RokSprocket

![][demo3]

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | :------ |  
| Theme               | Default |  
| Collapsible Preview | Enable  |  
| Display Limit       | ∞       |  
| Preview Length      | 20      |  
| Strip HTML Tags     | No      |  
| Previews Per Page   | 3       |  
| Arrow Navigation    | Show    |  
| Pagination          | Show    |  
| Autoplay            | 5       |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Gantry Extras`.
* Set the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text

![][demo4]

This section of the page is a standard text widget. You'll need to enter the following in the main text field.

~~~
<p>RocketLauncher installs a replica of the demo.</p>

<p class="fp-sidebar-b-img"><img class="rt-image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img7.jpg" alt="image" /></p>

<a class="readon" href="#">Read More</a>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `[span class=\"hidden-tablet\"]Oculus [/span]Demo`.
* Switch the **Box Variation** option to **Box 4**.
* Set the **Margin Variation** option to **No Margin Right**.
* Set the **Other Variations** option to **Horizontal Gradient**.
* Enter `icon-copy hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.


#### Text

![][demo5]

This section of the page is a standard text widget. You'll need to enter the following in the main text field.

~~~
<p>RokAjaxSearch style <span class="hidden-tablet">is available with this template.</span></p>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img1.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img2.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img3.jpg">
    </span>
  </div>
</div>

<div class="clear"></div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img4.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img5.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="http://demo.rockettheme.com/wordpress/wp_oculus/wp-content/rockettheme/rt_oculus_wp/frontpage/sidebar/img6.jpg">
    </span>
  </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Our Users`.
* Switch the **Box Variation** option to **Box 6**.
* Set the **Margin Variation** option to **No Margin Right**.
* Set the **Other Variations** option to **Horizontal Gradient**.
* Enter `icon-camera-retro fp-sidebar-b hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_7.jpeg
[demo3]: assets/demo_6.jpeg
[demo4]: assets/demo_8.jpeg
[demo5]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/