---
title: Crystalline: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Crystalline Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/crystalline:Crystalline

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Crystalline Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override    | Option                 | Setting                                                                                                            |
| :---------- | :----------            | :----------                                                                                                        |
| Default     | Header                 | Background: `#004e63`, Overlay: Lines 4, Header Graphic: Header 1, Text: `#ffffff`, Link: `#ebe5c3`, Shadows: Dark |
| Default     | Main                   | Background: `#f1e8d6`, Overlay: Circles, Text: `#55473e`, Link: `#000000`, Shadows: Light                          |
| Default     | Feature                | Background: `#dedede`, Overlay: Off, Text: `#444444`, Link: `#004e63`, Shadows: Light                              |
| Default     | Body                   | Background: `#ffffff`, Overlay: Off, Text: `#666666`, Link: `#004e63`, Shadows: Light                              |
| Default     | Bottom                 | Background: `#a61027`, Overlay: Lines 4, Text: `#ffffff`, Link: `#ebe5c3`, Shadows: Dark                           |
| Default     | Thumbnail Size         | Width: 177, Height: 114, Position: Left                                                                            |
| Default     | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                                                                  |
| Default     | Font Settings          | Font Family: Helvetica, Font Size: Default                                                                         |
| Default     | Use WordPress Comments | On                                                                                                                 |
| Default     | Custom CSS             | Blank                                                                                                              |

### Gizmos

![][gizmos]

| Override    | Option                | Setting                                       |
| :---------- | :----------           | :----------                                   |
| Default     | Overlay Check         | Enable: On                                    |
| Default     | Page Class Suffix     | Enable: Off                                   |
| Default     | Feed Links            | On                                            |
| Default     | Load Images           | Show: On, Offset Y: 200, XPath Ignores: Blank |
| Default     | Custom Title Tag      | Blank                                         |
| Default     | Typography Shortcodes | On                                            |
| Default     | Shortcodes in Widgets | On                                            |
| Default     | RokStyle              | On                                            |
| Default     | Google Analytics      | Enabled: Off, UA Code: Blank                  |

### Layouts

![][layouts]

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 2, 9:3     |
| Default     | Showcase Positions   | Positions: 1, 12      |
| Default     | Feature Positions    | Positions: 3, 3:3:6   |
| Default     | Utility Positions    | Positions: 2, 9:3     |
| Default     | MainTop Positions    | Positions: 3, 4:4:4   |
| Default     | MainBody Positions   | Positions: 2, 9:3     |
| Default     | MainBottom Positions | Positions: 3, 4:4:4   |
| Default     | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | Footer Positions     | Positions: 4, 3:3:3:3 |

### Mobile

![][layouts]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | iPhone Scalable                            | Off                                         |
| Default     | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 33% |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default     | Positions Aliases - Mobile Top             | top-a                                       |
| Default     | Positions Aliases - Mobile Header          | header-a                                    |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Footer Position | drawer                                      |
| Default     | Positions Aliases - Mobile Copyright       | copyright                                   |

### Advanced

![][advanced]

| Override    | Option                  | Setting                                                                   |
| :---------- | :----------             | :----------                                                               |
| Default     | Gantry Cache            | Enabled: On, Cache Time `900`                                             |
| Default     | Gantry GZipper          | Enabled: On, Cache Time `600`, Expires Time: `1440`, Strip Whitespace: On |
| Default     | Input Styling           | Enabled: On, Exclusions: `'.content_vote,#rt-popup'`                      |
| Default     | Demo Styles             | On                                                                        |
| Default     | Content                 | On                                                                        |
| Default     | RTL Support             | On                                                                        |
| Default     | Title Spans             | On                                                                        |
| Default     | Disable Texturize       | Off                                                                       |

### Assignments

![][assignmnets]

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[assignmnets]: assets/setassignments.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
