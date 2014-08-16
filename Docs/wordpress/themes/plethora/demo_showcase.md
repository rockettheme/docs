---
title: Plethora: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Showcase Section
-----

![][demo]

:   1. **RokSprocket (Features)** [10%, 5%, se]
    2. **RokSprocket (Tabs)** [10%, 66%, se]

Here is the widget breakdown for the Showcase section:

* RokSprocket
* Gantry Divider
* RokSprocket

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget using the **WordPress** provider.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting     |
| :----------      | :---------- |
| Display Limit    | ∞           |
| Theme            | Scroller    |
| Article Titles   | Show        |
| Article Text     | Show        |
| Preview Length   | 17          |
| Strip HTML Tags  | Yes         |
| Arrow Navigation | Hide        |
| Pagination       | Show        |
| Animation        | Crossfade   |
| Autoplay         | Disable     |
| Autoplay Delay   | 5           |
| Image Resize     | Disable     |
| Default Link     | `#`         |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

There are some custom adjustments to the line items. We have listed the changes from one of these items below as an example:

**Title**

~~~ .html
<span class="sprocket-pagination-title">Content delivery via a flexible<span class="hidden-tablet sprocket-pagination-title">, dynamic and configurable</span> framework</span>
~~~

The **Image** fields also include custom images used for the RokSprocket module that are not present on the article. 

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-roksprocket-features-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label**, **Link**, and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
Gantry
~~~

*Link*

~~~ .html
#
~~~

*Description*

~~~ .html
<h2 class="title"><span>Advanced <span class="hidden-tablet">theme</span>
framework <span class="visible-large">with vast portfolio of standard
features</span></span></h2>

<p><span class="rt-floatleft"><img alt="image" src=
"http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-roksprocket-tabs-showcase/img-01.jpg"></span><span>Gantry
is the core framework that sits at the heart of the theme, powering all the
major features and functions, providing a versatile set of rich capabilities to
make your site easy to customize<span class="hidden-tablet">, setup and
use</span>. <span class="hidden-tablet">The main asset of Gantry is its
intuitive administrative interface, that provides friendly control
options.</span></span></p>

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
* Set the **Widget Variations** to **Box 3, No Margin All**.
* Enter `fp-roksprocket-tabs-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/