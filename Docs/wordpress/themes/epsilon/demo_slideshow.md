---
title: Epsilon: Recreating the Demo - Slideshow
description: Your Guide to Recreating Elements of the Epsilon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/epsilon:Epsilon

---

Slideshow Section
-----

![][demo]

Here is the widget breakdown for the Slideshow section:

#### RokSprocket

The main feature showcase located near the top of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

>> NOTE: In the Epsilon demo, we used six different RokSprocket widgets to work with each of the presets. Below, we have listed instructions to create one of these widgets found in the demo. The `fps-preset1` custom variation sets the preset used to display the widget in the first preset.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Title** and **Description** fields of these items are custom. The **Background** and **Image** fields allow you to link to separate images to represent both the background and the foreground image that appears in each item.

**Title**

~~~ .html
A Modern Approach to Design.
~~~

**Description**

~~~ .html
Epsilon is a modern, sectioned based design, with a diverse infusion of background textures and patterns. These enrich and differentiate your site whilst maintaining an overall conservative approach, for flexible site application.
~~~

| Option     | Setting   |
| :--------- | :-------- |
| Position   | Right     |
| Animation  | FlipInX   |
| Link       | #         |

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting        |
| :--------------- | :------------- |
| Display Limit    | ∞              |
| Theme            | Animation      |
| Article Titles   | Show           |
| Article Text     | Show           |
| Preview Length   | ∞              |
| Strip HTML Tags  | No             |
| Arrow Navigation | Hide           |
| Pagination       | Show           |
| Animation        | Crossfade      |
| Autoplay         | Enable         |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Features widget in the **Choose Widget** field.
* Enter `fp-slideshow fps-preset1` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_2.jpeg
[roksprocket]: ../../plugins/roksprocket/
