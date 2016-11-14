---
title: Kinetic: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Kinetic Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Kinetic:Kinetic

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Kinetic Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][template2]

:   1. **Logo** [6%, 18%, se]
    2. **Menu** [6%, 35%, se]
    3. **Copyright** [91%, 45%, se]
    4. **To-Top Scroller** [91%, 16%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

| Style       | Option              | Setting                                    |
| :---------- | :----------         | :----------                                |
| Default     | Background Level    | High                                       |
| Default     | Body Level          | High                                       |
| Default     | CSS Style           | Style 8                                    |
| Default     | Link Color          | `#5e8080`                                  |
| Default     | Showcase Color      | Color 1                                    |
| Default     | Article Title Style | Color 1                                    |
| Default     | Font Settings       | Font Family: Helvetica, Font Size: Default |

### Features

![][features]

| Style       | Option           | Position    | Setting                                                                                           |
| :---------- | :----------      | :---------- | :----------                                                                                       |
| Default     | Logo             | header-a    | Show: On, Auto Size: On, Centered: On                                                             |
| Default     | Date             | top-d       | Show: Off, Client-side Date: Off                                                                  |
| Default     | Font-Sizer       | feature-b   | Show: Off                                                                                         |
| Default     | Login Panel      | top-c       | Show: On, Login Button Text: `Member Login`, Logout Button Text: `Logout`                         |
| Default     | Copyright        | copyright   | Show: On, `Designed by RocketTheme`                                                               |
| Default     | SmartLoad        |             | Show: Off, Offset Y: 10, Component Ignores: `com_contact`, XPath Ignores: `ul.menutop span.image` |
| Default     | To-Top Scroller  | copyright   | Show: On, `Scroll to Top`                                                                         |
| Default     | System Messages  | drawer      | Show: On                                                                                          |
| Default     | Reset Settings   | copyright   | Show: Off, `Reset Settings`                                                                       |
| Default     | IE6 Warning      |             | Show: On, Delay: `2000`                                                                           |
| Default     | Google Analytics |             | Enable: Off                                                                                       |

### Menu

![][menu]

| Style       | Option                    | Setting                                            |
| :---------- | :----------               | :----------                                        |
| Default     | Menu Control              | Show: On, Type: Split-Menu                         |
| Default     | Enable ID                 | Off                                                |
| Default     | Select a Menu             | Main Menu                                          |
| Default     | Module Cache              | On                                                 |
| Default     | Main Menu Position        | header-d                                           |
| Default     | Sub Menu Position         | navigation                                         |
| Default     | Sidebar Menu Position     | sidebar-a                                          |
| Default     | Top Bar Pill              | Show: On, Duration: `250`, Animation: Sine.easeOut |
| Default     | Navigation Bar Pill       | Show: On, Duration: `250`, Sine.easeOut            |
| Default     | Sidebar Menu Class Suffix | `box5`                                             |

### Layouts

![][layouts]

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 3:9     |
| Default     | Header Positions     | Positions: 2, 3:9     |
| Default     | Showcase Positions   | Positions: 1, 12      |
| Default     | Feature Positions    | Positions: 2, 6:6     |
| Default     | MainTop Positions    | Positions: 3, 4:4:4   |
| Default     | MainBody Positions   | Positions: 3, 6:3:3   |
| Default     | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | Footer Positions     | Positions: 3, 3:3:6   |

### Mobile

![][mobile]

| Style       | Option               | Position          | Setting                                                       |
| :---------- | :----------          | :----------       | :----------                                                   |
| Default     | iPhone Custom Theme  |                   | On                                                            |
| Default     | Scalable Content     |                   | Off                                                           |
| Default     | Standard View Switch | mobile-copyright  | Enable: Off, Position: mobile-copyright                       |
| Default     | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Cube                         |
| Default     | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 33%                  |
| Default     | Header Background    |                   | From: #e8e8e8, To: #ffffff, Start: left top, End: left bottom |
| Default     | Copyright Background |                   | From: #ffffff, To: #f0f0f0, Start: left top, End: left bottom |
| Default     | Positions Aliases    | mobile-drawer     | drawer                                                        |
| Default     | Positions Aliases    | mobile-top        | top-a                                                         |
| Default     | Positions Aliases    | mobile-header     | header-b                                                      |
| Default     | Positions Aliases    | mobile-navigation | mobile-navigation                                             |
| Default     | Positions Aliases    | mobile-showcase   | header-a                                                      |
| Default     | Positions Aliases    | mobile-feature    | header-a                                                      |
| Default     | Positions Aliases    | mobile-bottom     | header-a                                                      |
| Default     | Positions Aliases    | mobile-footer     | footer-a                                                      |
| Default     | Positions Aliases    | mobile-copyright  | copyright                                                     |

### Advanced

![][advanced]

| Style       | Option             | Setting                                                                 |
| :---------- | :----------        | :----------                                                             |
| Default     | Gantry Cache       | Enabled: Off, Cache Timeout: 900                                        |
| Default     | Input Styling      | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin'` |
| Default     | Display Component  | On                                                                      |
| Default     | Display Mainbody   | On                                                                      |
| Default     | RTL Support        | On                                                                      |
| Default     | Build Titles Spans | On                                                                      |
| Default     | Page Suffix        | Off                                                                     |

[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[template2]: assets/kinetic2.jpeg
[styles]: assets/setstyle.jpeg
[features]: assets/setfeatures.jpeg
[menu]: assets/setmenu.jpeg
[layouts]: assets/setlayouts.jpeg
[mobile]: assets/setmobile.jpeg
[advanced]: assets/setadvanced.jpeg
