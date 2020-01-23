---
title: Enigma: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Enigma Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/enigma:Enigma

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Enigma Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][setstyle]

| Override    | Option                 | Setting                                           |
| :---------- | :----------            | :----------                                       |
| Default     | Background Level       | High                                              |
| Default     | CSS Style              | Style 1                                           |
| Default     | Read More Style        | Button                                            |
| Default     | Load Transition        | On                                                |
| Default     | Pagination             | Style: Full, Side Pages: 8                        |
| Default     | Thumbnail Size         | Width: 125, Height 100, Position: Left            |
| Default     | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |
| Default     | Font Settings          | Font Family: Enigma, Font Size: Default           |
| Default     | Use WordPress Comments | On                                                |
| Default     | Comments Style         | Standard                                          |
| Default     | Custom CSS             |                                                   |

### Gizmos

![][setgizmos]

| Override    | Option                | Setting                                       |
| :---------- | :----------           | :----------                                   |
| Default     | Page Class Suffix     | Enabled: Off, Class: Blank                    |
| Default     | Feed Links            | On                                            |
| Default     | Smart-Load Images     | Show: On, Offset Y: 200, XPath Ignores: Blank |
| Default     | Custom Title Tag      | Blank                                         |
| Default     | Typography Shortcodes | On                                            |
| Default     | Shortcodes in Widgets | On                                            |
| Default     | RokStyle              | On                                            |
| Default     | Google Analytics      | Enabled: Off, UA Code: Blank                  |
| Front Page  | Page Suffix           | Enabled: On, Class: `jun12-home`              |

### Layouts

![][setlayouts]

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 1, 12      |
| Default    | Header Positions     | Positions: 2, 2:10    |
| Default    | Showcase Positions   | Positions: 1, 12      |
| Default    | Feature Positions    | Positions: 3, 4:4:4   |
| Default    | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 8:4     |
| Default    | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default    | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions     | Positions: 3, 4:4:4   |
| Default    | Copyright Positions  | Positions: 3, 4:4:4   |
| Front Page | Footer Positions     | Positions: 3, 6:3:3   |

### Mobile

![][setmobile]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | Android Custom Theme                       | On                                          |
| Default     | Scalable Content                           | Off                                         |
| Default     | Image Resize                               | Enabled: On, Min-Width: 80, Percentage: 25% |
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

![][setadvanced]

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
| Front Page  | Theme Page Types | Home Page, Front Page |

[menu]: ../../start/menu.md
[override]: http://docs.gantry.org/gantry4/configure
[setadvanced]: assets/setadvanced.jpeg
[setmobile]: assets/setmobile.jpeg
[setlayouts]: assets/setlayouts.jpeg
[setstyle]: assets/setstyle.jpeg
[setgizmos]: assets/setgizmos.jpeg