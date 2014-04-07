---
title: Anacron: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Anacron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/anacron:Anacron

---

Extension Section
-----

![][demo]

:   1. **RokSprocket** [15%, 6%, se]
    2. **Text** [70%, 6%, se]

Here is the widget breakdown for the Extension section:

* RokSprocket
* Text

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Description** field of these items is custom. Everything else is set to its default **None** setting.

**Description**

~~~ .html
RokAjaxSearch is a configurable search widget that uses AJAX to load results in real time via a styled popup. It can be set to local or Google search, inclusive of Web, image, video and blog. Results are paged and can be accessed via buttons or keyboard commands.
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            |      Setting |
| :---------------- | :----------- |
| Theme             |      Default |
| Display Limit     |            ∞ |
| Preview Length    |            ∞ |
| Strip HTML Tags   |           No |
| Previews Per Page |            1 |
| Items Per Row     |            1 |
| Arrow Navigation  |         Hide |
| Pagination        |         Show |
| Animation         | Fade Delayed |
| Autoplay          |      Disable |
| Autoplay Delay    |            5 |
| Image Resize      |      Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Align Variation** option to **RT-Center**.
* Enter `fp-roksprocket-strips rt-big-title` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/
