---
title: Epsilon: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Epsilon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/epsilon:Epsilon

---

Main Top Section
-----

![][demo]

Here is the widget breakdown for the Main Top section:

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Title** and **Description** fields of these items are custom. We have listed the options used on one of the Simple items below.

**Title**

~~~ .html
Custom Shapes
~~~

**Description**

~~~ .html
<h5 class="rt-uppercase">Quick, Easy &amp; Visually Effective</h5><p class="rt-small-text hidden-tablet">Epsilon uses a combination of custom template images, overlays and SVG masks to proliferate hexagons throughout the theme.</p>
~~~

| Option     | Setting                                                    |
| :--------- | :--------                                                  |
| Background | None                                                       |
| Image      | Custom                                                     |
| Position   | Above                                                      |
| Animation  | BounceIn                                                   |
| Link       | `http://www.rockettheme.com/docs/wordpress/themes/epsilon` |

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting   |
| :--------------- | :-------- |
| Display Limit    | ∞         |
| Theme            | Showcase  |
| Article Titles   | Show      |
| Article Text     | Show      |
| Preview Length   | ∞         |
| Strip HTML Tags  | No        |
| Arrow Navigation | Show      |
| Pagination       | Hide      |
| Animation        | Crossfade |
| Autoplay         | Enable    |
| Autoplay Delay   | 5         |
| Image Resize     | Disable   |
| Default Link     | None      |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-maintop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/