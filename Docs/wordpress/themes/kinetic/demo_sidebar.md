---
title: Kinetic: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Kinetic Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kinetic:Kinetic

---

Sidebar Section
-----

![][demo]

:   1. **RokNewsPager** [7%, 12%, se]
    2. **Text** [62%, 12%, se]
    3. **Gantry Menu** [7%, 52%, se]
    4. **RokTabs** [35%, 52%, se]
    5. **Gantry Meta** [59%, 52%, se]
    6. **Gantry Recent Comments** [80%, 52%, se]

Here is the widget breakdown for the Sidebar section:

* RokNewsPager
* Text
* Gantry Divider
* Gantry Menu
* RokTabs
* Gantry Meta
* Gantry Recent Comments

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><strong>Plugins</strong> are an important aspect of any WordPress site, and
Kinetic has styled integrated for many of our RocketTheme plugins such as
<em>RokStories, RokAjaxSearch, RokTabs, &amp; RokNewsPager</em></p>

<p><a href="http://rockettheme.com/wordpress">Download</a> our themes <a href=
"http://rockettheme.com/wordpress">Today</a></p>

<p>You can find all of these plugins in our Kinetic theme!</p><img alt=
"Plugins" src=
"http://demo.rockettheme.com/live/wordpress/kinetic/wp-content/rockettheme/rt_kinetic_wp/frontpage/extensions.png">
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Styled Addons`.
* Switch the **Widget Variations** option to **Ribbon 2**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting        |
| :----------------  | :--------      |
| Title              | `Main Menu`    |
| Menu               | Main Menu      |
| Menu Theme         | SplitMenu      |
| Limit Levels       | Yes            |
| Start Level        | 0              |
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
| Pill Animation     | Back.easeOut   |
| Pill Duration      | 250            |
| Centered Dropdowns | No             |
| Level 2 X Offset   | 10             |
| Level 2 Y Offset   | 8              |
| Submenus X Offset  | 0              |
| Submenus Y Offset  | 2              |
| Enable Active ID   | No             |
| Widget Variations  | Box 5          |

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Meta

The **Gantry Meta** widget gives the visitor quick access to common tools such as the site admin and RSS feed. Here are the settings we used with this widget.

| Option            | Setting     |
| :----------       | :---------- |
| Title             | `Meta`      |
| List Class        | `menu`      |
| Widget Variations | Box 5       |

#### Gantry Recent Comments

The **Ganty Recent Comments** widget lists the latest comments in a clean, seamless way. Here are the settings we used with this widget.

| Option                     | Setting       |
| :----------                | :----------   |
| Title                      |               |
| Number of Comments to Show | `1`           |
| Word Limit                 | `7`           |
| List Class                 | `jclist`      |
| Link Class                 | `jcl_comment` |

[demo]: assets/demo_4.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
