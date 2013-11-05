---
title: Oculus: Recreating the Demo - Navigation
description: Your Guide to Recreating Elements of the Oculus Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/oculus:Oculus

---

Navigation Section
-----

![][demo]

:	1. **Gantry Menu** [35%, 5%, se]
	2. **RokAjaxSearch** [35%, 73%, se]

Here's the widget breakdown for the Navigation section:

* Gantry Menu
* Gantry Divider
* RokAjaxSearch

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting   |  
| :---------------- | :-------- |  
| Menu              | Main Menu |  
| Menu Theme        | Dropdown  |  
| SplitMenu Style   | None      |  
| Limit Levels      | No        |  
| Start Level       | 0         |  
| End Level         | 0         |  
| Show All Children | Yes       |  
| Show Empty Menu   | No        |  
| Maximum Depth     | 10        |  
| Custom Chrome     | Menu      |  

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you'll want to change to match the demo.

* Enter `fp-rokajaxsearch` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_2.jpeg