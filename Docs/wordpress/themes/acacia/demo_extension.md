---
title: Acacia: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Acacia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/acacia:Acacia

---

Extension Section
-----

Here is the widget breakdown for the Extension section:

* RokSprocket - Tabs
* Gantry Divider 
* RokSprocket - Lists

#### RokSprocket - Tabs

![][demo]

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

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
| Preview Length  | ∞              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Tab Label**

~~~ .html
Features
~~~

**Description**

~~~ .html
<div class="gantry-width-40">
    <div class="gantry-width-spacer">
        <div class="rt-center">
            <div class="canvas-graph" data-canvas-graph=
            '{"icon":"icon-apple","iconSize":70,"radius":110,"size":30,"start":70}'>
            </div>
        </div>
    </div>
</div>

<div class="gantry-width-60">
    <div class="gantry-width-spacer">
        <div class="visible-desktop">
            <h3 class="title">Introduction</h3>

            <p>RokSprocket is a multi-content display plugin that is bundled
            with a selection of default layouts, with the ability to expand. It
            also sports an advanced, custom user interface.</p>
        </div>

        <h3 class="title">Features</h3>

        <p>Features is a showcase style layout, perfect for content, image or
        content and image display in slideshow format.</p>
    </div>
</div>

<div class="clear"></div>
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-roksprocket-tabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket - Lists

![][demo2]

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |
| :------------------ | :------ |
| Theme               | Default |
| Collapsible Preview | Enable  |
| Display Limit       | ∞       |
| Preview Length      | 50      |
| Strip HTML Tags     | Yes     |
| Previews Per Page   | 5       |
| Arrow Navigation    | Show    |
| Pagination          | Show    |
| Autoplay            | 5       |
| Image Resize        | Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Titles**, **Links**, and **Descriptions** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Title**

~~~ .html
Grid System
~~~

**Link**

~~~ .html
http://demo.rockettheme.com/live/wordpress/acacia/features/
~~~

**Description**

~~~ .html
Gantry splits the theme layout into rows of up to 6 grid blocks. Each grid block has per override width controls.
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Gantry Extras`.
* Set the **Box Variation** option to **Box 1**.
* Set the **Title Variation** option to **Title 4**.
* Enter `fp-roksprocket-lists` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/