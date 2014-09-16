---
title: Tessellate: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Tessellate Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override   | Option                   | Setting                                                                                                    |  
| :--------- | :----------------------- | :--------------------------------------------------------------------------------------------------------- |  
| Default    | Logo                     | Type: Preset 1                                                                                             |  
| Default    | Accent Style             | Accent 1 Color: `#01acde`, Accent 2 Color: `#bb3b79`, Accent 3 Color: `#1d182c`, Accent 4 Color: `#ede6ea` |  
| Default    | Demo Style               | Preset 1                                                                                                   |  
| Default    | Header Mode              | Header Mode Type: Static                                                                                   |  
| Default    | Header Colors and Type   | Color 1: `#262b3f`, Color 1: `#a9b8ef`, Type: Preset 1                                                     |  
| Default    | Header Bottom Gap        | `160`                                                                                                      |  
| Default    | Header Style             | Text Color: `#72698a`, Background Color: `#1d182c`                                                         |  
| Default    | Top Style                | Text Color: `#ffffff`, Background Color: `transparent`                                                     |  
| Default    | Showcase Style           | Text Color: `#72698a`, Background Color: `#1d182c`                                                         |  
| Default    | Feature Surround Style   | Background Color: `#f7f1f5`                                                                                |  
| Default    | Feature Style            | Text Color: `#1d182c`, Background Color: `#ffffff`                                                         |  
| Default    | BodyTop Surround Style   | Background Color: `#1d182c`                                                                                |  
| Default    | MainBody Surround Style  | Background Color: `#efe9ed`                                                                                |  
| Default    | MainBody Style           | Overlay: Light, Background Color: `#ffffff`                                                                |  
| Default    | BodyBottom Style         | Background Color: `#01acde`                                                                                |  
| Default    | Extension Surround Style | Background Color: `#1d182c`                                                                                |  
| Default    | Footer Surround Style    | Background Color: `#f7f1f5`                                                                                |  
| Default    | Footer Style             | Text Color: `#808080`, Background Color: `#1c1d1f`                                                         |  
| Default    | Bottom Style             | Text Color: `#ffffff`, Background Color: `#1c1d1f`                                                         |  
| Default    | Responsive Menu          | Panel                                                                                                      |  
| Default    | Featured Image Size      | Width: `750`, Height: `297`, Position: None                                                                |  
| Default    | Font Settings            | Font Family: Tessellate, Font Size: Default                                                                |  
| Default    | Pagination               | Enabled: On, Show Count: On, Side Pages: 8                                                                 |  
| Default    | Use WordPress Comments   | On                                                                                                         |  
| Default    | Custom CSS               | Blank                                                                                                      |  
| Front Page | Header Mode              | Animated                                                                                                   |  
| Front Page | Header Bottom Gap        | `0`                                                                                                        |  

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
| Front Page  | Page Suffix           | `menu-home -sep14-home`                        |

### Layouts

![][layouts]

| Override   | Option                   | Setting               |  
| :--------- | :----------------------- | :-------------------- |  
| Default    | Header Positions         | Positions: 3, 2:3:7   |  
| Default    | Top Positions            | Positions: 3, 2:7:3   |  
| Default    | Utility Positions        | Positions: 4, 3:3:3:3 |  
| Default    | Showcase Positions       | Positions: 4, 3:3:3:3 |  
| Default    | Feature Positions        | Positions: 4, 3:3:3:3 |  
| Default    | Utility Positions        | Positions: 4, 3:3:3:3 |  
| Default    | MainTop Positions        | Positions: 4, 3:3:3:3 |  
| Default    | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |  
| Default    | Mainbody Positions       | Positions: 2, 8:4     |  
| Default    | MainBottom Positions     | Positions: 4, 3:3:3:3 |  
| Default    | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |  
| Default    | Extension Positions      | Positions: 4, 3:3:3:3 |  
| Default    | Bottom Positions         | Positions: 4, 3:3:3:3 |  
| Default    | Footer Positions         | Positions: 2, 6:6     |  
| Default    | Copyright Positions      | Positions: 2, 6:6     |  
| Front Page | Top Positions            | Positions: 3, 6:4:2   |  
| Front Page | Showcase Positions       | Positions: 3, 4:3:5   |  
| Front Page | Feature Positions        | Positions: 2, 8:4     |  

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
| Front Page  | Template Page Type | Front Page  |
| Front Page  | Template Page Type | Home Page   |

[demo]: assets/tessellate2.jpeg
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[assignments]: assets/setassignments.jpeg
[style]: assets/setstyle.jpeg
