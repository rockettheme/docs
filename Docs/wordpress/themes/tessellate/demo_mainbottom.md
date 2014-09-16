---
title: Tessellate: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Main Bottom Section
-----

![][demo]

Here is the widget breakdown for the Main Bottom section:

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
Options
~~~

*Description*

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <h3>Present your media with RokBox</h3>

                <p>RokBox is a fully responsive modal "pop-up" plug-in for WordPress. This very popular plugin can showcase many different media formats ie. images and videos.</p><a class="readon4" href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/">Read More</a>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <h3>Disable the Mainbody or Component areas</h3>

                <p>A common feature provided by Gantry is the ability to disable the mainbody and/or content area on a per-override basis. Ideal for certain frontpage layouts.</p><a class="readon4" href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/">Read More</a>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <h3>A separate LESS file for demo specific CSS</h3>

                <p>Tessellate has a separate file for all demo specific CSS, which is for content elements unique to the demo. If you do not wish to use these, then disable accordingly.</p><a class="readon4" href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/">Read More</a>
            </div>
        </div>
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
* Enter `fp-roksprocket-tabs-mainbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/
