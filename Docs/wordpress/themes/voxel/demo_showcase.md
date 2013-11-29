---
title: Ximenia: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ximenia:Ximenia

---

Showcase Section
-----
![][demo2]

Here is the widget breakdown for the Showcase section:

* RokSprocket

#### RokSprocket
The main feature showcase located near the top of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Features Layout Options** for this widget.

| Option           |   Setting |  
| :--------------- | --------: |  
| Theme            | Slideshow |  
| Display Limit    |         3 |  
| Article Titles   |      Show |  
| Article Text     |      Show |  
| Preview Length   |         ∞ |  
| Strip HTML Tags  |       Yes |  
| Arrow Navigation |      Show |  
| Pagination       |      Hide |  
| Animation        | Crossfade |  
| Autoplay         |   Disable |  
| Autoplay Delay   |         5 |  
| Image Resize     |   Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Custom Variations** field to `nopaddingleft nopaddingright nopaddingtop`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo2]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/