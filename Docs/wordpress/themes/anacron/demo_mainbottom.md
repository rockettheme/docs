---
title: Anacron: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Anacron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/anacron:Anacron

---

Main Bottom Section
-----

![][demo]

:   1. **RokSprocket** [14%, 5%, se]
    2. **RokSprocket** [14%, 94%, sw]

Here is the widget breakdown for the Main Bottom section:

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
About
~~~

*Description*

~~~ .html
<div class="gantry-width-40 gantry-width-block">
    <div class="rt-about-img">
        <div class="rt-center">
            <img alt="image" src=
            "http://(Your Site URL)/wp-content/rockettheme/rt_anacron_wp/frontpage/mainbottom/img1.jpg">
            <span class="rt-about-info">Modern. Powerful.</span>
        </div>
    </div>
</div>

<div class="gantry-width-60 gantry-width-block">
    <h2 class="nomargintop">Replicate the Demo.</h2>

    <p><span class="rt-label-1">RocketLauncher</span></p>

    <p><span class="rt-label-2">Multiple Platforms</span></p>

    <p>The RocketLauncher is a customized WordPress install, that replaces the
    default sample data with the data from the demo, alongside images, the
    plugins and theme. It is a quick way to replicate the demo onto your
    server.</p>
</div>

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
| Preview Length  | 0              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-roksprocket-tabs` in the **Custom Variations** field.
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
The widget layout is split into rows of up to 6 grid blocks. Each grid…
~~~

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |
| :------------------ | :------ |
| Theme               | Default |
| Display Limit       | ∞       |
| Collapsible Preview | Enable  |
| Preview Length      | 15      |
| Strip HTML Tags     | Yes     |
| Previews Per Page   | 5       |
| Arrow Navigation    | Show    |
| Pagination          | Show    |
| Autoplay            | 5       |
| Image Resize        | Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Lists widget in the **Choose Widget** field.
* Set the **Title** to `Why Anacron`.
* Enter `fp-roksprocket-lists icon-puzzle-piece` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_8.jpeg
[roksprocket]: ../../plugins/roksprocket/