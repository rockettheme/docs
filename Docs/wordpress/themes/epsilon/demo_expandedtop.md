---
title: Epsilon: Recreating the Demo - Expanded Top
description: Your Guide to Recreating Elements of the Epsilon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/epsilon:Epsilon

---

Expanded Top Section
-----

![][demo]

:   1. **Text** [10%, 20%, se]
    2. **RokSprocket** [28%, 6%, se]

Here is the widget breakdown for the Expanded Top section:

* Text
* RokSprocket

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="rt-width-80">A diverse array of features to enrich your side, provide great flexibility as well as ease of use and swift customization.</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `What People Are Saying About Us` in the **Title** field.
* Set the **Align Variation** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Description** fields of these items are custom. Below is one example of the content present in one of the Simple item's description field.

**Description**

~~~ .html
<span class="rt-testimonial-item">A beautiful and rich selection of typography,
based on Bootstrap, to emphasise <span class="hidden-tablet">and
embellish</span> content.</span> <span class="rt-testimonial-img"></span>
<span class="rt-testimonial-author">Leo Parry</span><span class=
"rt-testimonial-position">CEO of Hexeris</span>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |
| :---------------- | :----------- |
| Display Limit     | ∞            |
| Theme             | Default      |
| Preview Length    | ∞            |
| Strip HTML Tags   | No           |
| Previews Per Page | 3            |
| Items Per Row     | 3            |
| Arrow Navigation  | Hide         |
| Pagination        | Show         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |
| Default Title     | None         |
| Default Link      | None         |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Strips widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/