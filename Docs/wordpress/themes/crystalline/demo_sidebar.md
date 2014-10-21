---
title: Crystalline: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Crystalline Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/crystalline:Crystalline

---

Sidebar Section
-----

![][demo]

:   1. **Gantry Menu** [5%, 20%, se]
    2. **Text** [27%, 20%, se]
    3. **Gantry Meta** [54%, 20%, se]
    4. **Gantry Categories** [70%, 20%, se]
    5. **Text** [83%, 20%, se]

Here is the widget breakdown for the Sidebar section:

* Gantry Menu
* Text
* Gantry Meta
* Gantry Categories
* Text

#### Gantry Menu

The Gantry Menu widget provides a menu for your visitors to navigate your site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting           |
| :----------------  | :--------         |
| Title              | `Site Navigation` |
| Menu               | Main Menu         |
| Menu Theme         | SplitMenu         |
| Limit Levels       | Yes               |
| Start Level        | 0                 |
| End Level          | 1                 |
| Show All Children  | No                |
| Show Empty Menu    | No                |
| Maximum Depth      | 10                |
| Load CSS           | No                |
| Enable JavaScript  | Yes               |
| Menu Opacity       | 1                 |
| Menu Effect        | Slide and Fade    |
| Hide Delay         | 500               |
| Menu Animation     | Sine.easeOut      |
| Menu Duration      | 200               |
| Enable Pill        | No                |
| Pill Animation     | Sine.easeOut      |
| Pill Duration      | 250               |
| Centered Dropdowns | No                |
| Level 2 X Offset   | 0                 |
| Level 2 Y Offset   | -1                |
| Submenus X Offset  | 1                 |
| Submenus X Offset  | -1                |
| Enable Active ID   | No                |
| Widget Variations  | Background 1      |

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><img src="http://demo.rockettheme.com/live/wordpress/crystalline/wp-content/rockettheme/rt_crystalline_wp/frontpage/rt1.jpg" alt="Oct10 Demo Image" class="demo-fp-img"/></p>
<p><em class="bold">Delivering versatile WordPress themes since Oct 2009.</em></p>
<p>Crystalline is a creation built using our new feature rich Gantry Framework. Unleash the WordPress power!</p>
<a class="readon" href="#"><span>Read More</span></a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Widget Variations** option to **Background 3**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Meta

The **Gantry Meta** widget gives the visitor quick access to common tools such as the site admin and RSS feed. Here are the settings we used with this widget.

| Option            | Setting      |
| :----------       | :----------  |
| Title             | `Meta`       |
| List Class        | `menu`       |
| Widget Variations | Background 2 |

#### Gantry Categories

The **Gantry Categories** widget displays post categories in an easy-to-use list for visitors. The settings used in the demo are listed below.

| Option            | Setting       |
| :----------       | :----------   |
| Title             | Categories    |
| Display           | List          |
| Order By          | Category Name |
| List Class        | `menu`        |
| Show Post Count   | No            |
| Show Hierarchy    | Yes           |
| Hide Empty        | Yes           |
| Exclude           | Blank         |
| Depth             | `0`           |
| Widget Variations | Background 5  |

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><em class="bold">Cross Browser Compatible</em></p>
<p>This theme is compatible with the major and modern browsers, plus limited support for IE6.</p>
<a class="readon" href="#"><span>Learn More</span></a>
~~~

Leaving everything else at its default setting, select **Save**.


[demo]: assets/demo_7.jpeg
