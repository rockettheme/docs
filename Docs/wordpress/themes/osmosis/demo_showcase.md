---
title: Osmosis: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Osmosis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

#### RokSprocket (Strips)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate posts or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | None        |
| Image       | None        |
| Link        | None        |

**Description**

~~~ .html
<div class="rt-icon-badge"><span class="fa fa-camera-retro"></span></div><h2>Animations</h2><p><span>Osmosis is proliferated with contemporary<span class="hidden-tablet">, non-intrusive</span> animations to add creative content interaction.</span></p>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting     |
| :----------       | :---------- |
| Theme             | Default     |
| Display Limit     | ∞           |
| Preview Length    | ∞           |
| Strip HTML Tags   | No          |
| Previews Per Page | 3           |
| Items Per Row     | 3           |
| Arrow Navigation  | Hide        |
| Pagination        | Show        |
| Animation         | Randomize   |
| Autoplay          | Disable     |
| Autoplay Delay    | 5           |
| Image Resize      | Disable     |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Widget Variations** to **RT-Center**.
* Enter `fp-showcase-a fp-showcase-animate` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/