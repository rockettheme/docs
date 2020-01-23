---
title: Panacea: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Panacea Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/panacea:Panacea

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Panacea Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

|  Override  |         Option         |                                  Setting                                  |
| :--------- | :--------------------- | :------------------------------------------------------------------------ |
| Default    | Static CSS             | Use Static: Off, Check Changes: On                                        |
| Default    | Main Background        | Background: `#EEEEEE`                                                     |
| Default    | Header                 | Background: `#FFFFFF`, Overlay: Light, Text: `#666666`, Link: `#A70000`   |
| Default    | Body                   | Background: `#FFFFFF`, Overlay: Light, Text: `#555555`, Link: `#A70000`   |
| Default    | Footer                 | Background: `#333333`, Overlay: Dark, Text: `#999999`, Link: `#FFFFFF`    |
| Default    | Widget Box 1           | Background: `#F1F1F1`, Text: `#555555`, Border: `#E3E3E3` Link: `#A70000` |
| Default    | Widget Box 2           | Background: `#999999`, Text: `#DDDDDD`, Border: `#7C7C7C` Link: `#FFFFFF` |
| Default    | Widget Box 3           | Background: `#666666`, Text: `#DDDDDD`, Border: `#555555` Link: `#FFFFFF` |
| Default    | Read More Style        | Button                                                                    |
| Default    | Article Style          | `title3`                                                                  |
| Default    | Article Overlay        | Light                                                                     |
| Default    | Article Info Style     | Layout 3                                                                  |
| Default    | Rotator                | Enabled: Off, Controls: On, Autoplay: Off, Delay: `20`, Interval: `500`   |
| Default    | Header Width           | Full                                                                      |
| Default    | Footer Width           | Full                                                                      |
| Default    | Thumbnail Size         | Width: `101`, Height: `69`, Position: `Right`                             |
| Default    | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                         |
| Default    | Font Settings          | Font Family: Helvetica, Font Size: Default                                |
| Default    | Use WordPress Comments | On                                                                        |
| Default    | Comments Style         | Standard                                                                  |
| Front Page | Rotator                | Enabled: On, Controls: On, Autoplay: Off, Delay: `20`, Interval: `500`    |

**Rotator Backgrounds (Manage Button)**

![][rotator]

|     Background     |
| :----------------- |
| Red Oils           |
| Japanese Gate Bw   |
| Japanese Garden Bw |

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

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 5:7     |
| Default    | Header Positions     | Positions: 2, 4:8     |
| Default    | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default    | Feature Positions    | Positions: 3, 4:4:4   |
| Default    | Utility Positions    | Positions: 1, 12      |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 8:4     |
| Default    | MainBottom Positions | Positions: 2, 7:5     |
| Default    | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions     | Positions: 3, 3:3:6   |
| Front Page | MainBody Positions   | Positions: 2, 7:5     |

### iPhone

![mobile][mobile]

| Override |                   Option                   |                   Setting                   |
| :------- | :----------------------------------------- | :------------------------------------------ |
| Default  | iPhone Custom Theme                        | On                                          |
| Default  | iPhone Scalable                            | Off                                         |
| Default  | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default  | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default  | Positions Aliases - Mobile Top             | top-a                                       |
| Default  | Positions Aliases - Mobile Header          | header-a                                    |
| Default  | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default  | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default  | Positions Aliases - Mobile Footer Position | footer-a                                    |
| Default  | Positions Aliases - Mobile Copyright       | copyright                                   |

### Advanced

![advanced][advanced]

| Override |          Option         |                              Setting                              |
| :------- | :---------------------- | :---------------------------------------------------------------- |
| Default  | Gantry Cache            | Enabled: On, Cache Time: 900                                      |
| Default  | Gantry GZipper          | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On |
| Default  | Input Styiling          | Enabled: On, Exclusions: `'.content_vote','\#rt-popup'`           |
| Default  | Display Content         | On                                                                |
| Default  | Display Mainbody        | On                                                                |
| Default  | RTL Support             | On                                                                |
| Default  | Build Title Spans       | On                                                                |
| Default  | RT Typography           | Enabled: On, Typography Style: Light                              |
| Default  | RT Plugins Styling      | On                                                                |
| Default  | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                   |
| Default  | Disable Texturize       | Off                                                               |

### Assignments

|  Override  |        Option       |        Setting        |
| :--------- | :------------------ | :-------------------- |
| Front Page | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpg
[mobile]: assets/setmobile.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
