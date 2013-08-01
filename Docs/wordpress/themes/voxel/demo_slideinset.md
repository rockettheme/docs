---
title: Voxel: Recreating the Demo - Slide Inset
description: Your Guide to Recreating Elements of the Voxel Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/voxel:Voxel

---

SlideInset Section
-----
![][demo2]

The SlideInset section actually creates a RokSprocket module within a RokSprocket module for the visitor. It combines two different RokSprocket elements into a single interface for your visitors to enjoy. The result is a unique look that enhances user experience.

Here's the widget breakdown for the SlideInset section:

* RokSprocket

#### RokSprocket
The **Most Popular** menu located in the main slideshow on the front page is a RokSprocket widget. You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview | Disable |  
| Display Limit       |       ∞ |  
| Preview Length      |       6 |  
| Strip HTML Tags     |     Yes |  
| Previews Per Page   |       3 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            | Disable |  
| Autoplay Delay      |       5 |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Title Variation** option to **Title 6**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo2]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/