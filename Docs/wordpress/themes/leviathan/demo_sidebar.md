---
title: Cerulean: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Cerulean Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/cerulean:Cerulean

---

Sidebar Section
-----

Here's the widget breakdown for the Sidebar section:

* Gantry Menu
* RokSprocket

#### Gantry Menu
![][sidebar1]
You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying a menu for the sidebar there. 

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting                                                                 |  
| :---------------- | :---------------------------------------------------------------------- |  
| Title             | Quick Menu                                                              |  
| Menu              | Quick Menu                                                              |  
| Menu Theme        | Split-Menu                                                              |  
| SplitMenu Style   | None                                                                    |  
| Limit Levels      | Yes                                                                     |  
| Start Level       | 0                                                                       |  
| End Level         | 1                                                                       |  
| Show All Children | Yes                                                                     |  
| Show Empty Menu   | No                                                                      |  
| Maximum Depth     | 10                                                                      |  
| Title Variation   | Title 1                                                                 |  
| Custom Variations | `fp-menu rt-small-sidebar-title nomargintop nopaddingtop visible-large` |   

### RokSprocket
![][sidebar2]
The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 
You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option            | Setting |  
| :---------------- | :------ |  
| Theme             | Default |  
| Display Limit     | ∞       | 
| Collapsible Preview | Enable | 
| Preview Length    | 20      |  
| Strip HTML Tags   | Yes     |  
| Previews Per Page | 5       |  
| Arrow Navigation  | Show    |  
| Pagination        | Show    |  
| Autoplay          | Disable |  
| Image Resize      | Disable |  
| Default Link      | None    |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Gantry Extras`
* Select your RokSprocket widget in the **Choose Widget** field.
* Set the **Title Variation** field to **Title 1**.
* Set the **Margin Variation** option to **No Margin Bottom**.
* Set the **Padding Variation** option to **No Padding Bottom**.
* Set the **Custom Variations** field to `rt-flush rt-large-sidebar-title rt-stackbox`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[sidebar1]: assets/demo_sidebar_1.jpeg
[sidebar2]: assets/demo_sidebar_2.jpeg