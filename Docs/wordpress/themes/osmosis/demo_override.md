---
title: Osmosis: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Osmosis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Osmosis Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

|  Override  |         Option         |                                                  Setting                                                   |
| :--------- | :--------------------- | :--------------------------------------------------------------------------------------------------------- |
| Default    | Logo                   | Type: Osmosis Theme                                                                                     |
| Default    | Accent Style           | Accent 1 Color: `#4BA5AD`, Accent 2 Color: `#3a949f`, Accent 3 Color: `#318499`, Accent 4 Color: `#2c7799` |
| Default    | Demo Style             | Preset 1                                                                                                   |
| Default    | Main Menu Automation   | Enable: On                                                                                                 |
| Default    | Page Surround          | Background Color: `#faefe8`, Page Alignment: Center Alignment, Type: Preset 1                              |
| Default    | Header Surround        | Background Color: `#121212`, Parallax: On, Parallax Speed: `-0.3`, Type: Preset 1                          |
| Default    | SidePanel Style        | Show: Off, Text Color: `#807878`, Background Color: `#121212`                                              |
| Default    | Header Style           | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default    | Top Style              | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default    | Utility Style          | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default    | Showcase Style         | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default    | Feature Style          | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default    | MainBody Style         | Overlay: Light                                                                                             |
| Default    | Bottom Style           | Text Color: `#6f849b`, Background Color: `#ffffff`                                                         |
| Default    | Footer Style           | Text Color: `#6f849b`, Background Color: `#ffffff`                                                         |
| Default    | Copyright Style        | Text Color: `#6f849b`, Background Color: `transparent`                                                     |
| Default    | Responsive Menu        | Panel                                                                                                      |
| Default    | Featured Image Size    | Width: `750`, Height: `297`, Position: None                                                                |
| Default    | Font Settings          | Font Family: Osmosis, Font Size: Default                                                                   |
| Default    | Pagination             | Enabled: On, Show Count: On, Side Pages: 8                                                                 |
| Default    | Use WordPress Comments | On                                                                                                         |
| Default    | Custom CSS             | Blank                                                                                                      |
| Front Page | SidePanel Style        | Show: On, Text Color: `#807878`, Background Color: `#121212`                                               |

### Gizmos

![][gizmos]

|  Override  |         Option        |                    Setting                     |
| :--------- | :-------------------- | :--------------------------------------------- |
| Default    | Chart                 | On                                             |
| Default    | Coming Soon Page      | Show: Off, Date: 1, Month: January, Year: 2020 |
| Default    | Email Subscription    | Show: On                                       |
| Defualt    | Feedburner URI        | Blank                                          |
| Default    | Page Suffix           | Enabled: Off, Class: Blank                     |
| Default    | Feed Links            | On                                             |
| Default    | Custom Title Tag      | Blank                                          |
| Default    | Shortcodes in Widgets | On                                             |
| Default    | RokStyle              | On                                             |
| Default    | Google Analytics      | Enabled: Off, UA Code: Blank                   |
| Front Page | Page Suffix           | `menu-home jul14-home`                         |

### Layouts

![][layouts]

|  Style  |          Option          |        Setting        |
| :------ | :----------------------- | :-------------------- |
| Default | Header Positions         | Positions: 2, 3:9     |
| Default | Top Positions            | Positions: 1, 12      |
| Default | Utility Positions        | Positions: 4, 3:3:3:3 |
| Default | Showcase Positions       | Positions: 1, 12      |
| Default | Feature Positions        | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions        | Positions: 4, 3:3:3:3 |
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default | MainBody Positions       | Positions: 1, 12      |
| Default | MainBottom Positions     | Positions: 4, 3:3:3:3 |
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default | Extension Positions      | Positions: 4, 3:3:3:3 |
| Default | Bottom Positions         | Positions: 4, 3:3:3:3 |
| Default | Footer Positions         | Positions: 3, 4:4:4   |
| Default | Copyright Positions      | Positions: 4, 3:3:3:3 |

### Advanced

![][advanced]

| Override |          Option         |                   Setting                   |
| :------- | :---------------------- | :------------------------------------------ |
| Default  | Layout Mode             | Fluid Responsive                            |
| Default  | Maintenance Mode        | Off                                         |
| Default  | Display Content         | On                                          |
| Default  | Display Mainbody        | On                                          |
| Default  | RTL Support             | Off                                         |
| Default  | Disable Auto Paragraphs | Enabled: On, Content Type: Both             |
| Default  | Disable Texturize       | Off                                         |
| Default  | Selectivizr             | On                                          |
| Default  | Less Compiler           | CSS Compression: On, Compile: 2, Debug: Off |
| Default  | IE7 Redirect            | On                                          |
| Default  | Demo Styling            | On                                          |

### Assignments

![][assignments]

|  Override  |       Option       |  Setting   |
| :--------- | :----------------- | :--------- |
| Front Page | Theme Page Type | Front Page |
| Front Page | Theme Page Type | Home Page  |

[demo]: assets/osmosis2.jpeg
[menu]: ../../start/menu.md
[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[assignments]: assets/setassignments.jpg
[style]: assets/setstyle.jpeg
