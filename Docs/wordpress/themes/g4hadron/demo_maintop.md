---
title: Hadron: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Hadron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hadron:Hadron

---

Main Top Section
-----

![][demo]

:   1. **RokSprocket** [11%, 8%, se]
    2. **RokSprocket** [25%, 90%, sw]

Here is the widget breakdown for the Main Top section:

* RokSprocket (Tabs)
* Gantry Divider
* RokSprocket (Lists)

#### RokSprocket (Tabs)

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label**, **Link**, and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
Intro
~~~

*Link*

~~~ .html
http://demo.rockettheme.com/live/wordpress/hadron/features/
~~~

*Description*

~~~ .html
<div class="gantry-width-50 gantry-width-block">
    <div class="sprocket-tabs-image"><img alt="image" src=
    "http://demo.rockettheme.com/live/wordpress/hadron/wp-content/rockettheme/rt_hadron_wp/frontpage/maintop/img1.jpg"></div>
</div>

<div class="gantry-width-50 gantry-width-block">
    <div class="sprocket-tabs-content">
        <h3 class="title nomargintop nomarginbottom">About Hadron</h3>

        <p class="rt-large-text nomargintop">A contemporary and corporate
        visual frame.</p>

        <p class="hidden-tablet">Hadron has a selection of preset styles with a
        diverse array of different background colors and shades to dramatically
        change the overall appearance.</p>

        <p class="visible-large">Subtle animations on the various theme
        elements provide enrichment to the site, such as the read more buttons
        or the unveil mechanism for the search input.</p>

        <p>The theme places content as the primary focus.</p>
    </div>
</div>
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

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Title**, **Link**, and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Title*

~~~ .html
Grid System
~~~

*Link*

~~~ .html
http://demo.rockettheme.com/live/wordpress/hadron/features/
~~~

*Description*

~~~ .html
Gantry splits the theme layout into rows of up to 6 grid blocks.
~~~

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |
| :------------------ | :------ |
| Theme               | Default |
| Display Limit       | ∞       |
| Collapsible Preview | Enable  |
| Preview Length      | 12      |
| Strip HTML Tags     | Yes     |
| Previews Per Page   | 5       |
| Arrow Navigation    | Show    |
| Pagination          | Show    |
| Autoplay            | 5       |
| Image Resize        | Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Lists widget in the **Choose Widget** field.
* Set the **Title** to `Gantry Extras`.
* Enter `fp-roksprocket-lists` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/