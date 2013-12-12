---
title: Alerion: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/alerion:Alerion

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

* RokSprocket
* Gantry Divider
* Alerion Floating Module

### RokSprocket

The main feature showcase located near the top of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

Here is a look at the **Features Layout Options** for this widget.

| Option           |   Setting |  
| :--------------- | :-------- |  
| Display Limit    |         ∞ |  
| Theme            |  Showcase |  
| Article Titles   |      Show |  
| Article Text     |      Show |  
| Preview Length   |         ∞ |  
| Strip HTML Tags  |        No |  
| Arrow Navigation |      Show |  
| Pagination       |      Hide |  
| Animation        | Crossfade |  
| Autoplay         |   Disable |  
| Autoplay Delay   |         5 |  
| Image Resize     |   Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Custom Variations** field to `fp-showcase`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Alerion Floating Module

The **Alerion Floating Module** is a widget available in the main Widgets listing that adds the **Floating Module Top** and **Floating Module Bottom** widget positions to the page. While this widget in itself does not make any direct aesthetic changes, it facilitates the creation of widgets that do contain content which will float down the side of the page as the user scrolls down until they combine.

There are two settings you will want to adjust in order to match what you see in the demo.

The **Ending Position** on the demo is set to **feature**. The **Stopping Offset (px)** is set to -25. Doing this will let WordPress know that the top floating widget will stop moving once it meets the bottom floating module, at the **feature** area of the site.

[demo]: assets/demo_2.jpeg
[roksprocket]: ../../plugins/roksprocket/