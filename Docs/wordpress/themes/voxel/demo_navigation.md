---
title: Voxel: Recreating the Demo - Navigation
description: Your Guide to Recreating Elements of the Voxel Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/voxel:Voxel

---

Navigation Section
-----
![][demo1]

Here's the widget breakdown for the Navigation section:

* Gantry Menu
* Gantry Divider
* RokAjaxSearch

The Navigation section remains the same across the entire demo site. For this reason, it exists in the default Widget Override menu. It's also a fairly simple section to set up.

#### Gantry Menu
The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your main menu there. 

More information about menus can be found in our [WordPress Menu guide][menu].

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option | Setting |
|:-------|------:|
| Menu | Main Menu |
| Menu Theme | Fusion |
| Limit Levels | No |
| Start Level | 0 |
| End Level | 0 |
| Show All Children | Yes |
| Show Empty Menu | No |
| Maximum Depth | 10 |
| Load CSS | No |
| Enable JavaScript | Yes |
| Menu Opacity | 1 |
| Menu Effect | Slide and Fade |
| Hide Delay | 500 |
| Menu Animation | Circ.easeOut |
| Menu Duration | 300 |
| Centered Dropdowns | No |
| Level 2 X Offset | -9 |
| Level 2 Y Offset | -12 |
| Submenus X Offset | -8 |
| Submenus Y Offset | -11 |
| Enable ActiveID | No |

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokAjaxSearch
The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you'll want to change to match the demo. This particular instance of RokAjaxSearch requires no adjustments of options. It works just fine at its default settings.

* Leaving everything at its default setting, select **Save**.

[demo1]: assets/demo_2.jpeg
[faq]: faq.md
[menu]: ../../start/menu.md