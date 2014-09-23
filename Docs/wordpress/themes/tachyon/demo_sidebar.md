---
title: Tachyon: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Tachyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tachyon:Tachyon

---

Sidebar Section
-----

![][demo1]

: 1. **Text 1** [7%, 15%, se]
  2. **RokNewsPager** [24%, 15%, se]
  3. **Gantry Menu** [56%, 15%, se]

Here is the widget breakdown for the Sidebar section:

* Text
* RokNewsPager
* Gantry Menu

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<a href="#">Check out our Blog.</a> We???ve recently added some new features that we???d like to tell you about!
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Site Updates` in the **Title** field.
* Switch the **Notice Box Variation** option to **Notice Box 4**.
* Leaving everything else at its default setting, select **Save**.

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting        |  
| :----------------- | :------------- |  
| Title              | `Main Menu`    |  
| Menu               | Main Menu      |  
| Menu Theme         | Split-Menu     |  
| Limit Levels       | Yes            |  
| Start Level        | 0              |  
| End Level          | 0              |  
| Show All Children  | Yes            |  
| Show Empty Menu    | No             |  
| Maximum Depth      | 10             |  
| Menu Classes       |                |  
| Load CSS           | No             |  
| Enable JavaScript  | Yes            |  
| Menu Opacity       | 1              |  
| Menu Effect        | Slide and Fade |  
| Hide Delay         | 500            |  
| Menu Animation     | Circ.easeOut   |  
| Menu Duration      | 300            |  
| Enable Pill        | No             |  
| Pill Animation     | Quad.easeOut   |  
| Pill Duration      | 200            |  
| Centered Dropdowns | No             |  
| Level 2 X Offset   | -10            |  
| Level 2 Y Offset   | -11            |  
| Submenus X         | 0              |  
| Submenus Y         | 0              |  
| Enable Active ID   | No             |  
| Box Variation      | Box 6          |  
| Title Variation    | Title 3        |  
| Other Variations   | No Hover       |

[roksprocket]: ../../plugins/roksprocket/
[demo1]: assets/demo_4.jpeg
