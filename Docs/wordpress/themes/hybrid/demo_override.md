---
title: Hybrid: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Hybrid Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hybrid:Hybrid

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Hybrid Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override | Option                 | Setting                                           |  
| :------- | :--------------------- | :------------------------------------------------ |  
| Default  | Background Level       | Highest                                           |  
| Default  | Body Level             | Highest                                           |  
| Default  | Header Color Style     | Style 4                                           |  
| Default  | Body Color Style       | Style 2                                           |  
| Default  | Body Accent Style      | Style 4                                           |  
| Default  | Footer Color Style     | Style 4                                           |  
| Default  | Read More Style        | Button                                            |  
| Default  | Article Style          | Blank                                             |  
| Default  | Header Width           | Full                                              |  
| Default  | Body Width             | Full                                              |  
| Default  | Footer Width           | Full                                              |  
| Default  | Fixed Footer           | Off                                               |  
| Default  | Thumbnail Size         | Width: `660`, Height: `128`, Position: `None`     |  
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |  
| Default  | Font Settings          | Font Family: Hybrid, Font Size: Default           |  
| Default  | Use WordPress Comments | On                                                |  
| Default  | Comments Style         | Standard                                          |  
| Default  | Custom CSS             | Blank                                             |  

### Gizmos

![gizmos][gizmos]

| Override   | Option                | Setting                                       |  
| :--------- | :-------------------- | :-------------------------------------------- |  
| Default    | Feature Panel         | Enable: On, Delay: `250`, Default: Open       |  
| Default    | Lower Panel           | Enable: On, Delay: `250`, Default: Open       |  
| Default    | Page Suffix           | Enable: Off                                   |  
| Default    | Feed Links            | Show: On                                      |  
| Default    | IE6 Warning           | Show: On, Delay: `2000`                       |  
| Default    | Smart-Load Images     | Show: Off, Offset Y: 50, XPath Ignores: Blank |  
| Default    | Custom Title Tag      | Blank                                         |  
| Default    | Typography Shortcodes | On                                            |  
| Default    | Shortcodes in Widgets | On                                            |  
| Default    | RokStyle              | On                                            |  
| Default    | Google Analytics      | Enabled: Off, UA Code: Blank                  |  
| Front Page | Page Suffix           | Enable: On, Class: `may10-home`               |  

### Layouts

![layouts][layouts]

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 2, 3:9     |
| Default     | Showcase Positions   | Positions: 1, 12      |
| Default     | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default     | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainBody Positions   | Positions: 2, 9:3     |
| Default     | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Bottom Positions     | Positions: 3, 3:3:6   |
| Default     | LowerPanel Positions | Positions: 1, 12      |
| Default     | Footer Positions     | Positions: 2, 6:6     |

### iPhone

![mobile][mobile]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | iPhone Scalable                            | Off                                         |
| Default     | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default     | Positions Aliases - Mobile Top             | top-a                                       |
| Default     | Positions Aliases - Mobile Header          | header-a                                    |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Footer Position | drawer                                      |
| Default     | Positions Aliases - Mobile Copyright       | copyright                                   |

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
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                   |  
| Default    | Disable Texturize       | Off                                                               |  

### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.png
[assignments]: assets/setassignments.png
[advanced]: assets/setadvanced.png
[mobile]: assets/setiphone.png
[layouts]: assets/setlayouts.png
[gizmos]: assets/setgizmos.png
