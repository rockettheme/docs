---
title: Somaxiom: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Somaxiom Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override | Option                 | Setting                                           |
| :------- | :--------------------- | :------------------------------------------------ |
| Default  | Body Level             | Highest                                           |
| Default  | Body Style             | Circles                                           |
| Default  | CSS Style              | Style 1                                           |
| Default  | Style Color            | `#CD5A1C`                                         |
| Default  | Article Surround Style | Default                                           |
| Default  | Thumbnail Size         | Width: `208`, Height: `305`, Position: `Right`    |
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |
| Default  | Font Settings          | Font Family: Helvetica, Font Size: Default        |
| Default  | Use WordPress Comments | On                                                |
| Default  | Comments Style         | Standard                                          |
| Default  | Custom CSS             | Blank                                             |

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
| Default    | Analytics             | Enabled: Off, Code: Blank                     |

### Layouts

![layouts][layouts]

| Override | Option               | Setting               |
| :------- | :------------------- | :-------------------- |
| Default  | Top Position         | Positions: 2, 5:7     |
| Default  | Header Position      | Positions: 3, 3:6:3   |
| Default  | Showcase Position    | Positions: 4, 3:3:3:3 |
| Default  | Feature Position     | Positions: 4, 3:3:3:3 |
| Default  | Utility Position     | Positions: 4, 3:3:3:3 |
| Default  | MainTop Position     | Positions: 4, 3:3:3:3 |
| Default  | MainBody Position    | Positions: 2, 4:8     |
| Default  | MainBottom Position  | Positions: 4, 3:3:3:3 |
| Default  | Bottom Position      | Positions: 4, 3:3:3:3 |
| Default  | Footer Position      | Positions: 3, 4:4:4   |

### iPhone

![mobile][mobile]

| Override    | Option                                     | Setting                                                           |
| :---------- | :----------                                | :----------                                                       |
| Default     | iPhone Enabled                             | On                                                                |
| Default     | iPhone Scalable                            | Off                                                               |
| Default     | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 33%                       |
| Default     | Header Background                          | From: `#89B6B6`, To: `#89B6B6`, Start: Left Top, End: Left Bottom |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                                            |
| Default     | Positions Aliases - Mobile Top             | top-a                                                             |
| Default     | Positions Aliases - Mobile Header          | header-a                                                          |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                                                 |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                                                   |
| Default     | Positions Aliases - Mobile Footer Position | drawer                                                            |
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
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                   |  
| Default    | Disable Texturize       | Off                                                               |  

### Assignments

![][assignments]

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpeg
[advanced]: assets/setadvanced.png
[mobile]: assets/setiphone.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
