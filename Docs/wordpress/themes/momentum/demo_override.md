---
title: Momentum: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Momentum Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/momentum:Momentum

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Momentum Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override    | Option                 | Setting                                           |
| :---------- | :----------            | :----------                                       |
| Default     | Backgrounds            | Enable: On, RokGallery                            |
| Default     | Read More Style        | Button                                            |
| Default     | Load Transition        | On                                                |
| Default     | Pagination             | Style: Full, Side Pages: `8`                      |
| Default     | Thumbnail Size         | Width: `120`, Height: `100`, Position: `Left`     |
| Default     | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |
| Default     | Font Settings          | Font Family: Momentum, Font Size: Default         |
| Default     | Use WordPress Comments | On                                                |
| Default     | Comments Style         | Standard                                          |

### Gizmos

![gizmos][gizmos]

| Override    | Option                | Setting                                       |
| :---------- | :----------           | :----------                                   |
| Default     | Page Suffix           | Enable: Off                                   |
| Default     | Feed Links            | Show: On                                      |
| Default     | Smart-Load Images     | Show: On, Offset Y: 200, XPath Ignores: Blank |
| Default     | Custom Title Tag      | Blank                                         |
| Default     | Typography Shortcodes | On                                            |
| Default     | Shortcodes in Widgets | On                                            |
| Default     | RokStyle              | On                                            |
| Default     | Google Analytics      | Enabled: Off, UA Code: Blank                  |

### Layouts

![layouts][layouts]

| Override    | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 4, 3:3:3:3 |
| Default     | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default     | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default     | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainBody Positions   | Positions: 2, 8:4     |
| Default     | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | Footer Positions     | Positions: 3, 4:4:4   |
| Default     | Copyright Positions  | Positions: 3, 4:4:4   |
| Front Page  | Bottom Positions     | Positions: 2, 8:4     |
| Front Page  | Footer Positions     | Positions: 4, 2:3:4:3 |

### Mobile

![mobile][mobile]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | Android Custom Theme                       | On                                          |
| Default     | Scalable Content                           | Off                                         |
| Default     | Images Resize                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default     | Positions Aliases - Mobile Top             | header-a                                    |
| Default     | Positions Aliases - Mobile Header          | header-c                                    |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Feature         | content-top-a                               |
| Default     | Positions Aliases - Mobile Bottom          | bottom-b                                    |
| Default     | Positions Aliases - Mobile Footer Position | footer-position-a                           |
| Default     | Positions Aliases - Mobile Copyright       | copyright-a                                 |

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

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpeg
[mobile]: assets/setmobile.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
