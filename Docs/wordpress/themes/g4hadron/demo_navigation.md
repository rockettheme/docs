---
title: Hadron: Recreating the Demo - Navigation
description: Your Guide to Recreating Elements of the Hadron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hadron:Hadron

---

Navigation Section
-----

![][demo]

:   1. **Gantry Menu** [30%, 6%, se]
    2. **Gantry Social Buttons** [30%, 70%, se]
    3. **RokAjaxSearch** [30%, 94%, sw]

Here is the widget breakdown for the Navigation section:

* Gantry Menu
* Gantry Divider
* Gantry Social Buttons
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

#### Gantry Social Buttons

The Gantry Social Buttons widget creates a set of social buttons on the top of the page. Filling this out is fairly straightforward. Once you have clicked and dragged the **Gantry Social Buttons** widget in place, you will want to add your various social URLs to their respective fields. Once this is done, simply hit **Save** and check the site. 

>> NOTE: The Icon fields can be filled in using FontAwesome icons. For example, a Facebook logo will appear if `icon-facebook` is placed in the field.

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `fp-rokajaxsearch hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_2.jpeg
