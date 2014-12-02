---
title: Chimera: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Chimera Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Main Bottom Section
-----

![Main Bottom](assets/demo_6.jpeg)

Here is the widget breakdown for the Main Bottom section:

#### RokSprocket (Strips)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option | Setting |
| :----- | :------ |
| Title  | None    |
| Image  | Custom  |
| Link   | None    |

**Description**

~~~ .html
<div class="wow zoomIn">
    <div class="rt-floatleft">
        <div class="rt-grey-box fa fa-tachometer" style="font-style: italic">
        </div>
    </div>

    <div class="rt-strips-desc">
        <h6><a href=
        "http://demo.rockettheme.com/live/wordpress/chimera/features-overview/">
        Replicate the demo <span class="hidden-tablet">with the
        RocketLauncher</span></a></h6><small>Full WordPress Install</small>
    </div>
</div>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |
| :----------       | :----------  |
| Theme             | Default      |
| Display Limit     | ∞            |
| Preview Length    | ∞            |
| Strip HTML Tags   | No           |
| Previews Per Page | 3            |
| Items Per Row     | 3            |
| Arrow Navigation  | Show         |
| Pagination        | Show         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips fp-preset-images` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.
