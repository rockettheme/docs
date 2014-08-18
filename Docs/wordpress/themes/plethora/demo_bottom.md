---
title: Plethora: Recreating the Demo - Content Bottom
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Content Bottom Section
-----

![][demo]

Here is the widget breakdown for the Content Bottom section:

#### RokSprocket (Strips)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom headline text without having to create separate articles or pages to do so. Here are the details of one of the items.

| Option      | Setting     |
| :---------- | :---------- |
| Image       | Custom      |
| Link        | None        |

**Title**

~~~ .html
<span class="rt-strips-tag">Strips</span><span>Display content grids in a horizontal row<span class="visible-large"> structure</span></span>
~~~

**Description**

~~~ .html
A RokSprocket layout mode with support for images and text.
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |
| :----------       | :----------  |
| Theme             | Default      |
| Display Limit     | 10           |
| Preview Length    | 20           |
| Strip HTML Tags   | No           |
| Previews Per Page | 5            |
| Items Per Row     | 5            |
| Arrow Navigation  | Show         |
| Pagination        | Hide         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Widget Variations** to **No Padding All, No Margin All**.
* Enter `fp-roksprocket-strips-bottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_6.jpeg
