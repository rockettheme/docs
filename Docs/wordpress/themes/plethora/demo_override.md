---
title: Plethora: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Plethora Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override    | Option                 | Setting                                                      |
| :---------- | :----------            | :----------                                                  |
| Default     | Logo                   | Type: Plethora Theme                                      |
| Default     | Accent Style           | Accent 1 Color: `#e35614`, Accent 2 Color: `#338de0`         |
| Default     | Demo Style             | Preset 1                                                     |
| Default     | Main Menu Automation   | Enable: On                                                   |
| Default     | PageSurround Style     | Background Color: `#f5f5f5`                                  |
| Default     | Top Style              | Text Color: `#808080`, Background Color: `#1c1d1f`           |
| Default     | Header Style           | Text Color: `#808080`, Background Color: `1c1d1f`            |
| Default     | Feature Style          | Text Color: `#ffffff`, Background Color: `1c1d1f`            |
| Default     | MainTop Style          | Text Color: `#a8a8a8`, Background Color: `ffffff`            |
| Default     | MainBody Style         | Overlay: Light                                               |
| Default     | Extension Style        | Text Color: `#ffffff`, Background Color: `#e35614`           |
| Default     | Bottom Style           | Text Color: `#ffffff`, Background Color: `#1c1d1f`           |
| Default     | Footer Style           | Text Color: `#808080`, Background Color: `1c1d1f`            |
| Default     | Responsive Menu        | Panel                                                        |
| Default     | Featured Image Size    | Width: `750`, Height: `297`, Position: None                  |
| Default     | Font Settings          | Font Family: Plethora, Font Size: Default                    |
| Default     | Pagination             | Enabled: On, Show Count: On, Side Pages: 8                   |
| Default     | Use WordPress Comments | On                                                           |
| Default     | Custom CSS             | Blank                                                        |

### Gizmos

![][gizmos]

| Override    | Option                | Setting                                        |
| :---------- | :----------           | :----------                                    |
| Default     | Chart                 | On                                             |
| Default     | Coming Soon Page      | Show: Off, Date: 1, Month: January, Year: 2020 |
| Default     | Email Subscription    | Show: On                                       |
| Defualt     | Feedburner URI        | Blank                                          |
| Default     | Page Suffix           | Enabled: Off, Class: Blank                     |
| Default     | Feed Links            | On                                             |
| Default     | Custom Title Tag      | Blank                                          |
| Default     | Shortcodes in Widgets | On                                             |
| Default     | RokStyle              | On                                             |
| Default     | Google Analytics      | Enabled: Off, UA Code: Blank                   |
| Front Page  | Page Suffix           | `menu-home aug14-home`                         |

### Layouts

![][layouts]

|   Style    |          Option          |        Setting        |
| :--------- | :----------------------- | :-------------------- |
| Default    | Top Positions            | Positions: 3, 6:4:2   |
| Default    | Header Positions         | Positions: 3, 2:7:3   |
| Default    | Showcase Positions       | Positions: 2, 6:6     |
| Default    | Feature Positions        | Positions: 3, 4:4:4   |
| Default    | Utility Positions        | Positions: 4, 3:3:3:3 |
| Default    | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions        | Positions: 3, 4:4:4   |
| Default    | MainBody Positions       | Positions: 1, 12      |
| Default    | MainBottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default    | Extension Positions      | Positions: 4, 3:3:3:3 |
| Default    | Bottom Positions         | Positions: 1, 12      |
| Default    | Footer Positions         | Positions: 3, 4:4:4   |
| Default    | Copyright Positions      | Positions: 3, 2:8:2   |
| Front Page | Showcase Positions       | Positions: 2, 8:4     |
| Front Page | Feature Positions        | Positions: 3, 6:2:4   |
| Front Page | MainTop Positions        | Positions: 3, 6:2:4   |

### Advanced

![][advanced]

| Override    | Option                  | Setting                                     |
| :---------- | :----------             | :----------                                 |
| Default     | Layout Mode             | Responsive                                  |
| Default     | Maintenance Mode        | Off                                         |
| Default     | Display Content         | On                                          |
| Default     | Display Mainbody        | On                                          |
| Default     | RTL Support             | Off                                         |
| Default     | Disable Auto Paragraphs | Enabled: On, Content Type: Both             |
| Default     | Disable Texturize       | Off                                         |
| Default     | Selectivizr             | On                                          |
| Default     | Less Compiler           | CSS Compression: On, Compile: 2, Debug: Off |
| Default     | IE7 Redirect            | On                                          |
| Default     | Demo Styling            | On                                          |
| Front Page  | Display Mainbody        | Off                                         |

### Assignments

| Override    | Option             | Setting     |
| :---------- | :----------        | :---------- |
| Front Page  | Theme Page Type | Front Page  |
| Front Page  | Theme Page Type | Home Page   |

[demo]: assets/plethora2.jpeg
[menu]: ../../start/menu.md
[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[assignments]: assets/setassignments.jpeg
[style]: assets/setstyle.jpeg
