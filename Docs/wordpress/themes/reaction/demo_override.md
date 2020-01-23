---
title: Reaction: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Reaction Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/reaction:Reaction

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Reaction Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override |         Option         |                     Setting                      |
| :------- | :--------------------- | :----------------------------------------------- |
| Default  | Background Level       | High                                             |
| Default  | Body Level             | High                                             |
| Default  | CSS Style              | Style 4                                          |
| Default  | Link Color             | `#05adc0`                                        |
| Default  | WebFonts               | Show: On, WebFonts Source: Google Font Directory |
| Default  | Font Settings          | Font Family: Bebas, Font Size: Default           |
| Default  | Use WordPress Comments | On                                               |
| Default  | Custom CSS             | Blank                                            |

### Gizmos

![][gizmos]

| Override |         Option        |                             Setting                             |
| :------- | :-------------------- | :-------------------------------------------------------------- |
| Default  | Feed Links            | Show: On                                                        |
| Default  | IE6 Warning           | Show: On, Delay: `2000`                                         |
| Default  | Smart-Load Images     | Show: On, Offset Y: `50`, XPath Ignores: `.widget_roknewspager` |
| Default  | Custom Title Tag      | Blank                                                           |
| Default  | Typography Shortcodes | On                                                              |
| Default  | Shortcodes in Widgets | On                                                              |
| Default  | RokStyle              | On                                                              |
| Default  | Google Analytics      | Enabled: Off, UA Code: Blank                                    |

### Layouts

![][layouts]

|  Style  |        Option        |        Setting        |
| :------ | :------------------- | :-------------------- |
| Default | Top Positions        | Positions: 2, 5:7     |
| Default | Header Positions     | Positions: 2, 5:7     |
| Default | Showcase Positions   | Positions: 3, 4:4:4   |
| Default | Feature Positions    | Positions: 2, 6:6     |
| Default | MainTop Positions    | Positions: 3, 4:4:4   |
| Default | MainBody Positions   | Positions: 2, 8:4     |
| Default | MainBottom Positions | Positions: 3, 4:4:4   |
| Default | Bottom Positions     | Positions: 2, 6:6     |
| Default | Footer Positions     | Positions: 4, 3:3:3:3 |

### Mobile

![][layouts]

| Override |                   Option                   |                   Setting                   |
| :------- | :----------------------------------------- | :------------------------------------------ |
| Default  | iPhone Enabled                             | On                                          |
| Default  | iPhone Scalable                            | Off                                         |
| Default  | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 33% |
| Default  | Positions Aliases - Mobile Drawer          | top-a                                       |
| Default  | Positions Aliases - Mobile Top             | top-a                                       |
| Default  | Positions Aliases - Mobile Header          | header-a                                    |
| Default  | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default  | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default  | Positions Aliases - Mobile Footer Position | top-a                                       |
| Default  | Positions Aliases - Mobile Copyright       | copyright                                   |

### Advanced

![][advanced]

| Override |       Option      |                                  Setting                                  |
| :------- | :---------------- | :------------------------------------------------------------------------ |
| Default  | Gantry Cache      | Enabled: On, Cache Time `900`                                             |
| Default  | Gantry GZipper    | Enabled: On, Cache Time `600`, Expires Time: `1440`, Strip Whitespace: On |
| Default  | Input Styling     | Enabled: On, Exclusions: `'.content_vote,#rt-popup'`                      |
| Default  | Demo Styles       | On                                                                        |
| Default  | Content           | On                                                                        |
| Default  | RTL Support       | On                                                                        |
| Default  | Title Spans       | On                                                                        |
| Default  | Disable Texturize | Off                                                                       |

### Assignments

![][assignmnets]

|  Override  |        Option       |        Setting        |
| :--------- | :------------------ | :-------------------- |
| Front Page | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[assignmnets]: assets/setassignments.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
