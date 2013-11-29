---
title: Ionosphere: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Ionosphere Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ionosphere:Ionosphere

---

Extension
-----
![][demo]

Here is the widget breakdown for the Extension section:

* RokGallery
* Gantry Divider
* RokGallery
* Gantry Divider
* RokSprocket

#### RokGallery
This RokGallery widget is used to display a **Grid** of images in order to demonstrate what RokGallery can do to enhance your site's look.

Here is a breakdown of the widget options: 

| Option           |                   Setting |  
| :--------------- | ------------------------: |  
| Title            |  RocketLauncher Available |  
| Link Type        | Link to RokBox Full Image |  
| Show Title       |                       Yes |  
| Show Caption     |                       Yes |  
| Sort By          |                     Order |  
| Sort Direction   |                 Ascending |  
| Slice Limit      |                         1 |  
| Gallery Style    |                      Dark |  
| Gallery Layout   |               Grid Layout |  
| Grid Columns     |                         1 |  
| Title Variation  |                   Title 1 |  
| Margin Variation |          No Margin Bottom |  

This will create the widget, but you will need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokGallery
This RokGallery widget is used to display a **Grid** of images in order to demonstrate what RokGallery can do to enhance your site's look.

Here is a breakdown of the widget options: 

| Option           |                     Setting |  
| :--------------- | --------------------------: |  
| Title            | Adobe Fireworks PNG Sources |  
| Link Type        |   Link to RokBox Full Image |  
| Show Title       |                          No |  
| Show Caption     |                          No |  
| Sort By          |                       Order |  
| Sort Direction   |                   Ascending |  
| Slice Limit      |                           6 |  
| Gallery Style    |                        Dark |  
| Gallery Layout   |                 Grid Layout |  
| Grid Columns     |                           3 |  
| Title Variation  |                     Title 1 |  
| Margin Variation |            No Margin Bottom |  

This will create the widget, but you will need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket
You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview |  Enable |  
| Display Limit       |       ∞ |  
| Preview Length      |      20 |  
| Strip HTML Tags     |     Yes |  
| Previews Per Page   |       2 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            | Disable |  
| Autoplay Delay      |       5 |  
| Image Resize        | Disable |  
| Default Image       |    None |  
| Default Link        |    None |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Integrated RokPlugins`.
* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[rokgallery]: ../../plugins/rokgallery
[demo]: assets/demo_11.jpeg