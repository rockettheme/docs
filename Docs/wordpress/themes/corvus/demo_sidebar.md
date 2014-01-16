---
title: Corvus: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Sidebar Section
-----

![][demo]

:   1. **RokSprocket** [8%, 8%, se]
    2. **Text** [8%, 63%, se]
    3. **RokSprocket** [45%, 63%, se]

Here is the widget breakdown for the Sidebar section:

* RokSprocket
* Gantry Divider
* Text
* RokSprocket

#### RokSprocket

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting              |  
| :------------------ | :------------------- |  
| Theme               | Default              |  
| Collapsible Preview | Disable              |  
| Display Limit       | 6                    |  
| Preview Length      | 50                   |  
| Strip HTML Tags     | No                   |  
| Previews Per Page   | 2                    |  
| Article Details     | Show Author and Date |  
| Arrow Navigation    | Show                 |  
| Pagination          | Show                 |  
| Autoplay            | 5                    |  
| Image Resize        | Disable              |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Gantry Extras`.
* Set the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.


#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p><strong>RocketLauncher</strong> installs a replica of the demo.</p>
<a href="#"><span class="rt-image-b"><img src="http://demo.rockettheme.com/wordpress/wp_corvus/wp-content/rockettheme/rt_corvus_wp/frontpage/sidebar-b/img1.jpg" alt="image"></span></a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Corvus`.
* Enter `fp-sidebar-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.


#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket]. In this particular instance, we elected to go with the **Simple** content provider in order to create custom items that aren't directly sourced from posts.

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

**Simple Item Content**

Simple items make it possible to create objects within a RokSprocket widget that don't source directly from existing posts. Here are the options used in the **Movie** tab in this widget.

| Field     | Setting |  
| :-------- | :------ |  
| Tab Label | Movie   |  
| Icon      | None    |  
| Link      | None    |  

Description:

~~~ .html
<h3 class="nomargintop nomarginbottom">Responsive Layout</h3><strong class=
"hidden-tablet">Mobile, Tablet &amp; Desktop</strong>

<p><a href=
"http://demo.rockettheme.com/wordpress/wp_corvus/features/"><span class=
"rt-image-b"><img alt="image" src=
"http://demo.rockettheme.com/wordpress/wp_corvus/wp-content/rockettheme/rt_corvus_wp/frontpage/sidebar-b/img2.jpg"></span></a></p>

<p><span class="hidden-tablet">A single template that a</span><span class=
"rt-displayinline visible-tablet">A</span>dapts to different viewing
devices<span class="rt-displayinline visible-large">, such as
mobile</span>.</p><span class="readon-wrapper"><a class="readon2" href=
"http://demo.rockettheme.com/wordpress/wp_corvus/features/">+</a></span>
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `Latest News` in the **Title** field.
* Set the **Title Variation** option to **Title 4**.
* Set the **Padding Variation** option to **No Padding Bottom**.
* Enter `fp-roksprockettabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg