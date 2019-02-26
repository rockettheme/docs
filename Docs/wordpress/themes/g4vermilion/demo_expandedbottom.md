---
title: Vermilion: Recreating the Demo - Expanded Bottom
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Expanded Bottom Section
-----

![][demo]

:    1. **Text** [15%, 38%, se]
     2. **RokSprocket (Strips)** [33%, 15%, se]

Here is the widget breakdown for the Expanded Bottom section:

* Text
* RokSprocket (Strips)

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `RokSprocket[span class="rt-title-tag"]Versatile Content Extension for WordPress[/span]` in the **Title** field.
* Set the **Widget Variations** option to **RT-Center**.
* Enter `fp-expandedbottom-01 rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket (Strips)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Mosaic`    |
| Image       | Custom      |
| Link        | #           |

**Description**

~~~ .html
The Mosaic layout displays content in dynamic blocks that adapt to their content size and by frontend filters.
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
| Arrow Navigation  | Hide         |
| Pagination        | Hide         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Widget Variations** to **RT-Center**.
* Enter `fp-expandedbottom-02` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/
