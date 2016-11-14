---
title: Panacea: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Panacea Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][template2]

:   1. **Logo** [6%, 18%, se]
    2. **Menu** [6%, 78%, sw]
    3. **Branding** [92%, 15%, se]
    4. **Copyright** [92%, 71%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

| Style       | Option             | Setting                                                                                    |
| :---------- | :----------        | :----------                                                                                |
| Default     | Use Static CSS     | Use Static: Off, Check Changes: On                                                         |
| Default     | Read More Style    | Button                                                                                     |
| Default     | Article Style      | `title3`                                                                                   |
| Default     | Article Overlay    | Light                                                                                      |
| Default     | Article Info Style | Layout 3                                                                                   |
| Default     | Rotator            | Enable: Off, Controls: On, Autoplay: On, Delay: `20`, Interval: `500`, Order: Oldest First |
| Default     | Header Width       | Full                                                                                       |
| Default     | Footer Width       | Full                                                                                       |
| Default     | Font Settings      | Font Family: Default, Font Size: Default                                                   |
| Home        | Rotator            | Enable: On, Controls: On, Autoplay: On, Delay: `20`, Interval: `500`, Order: Oldest First  |

**Rotator Backgrounds (Manage Button)**

![][rotator]

| Background         |
| :----------        |
| Red Oils           |
| Japanese Gate Bw   |
| Japanese Garden Bw |

### Features

![][features]

| Style       | Option           | Position    | Setting                                                                                                                                                                         |
| :---------- | :----------      | :---------- | :----------                                                                                                                                                                     |
| Default     | Logo             | header-a    | Show: On, Auto Size: On, Centered: Off                                                                                                                                          |
| Default     | Date             | top-a       | Show: Off, Client-side Date: Off                                                                                                                                                |
| Default     | Font-Sizer       | top-b       | Show: Off                                                                                                                                                                       |
| Default     | Login Panel      | top-c       | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                                                                                      |
| Default     | Branding         | copyright   | Show: On                                                                                                                                                                        |
| Default     | Copyright        | copyright   | Show: Off, Text: `Designed by RocketTheme`                                                                                                                                      |
| Default     | SmartLoad        |             | Show: On, Offset Y: 10, Component Ignores: `com_community,com_contact,com_k2,com_tienda`, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper` |
| Default     | To-Top Scroller  | copyright       | Show: Off, `Scroll to Top`                                                                                                                                                      |
| Default     | System Messages  | drawer      | Show: On                                                                                                                                                                        |
| Default     | Reset Settings   | copyright   | Show: Off, `Reset Settings`                                                                                                                                                     |
| Default     | Google Analytics |             | Enable: Off                                                                                                                                                                     |

### Menu

![][menu]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Menu Control      | Show: On, Type: Fusion-Menu                             |
| Default     | Select a Menu     | Main Menu                                               |
| Default     | Position          | header-b                                                |
| Default     | Enable JavaScript | On                                                      |
| Default     | Menu Opacity      | 1                                                       |
| Default     | Menu Effect       | Slide + Fade                                            |
| Default     | Menu Delay        | 400                                                     |
| Default     | Menu Animation    | Quad.easeOut                                            |
| Default     | Menu Duration     | 400                                                     |
| Default     | Pill              | Enable: Off, Duration: `400`, Animation: `Back.easeOut` |
| Default     | Enable ID         | Off                                                     |
| Default     | Module Cache      | On                                                      |

### Layouts

![][layouts]

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 2, 4:8     |
| Default     | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default     | Feature Positions    | Positions: 3, 4:4:4   |
| Default     | Utility Positions    | Positions: 1, 12      |
| Default     | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainBody Positions   | Positions: 2, 8:4     |
| Default     | MainBottom Positions | Positions: 2, 7:5     |
| Default     | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | Footer Positions     | Positions: 3, 3:3:6   |
| Home        | MainBody Positions   | Positions: 2, 7:5     |

### Mobile

![][mobile]

| Style       | Option               | Position          | Setting                                      |
| :---------- | :----------          | :----------       | :----------                                  |
| Default     | iPhone Custom Theme  |                   | On                                           |
| Default     | Scalable Content     |                   | Off                                          |
| Default     | Standard View Switch | mobile-copyright  | Enable: On, Position: mobile-copyright       |
| Default     | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide       |
| Default     | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |
| Default     | Positions Aliases    | mobile-drawer     | drawer                                       |
| Default     | Positions Aliases    | mobile-top        | top-a                                        |
| Default     | Positions Aliases    | mobile-header     | header-b                                     |
| Default     | Positions Aliases    | mobile-navigation | mobile-navigation                            |
| Default     | Positions Aliases    | mobile-showcase   | header-a                                     |
| Default     | Positions Aliases    | mobile-footer     | footer-a                                     |
| Default     | Positions Aliases    | mobile-copyright  | copyright                                    |

### Advanced

![][advanced]

| Style       | Option              | Setting                                                              |
| :---------- | :----------         | :----------                                                          |
| Default     | Gantry Cache        | Enabled: On, Cache Timeout: 900                                      |
| Default     | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |
| Default     | Display Component   | On                                                                   |
| Default     | RTL Support         | On                                                                   |
| Default     | Page Suffix         | On                                                                   |
| Default     | Third Party Support | Off                                                                  |
| Default     | IE7 Redirect        | On                                                                   |

[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[template2]: assets/panacea2.jpeg
[styles]: assets/setstyle.jpeg
[features]: assets/setfeatures.jpeg
[menu]: assets/setmenu.jpeg
[layouts]: assets/setlayouts.jpeg
[mobile]: assets/setmobile.jpeg
[rotator]: assets/setrotator.jpeg
[advanced]: assets/setadvanced.jpeg
