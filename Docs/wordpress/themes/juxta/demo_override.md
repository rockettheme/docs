---
title: Juxta: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Juxta Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/juxta:Juxta

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Juxta Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override   | Option                 | Setting                                                                |
| :-------   | :--------------------- | :------------------------------------------------                      |
| Default    | Background Level       | High                                                                   |
| Default    | Background Style       | Style 2                                                                |
| Default    | Body Level             | High                                                                   |
| Default    | CSS Style              | Style 2                                                                |
| Default    | Link Color             | Link Color: `#701110`                                                  |
| Default    | Thumbnail Size         | Width: `122`, Height: `189`, Position: `Left`                          |
| Default    | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                      |
| Default    | Article Surround Style | Default                                                                |
| Default    | Header Graphic Image   | On                                                                     |
| Default    | Font Settings          | Font Family: Georgia, Font Size: Default                               |
| Default    | Use WordPress Comments | On                                                                     |
| Default    | Comments Style         | Standard                                                               |

### Gizmos

![gizmos][gizmos]

| Override   | Option                | Setting                                       |
| :--------- | :-------------------- | :-------------------------------------------- |
| Default    | Page Class Suffix     | Enable: Off                                   |
| Default    | Feed Links            | Show: On                                      |
| Default    | IE6 Warning           | Show: On, Delay: `2000`                       |
| Default    | Smart-Load Images     | Show: Off, Offset Y: 50, XPath Ignores: Blank |
| Default    | Custom Title Tag      | Blank                                         |
| Default    | Typography Shortcodes | On                                            |
| Default    | Shortcodes in Widgets | On                                            |
| Default    | RokStyle              | On                                            |
| Default    | Google Analytics      | Enabled: Off, UA Code: Blank                  |

### Layouts

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 1, 12      |
| Default     | Showcase Positions   | Positions: 3, 4:4:4   |
| Default     | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default     | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions    | Positions: 3, 4:4:4   |
| Default     | MainBody Positions   | Positions: 2, 8:4     |
| Default     | MainBottom Positions | Positions: 2, 4:8     |
| Default     | Bottom Positions     | Positions: 2, 6:6     |
| Default     | Footer Positions     | Positions: 3, 4:4:4   |

### iPhone

![mobile][mobile]

| Override    | Option                                     | Setting                                                           |
| :---------- | :----------                                | :----------                                                       |
| Default     | iPhone Custom Theme                        | On                                                                |
| Default     | iPhone Scalable                            | Off                                                               |
| Default     | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 33%                       |
| Default     | Header Background                          | From: `#dbdbdb`, To: `#ffffff`, Start: Left Top, End: Left Bottom |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                                            |
| Default     | Positions Aliases - Mobile Top             | top-a                                                             |
| Default     | Positions Aliases - Mobile Header          | header-a                                                          |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                                                 |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                                                   |
| Default     | Positions Aliases - Mobile Footer Position | footer-a                                                          |
| Default     | Positions Aliases - Mobile Copyright       | copyright                                                         |

### Advanced

![advanced][advanced]

| Override   | Option                  | Setting                                                           |
| :--------- | :---------------------- | :---------------------------------------------------------------- |
| Default    | Gantry Cache            | Enabled: On, Cache Time: 900                                      |
| Default    | Gantry GZipper          | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On |
| Default    | Input Styiling          | Enabled: On, Exclusions: `'.content_vote','\#rt-popup'`           |
| Default    | Display Content         | On                                                                |
| Default    | Display Mainbody        | On                                                                |
| Default    | RTL Support             | On                                                                |
| Default    | Build Title Spans       | On                                                                |
| Default    | RT Typography           | Enabled: On, Typography Style: Light                              |
| Default    | RT Plugins Styling      | On                                                                |
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Content                                |
| Default    | Disable Texturize       | Off                                                               |

### Assignments

![][assignments]

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpg
[mobile]: assets/setmobile.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
