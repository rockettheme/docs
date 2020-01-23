---
title: Nuance: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate posts or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting     |
| :---------- | :---------- |
| Image       | Custom      |
| Link        | Custom      |

**Title**

~~~ .html
<span class="sprocket-scrollbar-title1"><i class="fa fa-map-marker fa-fw"></i> Colorful<span class="hidden-tablet"> Infusion</span></span><span class="sprocket-scrollbar-title2">Transparent<span class="hidden-tablet"> Areas</span></span>
~~~

**Description**

~~~ .html
<span class="sprocket-scroller-content">The <a href="#">transparent</a> nature of the Nuance design allows the background colors to bleed through to the forefront, to <a href="#">complement and embellish</a> your content.</span>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting       |
| :----------      | :----------   |
| Display Limit    | ∞             |
| Theme            | Scroller      |
| Article Titles   | Show          |
| Article Text     | Show          |
| Preview Length   | ∞             |
| Strip HTML Tags  | No            |
| Arrow Navigation | Show on Hover |
| Pagination       | Show          |
| Animation        | Crossfade     |
| Autoplay         | Disable       |
| Autoplay Delay   | 5             |
| Image Resize     | Disable       |

>> The **Scroller** theme is unique to Nuance and was created to give the RokSprocket mode a certain set of attributes that enables it to look the way it does in this theme. You can find more information about overriding themes [here](../../plugins/roksprocket/layout_modes.md#custom-layout-theme-overrides).


You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-roksprocket-features-scroller` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/
