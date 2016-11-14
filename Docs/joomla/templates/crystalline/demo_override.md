---
title: Crystalline: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Crystalline Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/crystalline:Crystalline

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Crystalline Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][template2]

:   1. **Logo** [6%, 18%, se]
    2. **Menu** [10%, 18%, se]
    3. **Branding** [90%, 18%, se]
    4. **Copyright** [92%, 45%, se]
    5. **Login Panel** [22%, 78%, sw]
    6. **Color Chooser** [6%, 78%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

| Style       | Option        | Setting                                                                 |
| :---------- | :----------   | :----------                                                             |
| Default     | Header        | Background: `#004e63`, Text: `#ffffff`, Link: `#ebe5c3`, Shadows: Dark  |
| Default     | Main          | Background: `#f1e8d6`, Text: `#55473e`, Link: `#000000`, Shadows: Light |
| Default     | Feature       | Background: `#dedede`, Text: `#444444`, Link: `#004e63`, Shadows: Light |
| Default     | Body          | Background: `#ffffff`, Text: `#666666`, Link: `#004e63`, Shadows: Light |
| Default     | Bottom        | Background: `#a61027`, Text: `#ffffff`, Link: `#ebe5c3`, Shadows: Dark  |
| Default     | Font Settings | Font Family: Helvetica, Font Size: Default                              |

### Features

![][features]

| Style       | Option           | Position    | Setting                                                                                           |
| :---------- | :----------      | :---------- | :----------                                                                                       |
| Default     | Logo             | header-a    | Show: On, Auto Size: Off                                                                          |
| Default     | Color Chooser    | header-b    | `Color Chooser`                                                                                   |
| Default     | Overlay Check    |             | Enabled: On                                                                                       |
| Default     | Date             | top-d       | Show: Off, Client-side Date: Off                                                                  |
| Default     | Font-Sizer       | utility-c   | Show: Off                                                                                         |
| Default     | Login Panel      | utility-b   | Show: On, Login Button Text: `Member Login`, Logout Button Text: `Logout`                        |
| Default     | Branding         | copyright   | Show: On                                                                                          |
| Default     | Copyright        | copyright   | Designed by RocketTheme                                                                           |
| Default     | SmartLoad        |             | Show: Off, Offset Y: 10, Component Ignores: `com_contact`, XPath Ignores: `ul.menutop span.image` |
| Default     | To-Top Scroller  | debug       | Show: Off, `Scroll to Top`                                                                        |
| Default     | System Messages  | drawer      | Show: On                                                                                          |
| Default     | Reset Settings   | copyright   | Show: Off, `Reset Settings`                                                                       |
| Default     | IE6 Warning      |             | Show: On, Delay: `2000`                                                                           |
| Default     | Google Analytics |             | Enable: Off                                                                                       |

### Menu

![][menu]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Menu Control      | Show: On, Type: Fusion-Menu                             |
| Default     | Select a Menu     | Main Menu                                               |
| Default     | Position          | navigation                                              |
| Default     | Enable JavaScript | On                                                      |
| Default     | Menu Opacity      | 1                                                       |
| Default     | Menu Effect       | Slide + Fade                                            |
| Default     | Menu Delay        | 500                                                     |
| Default     | Menu Animation    | Quad.easeOut                                            |
| Default     | Pill              | Enable: Off, Duration: `400`, Animation: `Back.easeOut` |
| Default     | Enable ID         | Off                                                     |
| Default     | Module Cache      | On                                                      |

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

| Style       | Option             | Setting                                    |
| :---------- | :----------        | :----------                                |
| Default     | Gantry Cache       | Enabled: On, Cache Timeout: 900            |
| Default     | Input Styling      | Enabled: On, Exclusions: `'.content_vote'` |
| Default     | Display Component  | On                                         |
| Default     | Display Mainbody   | On                                         |
| Default     | RTL Support        | On                                         |
| Default     | Build Titles Spans | On                                         |
| Default     | Page Suffix        | On                                         |

[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[template2]: assets/crystalline2.jpeg
[styles]: assets/setstyle.jpeg
[features]: assets/setfeatures.jpeg
[menu]: assets/setmenu.jpeg
[layouts]: assets/setlayouts.jpeg
[mobile]: assets/setmobile.jpeg
[advanced]: assets/setadvanced.jpeg
