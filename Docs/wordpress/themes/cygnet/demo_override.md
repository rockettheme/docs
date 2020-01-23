---
title: Cygnet: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Cygnet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Cygnet Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation](http://docs.gantry.org/gantry4/configure).

### Style

![Style](assets/setstyle.jpeg)

| Style   | Option                 | Setting                                                                                   |
| :------ | :--------------------- | :-----------------------------------------------------------------------------            |
| Default | Logo                   | Type: Preset 1                                                                            |
| Default | Demo Body Class        | Preset 1                                                                                  |
| Default | Accent Style           | Accent 1 Color: `#22eab8`, Accent 2 Color: `#3949a0`, Accent 3 Color: `#ffeb3b`           |
| Default | PageSurround Style     | Background Color: `#13112b`                                                               |
| Default | Body Style             | Overlay: Dark                                                                             |
| Default | Top Style              | Text Color: `#ffffff`, Background Color: `#3949a0`                                        |
| Default | Header Style           | Text Color: `#ffffff`, Background Color: `#2d3c8e`, Header Type: Normal Header            |
| Default | Slideshow Style        | Text Color: `#ffffff`, Background Color: `#3949a0`, Background Image: Particles Animation |
| Default | Showcase Style         | Text Color: `#8f8f8f`, Background Color: `#3949a0`                                        |
| Default | Utility Style          | Text Color: `#777496`, Background Color: `#13112b`                                        |
| Default | Feature Style          | Text Color: `#777496`, Background Color: `#13112b`                                        |
| Default | MainTop Style          | Text Color: `#ffffff`, Background Color: `#3949a0`                                        |
| Default | ExpandedTop Style      | Text Color: `#8582a5`, Background Color: `#1d1a37`                                        |
| Default | ExpandedBottom Style   | Text Color: `#777496`, Background Color: `#13112b`                                        |
| Default | MainBottom Style       | Text Color: `#777496`, Background Color: `#13112b`                                        |
| Default | Extension Style        | Text Color: `#8582a5`, Background Color: `#1d1a37`                                        |
| Default | Footer Style           | Text Color: `#8582a5`, Background Color: `#1d1a37`                                        |
| Default | Copyright Style        | Text Color: `#777496`, Background Color: `#252243`                                        |
| Default | Responsive Menu        | Panel                                                                                     |
| Default | Featured Image Size    | Width: `750`, Height: `297`, Position: NONE                                               |
| Default | Font Settings          | Font Family: Cygnet, Font Size: Default                                                   |
| Default | Pagination             | Enabled: On, Show Count: Off, Side Pages: `8`                                             |
| Default | Use WordPress Comments | On                                                                                        |
| Default | Custom CSS             | Blank                                                                                     |



### Gizmos

![Gizmos](assets/setgizmos.jpeg)

| Override   | Option                | Setting                                        |
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
| Front Page | Page Suffix           | `rt-menu-home -rt-cygnet-home`                 |

### Layouts

![Layouts](assets/setlayouts.jpeg)

| Style      | Option                   | Setting               |
| :------    | :----------------------- | :-------------------- |
| Default    | Top Positions            | Positions: 4, 3:3:3:3 |
| Default    | Header Positions         | Positions: 3, 5:2:5   |
| Default    | Showcase Positions       | Positions: 1, 12      |
| Default    | Utility Positions        | Positions: 1, 12      |
| Default    | Feature Positions        | Positions: 1, 12      |
| Default    | MainTop Positions        | Positions: 1, 12      |
| Default    | ExpandedTop Positions    | Positions: 2, 6:6     |
| Default    | MainBottom Positions     | Positions: 2, 6:6     |
| Default    | ExpandedBottom Positions | Positions: 1, 12      |
| Default    | MainBody Positions       | Positions: 2, 8:4     |
| Default    | Extension Positions      | Positions: 1, 12      |
| Default    | Bottom Positions         | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions         | Positions: 1, 12      |
| Default    | Copyright Positions      | Positions: 3, 2:5:5   |
| Front Page | ExpandedTop Positions    | Positions: 2, 8:4     |
| Front Page | MainBottom Positions     | Positions: 2, 9:3     |
| Front Page | MainBody Positions       | Positions: 2, 4:8     |


### Advanced

![Advanced](assets/setadvanced.jpeg)

| Override   | Option                  | Setting                                     |
| :--------- | :---------------------- | :------------------------------------------ |
| Default    | Layout Mode             | Responsive                                  |
| Default    | Maintenance Mode        | Off                                         |
| Default    | Display Content         | On                                          |
| Default    | Display Mainbody        | On                                          |
| Default    | RTL Support             | Off                                         |
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both             |
| Default    | Disable Texturize       | Off                                         |
| Default    | Selectivizr             | On                                          |
| Default    | Less Compiler           | CSS Compression: On, Compile: 2, Debug: Off |
| Default    | IE7 Redirect            | On                                          |
| Default    | Demo Styling            | On                                          |
| Default    | Animate                 | On                                         |
| Default    | Odometer                | On                                          |

### Assignments

![assignments](assets/setassignments.jpeg)

| Override    | Option             | Setting     |
| :---------- | :----------        | :---------- |
| Front Page  | Theme Page Type | Front Page  |
| Front Page  | Theme Page Type | Home Page   |
