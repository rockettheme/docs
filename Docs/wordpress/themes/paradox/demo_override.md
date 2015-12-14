---
title: Paradox: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Paradox Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/paradox:Paradox

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Paradox Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override   | Option                 | Setting                                                                   |
| :--------- | :--------------------- | :------------------------------------------------------------------------ |
| Default    | Background Level       | High                                                                      |
| Default    | Body Level             | High                                                                      |
| Default    | CSS Style              | Style 8                                                                   |
| Default    | Link Color             | `#689cb9`                                                                 |
| Default    | Read More Style        | Button                                                                    |
| Default    | Article Style          | Blank                                                                     |
| Default    | Thumbnail Size         | Width: `400`, Height: `131`, Position: None                               |
| Default    | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                         |
| Default    | Font Settings          | Font Family: Paradox, Font Size: Default                                  |
| Default    | Use WordPress Comments | On                                                                        |
| Default    | Comments Style         | Standard                                                                  |
| Default    | Custom CSS             | Blank                                                                     |

### Gizmos

![gizmos][gizmos]

| Override   | Option                | Setting                                                                                                                                                                                                        |
| :--------- | :-------------------- | :--------------------------------------------                                                                                                                                                                  |
| Default    | Page Class Suffix     | Enable: Off                                                                                                                                                                                                    |
| Default    | Feed Links            | Show: On                                                                                                                                                                                                       |
| Default    | IE6 Warning           | Show: On, Delay: `2000`                                                                                                                                                                                        |
| Default    | Smart-Load Images     | Show: Off, Offset Y: 50, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper,.module-content ul.menu .image,.roknewspager-div a,#rokintroscroller,.feature-block .image-full` |
| Default    | Custom Title Tag      | Blank                                                                                                                                                                                                          |
| Default    | Typography Shortcodes | On                                                                                                                                                                                                             |
| Default    | Shortcodes in Widgets | On                                                                                                                                                                                                             |
| Default    | RokStyle              | On                                                                                                                                                                                                             |
| Default    | Google Analytics      | Enabled: Off, UA Code: Blank                                                                                                                                                                                   |
| Front Page | Page Class Suffix     | `jun11-home`                                                                                                                                                                                                   |

### Scrolling Modules

![scrolling](setscrolling.png)

| Style   | Option               | Setting                                                                              |
| :------ | :------------------- | :--------------------                                                                |
| Default | Top Position         | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |
| Default | Showcase Position    | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |
| Default | Feature Position     | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |
| Default | Bottom Position      | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |

### Layouts

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 5:7     |  
| Default | Header Positions     | Positions: 1, 12      |  
| Default | Showcase Positions   | Positions: 2, 8:4     |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 3, 6:3:3   |  
| Default | MainBottom Positions | Positions: 3, 4:4:4   |  
| Default | Bottom Positions     | Positions: 3, 3:3:6   |  
| Default | Footer Positions     | Positions: 2, 6:6     |  

### iPhone

![mobile][mobile]

| Override | Option                                     | Setting                                     |
| :------- | :----------------------------------------- | :------------------------------------------ |
| Default  | iPhone Custom Theme                        | On                                          |
| Default  | iPhone Scalable                            | Off                                         |
| Default  | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default  | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default  | Positions Aliases - Mobile Top             | top-a                                       |
| Default  | Positions Aliases - Mobile Header          | header-a                                    |
| Default  | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default  | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default  | Positions Aliases - Mobile Footer Position | drawer                                      |
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
| Front Page | Template Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[style]: assets/setstyle.png
[assignments]: assets/setassignments.png
[advanced]: assets/setadvanced.png
[mobile]: assets/setmobile.png
[layouts]: assets/setlayouts.png
[gizmos]: assets/setgizmos.png
