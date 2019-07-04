---
title: Spectral: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Sidebar Section
-----

![][demo]

Here is the widget breakdown for the Sidebar section:

* RokSprocket


#### RokSprocket

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Title** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Title**

~~~ .html
Grid System
~~~

**Description**

~~~ .html
Gantry splits the theme layout into rows of up to 6 grid blocks.
~~~

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |
| :------------------ | :------ |
| Theme               | Default |
| Collapsible Preview | Enable  |
| Display Limit       | ∞       |
| Preview Length      | 20      |
| Strip HTML Tags     | Yes     |
| Previews Per Page   | 2       |
| Arrow Navigation    | Show    |
| Pagination          | Show    |
| Autoplay            | 5       |
| Image Resize        | Disable |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Enter `Gantry Extras` as the **Title**.
* Enter `fp-roksprocket-lists hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/
