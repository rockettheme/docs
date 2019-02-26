---
title: Vermilion: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Extension Section
-----

![][demo]

:   1. **RokSprocket (Tabs)** [12%, 7%, se]
    2. **** [12%, 50%, se]

Here is the widget breakdown for the Extension section:

* RokSprocket (Tabs)
* Gantry Divider
* RokSprocket (Lists)

#### RokSprocket (Tabs)

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
Setup
~~~

*Description*

~~~ .html
<div class="rt-icon-badge rt-badge-left">
    <a href="#"></a>
</div>
<h2 class="title"><a href="#">RocketLauncher</a></h2>
<p>A RocketLauncher is a custom, full WordPress package that installs a near
equivalent of the demo onto your server.</p>
<p class="hidden-tablet hidden-phone">This option allows you to check exactly
how the demo is constructed.</p>
<div class="clear"></div>
<div class="rt-icon-badge rt-badge-left">
    <a href="#"></a>
</div>
<h2 class="title"><a href="#">Documentation</a></h2>
<p>In addition, Vermilion has free online guides to assist in setting up the
template on your site.</p>
<p><a class="readon3" href=
"http://www.rockettheme.com/docs/wordpress/themes/vermilion">Read More</a></p>
<div class="clear"></div>
~~~

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Display Limit   | ∞              |
| Tabs Position   | Top            |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | ∞              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-extension-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket (Lists)

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Title** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Title*

~~~ .html
Grid System
~~~

*Description*

~~~ .html
The widget layout is split into rows of up to 6 grid blocks. Each grid block has per override width controls.
~~~

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |
| :------------------ | :------ |
| Theme               | Default |
| Display Limit       | ∞       |
| Collapsible Preview | Enable  |
| Preview Length      | ∞       |
| Strip HTML Tags     | Yes     |
| Previews Per Page   | 4       |
| Arrow Navigation    | Show    |
| Pagination          | Show    |
| Autoplay            | 5       |
| Image Resize        | Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `More Features`.
* Enter `fp-extension-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/
