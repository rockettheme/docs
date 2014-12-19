---
title: Ricochet: Recreating the Demo - Addition Top
description: Your Guide to Recreating Elements of the Ricochet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ricochet:Ricochet

---

Addition Top Section
-----

![Addition Top](assets/demo_7.jpeg)

Here is the widget breakdown for the Addition Top section:

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Title**, **Tags**, **Description** fields of these items are custom, with custom images set, as well. Any tags set appear below the image on the frontend, and are used in sorting.

**Title**

~~~ .html
A Content Block Layout with Auto Positioning
~~~

**Description**

~~~ .html
Grids presents content in up to 10 columns, either as images, text overlays, static text or a combination of each<span class="hidden-tablet"> or all</span>.
~~~

Here is a look at the **Mosaic Layout Options** for this widget.

|      Option     |           Setting            |
| :-------------- | :--------------------------- |
| Theme           | Default                      |
| Display Limit   | ∞                            |
| Columns         | 3                            |
| Preview Length  | ∞                            |
| Only Show Tags  |                              |
| Strip HTML Tags | No                           |
| Blocks Per View | 3                            |
| Article Details | Hide Author and Date         |
| Block Animation | Fade, Scale, Rotate          |
| Ordering        | Default, Title, Date, Random |
| Image Resize    | Disable                      |

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `Characteristics` in the **Title** field.
* Enter `fp-roksprocketmosaic-additiontop title5` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.