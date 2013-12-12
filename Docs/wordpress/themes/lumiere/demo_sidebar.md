---
title: Lumiere: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Lumiere Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/lumiere:Lumiere

---

Sidebar Section
-----

Here is the widget breakdown for the Sidebar section:

* Custom Menu
* Gantry Divider
* RokSprocket

#### Custom Menu
![][sidebar1]

The Custom Menu widget allows us to add an extra menu in the sidebar. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Set the **Box Variation** option to **Box 1**.
* Set the **Custom Variations** field to `fp-sidebar-menu`.
* Leaving all other options at their default settings, click **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket
![][sidebar2]

This widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | :------ |  
| Theme               | Default |  
| Display Limit       | ∞       |  
| Collapsible Preview | Enable  |  
| Preview Length      | 20      |  
| Strip HTML Tags     | Yes     |  
| Previews Per Page   | 4       |  
| Arrow Navigation    | Show    |  
| Pagination          | Show    |  
| Autoplay            | Disable |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket widget in the **Choose Widget** field.
* Set the **Custom Variations** field to `nomarginall medpaddingall`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[sidebar1]: assets/demo_10.jpeg
[sidebar2]: assets/demo_11.jpeg
[roksprocket]: ../../plugins/roksprocket/
