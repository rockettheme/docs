---
title: Hadron: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Hadron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hadron:Hadron

---

Feature Section
-----

![][demo]

: 1. **Text** [20%, 8%, se]
  2. **RokSprocket** [41%, 8%, se]

Here is the widget breakdown for the Feature section:

* Text
* RokSprocket

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p class="fp-feature-content">The theme also supports a simple coming soon or offline style page with a time counter.</p>
<p class="fp-feature-content">It has been specifically styled to match Hadron.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Latest Featured Works` in the **Title** field.
* Set the **Margin Variation** option to **No Margin Bottom**.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Title** and **Image** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Title**

~~~ .html
Paradigm
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            |      Setting |
| :---------------- | :----------- |
| Theme             |      Default |
| Display Limit     |            ∞ |
| Preview Length    |            ∞ |
| Strip HTML Tags   |          Yes |
| Previews Per Page |            3 |
| Items Per Row     |            3 |
| Arrow Navigation  |         Show |
| Pagination        |         Hide |
| Animation         | Fade Delayed |
| Autoplay          |      Disable |
| Autoplay Delay    |            5 |
| Image Resize      |      Disable |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Strips widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/