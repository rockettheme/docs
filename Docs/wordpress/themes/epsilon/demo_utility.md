---
title: Epsilon: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Epsilon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/epsilon:Epsilon

---

Utility Section
-----

![][demo]

Here is the widget breakdown for the Utility section:

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
RokSprocket<span class="hidden-tablet"> Integration</span>
~~~

*Description*

~~~ .html
<div class="rt-center">
    <div class="rt-width-80">
        <h2>RokSprocket Integration</h2>
        <p>RokSprocket is a powerful, content switchblade plugin that provides
        for flexible content display through its assortment of pre-built layout
        types, which are easy to modify, as well as a custom, intuitive
        administrative console.</p>
    </div>
    <div class="gantry-width-25 gantry-width-block">
        <div class="gantry-width-spacer">
            <div class="rt-hexagon">
                <a href="#"></a>
            </div>
            <h5 class="rt-uppercase rt-regular-text">Features</h5>
            <div class="rt-divider"></div>
            <p class="rt-small-text">A showcase or slideshow layout mode for
            displaying image and/or text based content.</p>
        </div>
    </div>
    <div class="gantry-width-25 gantry-width-block">
        <div class="gantry-width-spacer">
            <div class="rt-hexagon">
                <a href="#"></a>
            </div>
            <h5 class="rt-uppercase rt-regular-text">Strips</h5>
            <div class="rt-divider"></div>
            <p class="rt-small-text">A horizontal centric grid based content
            rotator, for the display of multiple image/text content blocks.</p>
        </div>
    </div>
    <div class="gantry-width-25 gantry-width-block">
        <div class="gantry-width-spacer">
            <div class="rt-hexagon">
                <a href="#"></a>
            </div>
            <h5 class="rt-uppercase rt-regular-text">Tabs</h5>
            <div class="rt-divider"></div>
            <p class="rt-small-text">Custom content items in a tabbed format,
            whether top, bottom, left or right, for flexible content
            display.</p>
        </div>
    </div>
    <div class="gantry-width-25 gantry-width-block">
        <div class="gantry-width-spacer">
            <div class="rt-hexagon">
                <a href="#"></a>
            </div>
            <h5 class="rt-uppercase rt-regular-text">Mosaic</h5>
            <div class="rt-divider"></div>
            <p class="rt-small-text">A dynamic content grid layout type, to
            display sortable and animated image and/or text content blocks.</p>
        </div>
    </div>
    <div class="clear"></div>
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
* Enter `fp-utility` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_4.jpeg
[roksprocket]: ../../plugins/roksprocket/