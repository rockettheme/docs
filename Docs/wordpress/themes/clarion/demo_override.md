---
title: Clarion: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Clarion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/clarion:Clarion

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Clarion Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override    | Option                 | Setting                                           |
| :---------- | :----------            | :----------                                       |
| Default     | Main Colors            | Body Style: Light, Color: `#00AFF0`               |
| Default     | Background Style       | Wavy Lines Light                                  |
| Default     | Load Transition        | On                                                |
| Default     | Pagination             | Style: Full, Side Pages: 8                        |
| Default     | Thumbnail Size         | Width: 275, Height: 192, Position: Left           |
| Default     | Web Fonts              | Show: Off, WebFonts Source: Google Font Directory |
| Default     | Font Settings          | Font Family: Clarion, Font Size: Default          |
| Default     | Use WordPress Comments | On                                                |

### Gizmos

![gizmos][gizmos]

| Override    | Option                | Setting                                       |
| :---------- | :----------           | :----------                                   |
| Default     | Page Suffix           | Enabled: Off, Class: Blank                    |
| Default     | Feed Links            | On                                            |
| Default     | Load Images           | Show: On, Offset Y: 200, XPath Ignores: Blank |
| Default     | Custom Title Tag      | Blank                                         |
| Default     | Typography Shortcodes | On                                            |
| Default     | Shortcodes in Widgets | On                                            |
| Default     | RokStyle              | On                                            |
| Default     | Google Analytics      | Enabled: Off, UA Code: Blank                  |
| Front Page  | Page Suffix           | Enabled: On, Class: `sep12-home`              |

### Layouts

![layouts][layouts]

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 6:6     |
| Default    | Navigation Positions | Positions: 2, 4:8     |
| Default    | Header Positions     | Positions: 4, 3:3:3:3 |
| Default    | Showcase Positions   | Positions: 1, 12      |
| Default    | Feature Positions    | Positions: 2, 6:6     |
| Default    | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 8:4     |
| Default    | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default    | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions     | Positions: 4, 3:3:3:3 |
| Default    | Copyright Positions  | Positions: 3, 4:4:4   |
| Front Page | Feature Positions    | Positions: 2, 3:9     |


### Mobile

![mobile][mobile]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | Android Custom Theme                       | On                                          |
| Default     | Scalable Content                           | Off                                         |
| Default     | Images Resize                              | Enabled: On, Min-Width: 80, Percentage: 12% |
| Default     | Positions Aliases - Mobile Drawer          | Drawer                                      |
| Default     | Positions Aliases - Mobile Top             | mobile-top                                  |
| Default     | Positions Aliases - Mobile Header          | navigation-a                                |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Feature         | mobile-feature                              |
| Default     | Positions Aliases - Mobile Utility         | mobile-utility                              |
| Default     | Positions Aliases - Mobile Extension       | analytics                                   |
| Default     | Positions Aliases - Mobile Bottom          | bottom-b                                    |
| Default     | Positions Aliases - Mobile Footer Position | footer-position-a                           |
| Default     | Positions Aliases - Mobile Copyright       | Copyright-c                                 |

### Advanced

![advanced][advanced]

| Override    | Option                  | Setting                                                                                         |
| :---------- | :----------             | :----------                                                                                     |
| Default     | Gantry Cache            | Enabled: On, Cache Time: 900                                                                    |
| Default     | Gantry GZipper          | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On                               |
| Default     | Input Styiling          | Enabled: On, Exclusions: `'.content_vote','\#rt-popup','\#rt-popuplogin','\#send_message_form'` |
| Default     | Display Content         | On                                                                                              |
| Default     | Display Mainbody        | On                                                                                              |
| Default     | RTL Support             | On                                                                                              |
| Default     | Build Title Spans       | On                                                                                              |
| Default     | RT Typography           | Enabled: On, Typography Style: Light                                                            |
| Default     | RT Plugins Styling      | On                                                                                              |
| Default     | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                                                 |
| Default     | Disable Texturize       | Off                                                                                             |
| Default     | IE6 Redirect            | On                                                                                              |

### Assignments

![assignments][assignments]

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpeg
[mobile]: assets/setmobile.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
