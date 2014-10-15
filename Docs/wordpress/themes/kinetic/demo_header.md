---
title: Kinetic: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Kinetic Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kinetic:Kinetic

---

Header Section
-----

![][demo]

:   1. **Gantry Logo** [30%, 6%, se]
    2. **Gantry Menu** [30%, 30%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

In this instance, the **Per Style Logo** option has been checked.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting        |
| :----------------  | :--------      |
| Menu               | Main Menu      |
| Menu Theme         | SplitMenu      |
| Limit Levels       | Yes            |
| Start Level        | 0              |
| End Level          | 0              |
| Show All Children  | No             |
| Show Empty Menu    | No             |
| Maximum Depth      | 10             |
| Load CSS           | No             |
| Enable JavaScript  | Yes            |
| Menu Opacity       | 1              |
| Menu Effect        | Slide and Fade |
| Hide Delay         | 500            |
| Menu Animation     | Sine.easeOut   |
| Menu Duration      | 300            |
| Enable Pill        | No             |
| Pill Animation     | Back.easeOut   |
| Pill Duration      | 400            |
| Centered Dropdowns | No             |
| Level 2 X Offset   | 10             |
| Level 2 Y Offset   | 8              |
| Submenus X Offset  | 0              |
| Submenus Y Offset  | 2              |
| Enable Active ID   | No             |
| Widget Style       | Flush          |

![][demo2]

There is a submenu that doesn't appear on the front page, as it has no direct children, but will appear on other pages. This is another **Gantry Menu** widget placed in the **Navigation** widget position.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting        |
| :----------------  | :--------      |
| Menu               | Main Menu      |
| Menu Theme         | SplitMenu      |
| Limit Levels       | Yes            |
| Start Level        | 1              |
| End Level          | 1              |
| Show All Children  | No             |
| Show Empty Menu    | No             |
| Maximum Depth      | 10             |
| Load CSS           | No             |
| Enable JavaScript  | Yes            |
| Menu Opacity       | 1              |
| Menu Effect        | Slide and Fade |
| Hide Delay         | 500            |
| Menu Animation     | Sine.easeOut   |
| Menu Duration      | 200            |
| Enable Pill        | No             |
| Pill Animation     | Sine.easeOut   |
| Pill Duration      | 250            |
| Centered Dropdowns | No             |
| Level 2 X Offset   | 10             |
| Level 2 Y Offset   | 8              |
| Submenus X Offset  | 0              |
| Submenus Y Offset  | 2              |
| Enable Active ID   | No             |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_9.png
[menu]: ../../start/menus.md
[faq]: faq.md
