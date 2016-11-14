---
title: Tessellate: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Tessellate Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Tessellate2]

:   1. **Logo**  [6%, 17%, se]
    2. **Menu**  [5%, 62%, se]
    3. **Social Buttons** [91%, 17%, se]
    4. **Copyright** [92%, 35%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][gantrydocs].

### Style

![Style Settings][style]

| Style       | Option                    | Position    | Setting                                                                                                    |
| :---------- | :----------               | :---------- | :----------                                                                                                |
| Default     | Logo                      | header-a    | Show: On, Type: Tessellate Template                                                                        |
| Default     | Accent Style              |             | Accent 1 Color: `#01acde`, Accent 2 Color: `#bb3b79`, Accent 3 Color: `#1d182c`, Accent 4 Color: `#ede6ea` |
| Default     | Demo Style                |             | Preset 1                                                                                                   |
| Default     | PageSurround Style        |             | Background Color: `#f5f5f5`                                                                                |
| Default     | Header Surround Style     |             | Mode: Static, Color 1: `#262b3f`, Color 2: `#a9b8ef`, Type: Preset 1                                       |
| Default     | Header Bottom Gap         |             | Header Bottom Gap: `160`                                                                                   |
| Default     | Header Style              |             | Text Color: `#72698a`, Background Color: `#1d182c`                                                         |
| Default     | Top Style                 |             | Text Color: `#ffffff`, Background Color: `transparent`                                                     |
| Default     | Showcase Style            |             | Text Color: `#72698a`, Background Color: `#1d182c`                                                         |
| Default     | Feature Surround Style    |             | Background Color: `#f7f1f5`                                                                                |
| Default     | Feature Style             |             | Text Color: `#1d182c`, Background Color: `#ffffff`                                                         |
| Default     | BodyTop Surround Style    |             | Background Color: `#1d182c`                                                                                |
| Default     | MainBody Surround Style   |             | Background Color: `#efe9ed`                                                                                |
| Default     | MainBody Style            |             | Overlay: Light, Background Color: `#ffffff`                                                                |
| Default     | BodyBottom Surround Style |             | Background Color: `#01acde`                                                                                |
| Default     | Extension Surround Style  |             | Background Color: `#1d182c`                                                                                |
| Default     | Footer Surround Style     |             | Background Color: `#f7f1f5`                                                                                |
| Default     | Footer Style              |             | Text Color: `#808080`, Background Color: `#1c1d1f`                                                         |
| Default     | Bottom Style              |             | Text Color: `#ffffff`, Background Color: `#1c1d1f`                                                         |
| Default     | Font Settings             |             | Font Family: Tessellate, Font Size: Default                                                                |
| Home        | Header Surround Style     |             | Mode: Animated, Color 1: `#262b3f`, Color 2: `#a9b8ef`, Type: Preset 1                                     |

### Features

![Features Settings][features]

| Style       | Option             | Position    | Setting                                                                       |
| :---------- | :----------        | :---------- | :----------                                                                   |
| Default     | Social Buttons     | footer-a    | Show: Off                                                                     |
| Default     | Chart              |             | Show: On                                                                      |
| Default     | Coming Soon Page   |             | Show: Off                                                                     |
| Default     | Email Subscription |             | Show: On                                                                      |
| Default     | Feedburner URI     |             | Blank                                                                         |
| Default     | System Messages    | drawer      | On                                                                            |
| Default     | Date               | utility-a   | Show: Off, Client-Side Date: Off                                              |
| Default     | Font-Sizer         | utility-b   | Show: Off                                                                     |
| Default     | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`    |
| Default     | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                  |
| Default     | Branding           | copyright-a | Show: Off                                                                     |
| Default     | Copyright          | copyright-b | Show: On, Text: `Copyright &copy; 2014 - Tessellate - Powered by RocketTheme` |
| Default     | To-Top Scroller    | copyright-c | Show: On, Text: `Top`                                                         |
| Default     | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                             |
| Default     | Google Analytics   |             | Enable: Off                                                                   |
| Home        | Social Buttons     | footer-a    | Show: On, Settings: **Listed Below**                                          |

##### Social Buttons Settings

| Option      | Setting                                          |
| :---------- | :----------                                      |
| Target      | New Window                                       |
| Icon 1      | `fa fa-twitter`                                  |
| Text 1      |                                                  |
| Link 1      | `https://twitter.com/rockettheme`                |
| Icon 2      | `fa fa-facebook`                                 |
| Text 2      |                                                  |
| Link 2      | `https://www.facebook.com/RocketTheme`           |
| Icon 3      | `fa fa-rss`                                      |
| Text 3      |                                                  |
| Link 3      | `http://www.rockettheme.com/product-updates?rss` |
| Icon 4      | `fa fa-google-plus`                              |
| Text 4      |                                                  |
| Link 4      | `https://plus.google.com/+rockettheme`           |

### Menu

![Menu Settings][menu2]

| Style       | Option          | Setting                       |
| :---------- | :----------     | :----------                   |
| Default     | Menu Control    | Show: On, Type: Dropdown-Menu |
| Default     | Select a Menu   | Main Menu                     |
| Default     | Position        | header-c                      |
| Default     | Responsive Menu | Panel                         |
| Default     | Enable ID       | Off                           |
| Default     | Module Cache    | On                            |

### Layouts

![Layouts Settings][layouts]

| Style       | Option                   | Setting               |
| :---------- | :----------              | :----------           |
| Default     | Header Positions         | Positions: 3, 2:3:7   |
| Default     | Top Positions            | Positions: 2, 6:6     |
| Default     | Showcase Positions       | Positions: 3, 4:4:4   |
| Default     | Feature Positions        | Positions: 2, 6:6     |
| Default     | Utility Positions        | Positions: 1, 12      |
| Default     | ExpandedTop Positions    | Positions: 2, 6:6     |
| Default     | MainTop Positions        | Positions: 2, 6:6     |
| Default     | MainBody Positions       | Positions: 1, 12      |
| Default     | MainBottom Positions     | Positions: 1, 12      |
| Default     | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Extension Positions      | Positions: 1, 12      |
| Default     | Bottom Positions         | Positions: 1, 12      |
| Default     | Footer Positions         | Positions: 4, 3:3:3:3 |
| Default     | Copyright Positions      | Positions: 2, 6:6     |
| Home        | Top Positions            | Positions: 2, 2:10    |
| Home        | Showcase Positions       | Positions: 3, 4:3:5   |
| Home        | Feature Positions        | Positions: 2, 8:4     |
| Home        | Bottom Positions         | Positions: 4, 4:2:2:4 |
| Home        | Footer Positions         | Positions: 4, 3:3:3:3 |

### Advanced

![Advanced Settings][advanced]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Layout Mode       | Responsive                                              |
| Default     | Display Component | On                                                      |
| Default     | Mainbody Enabled  | On                                                      |
| Default     | RTL Support       | Off                                                     |
| Default     | Page Suffix       | On                                                      |
| Default     | Selectivizr       | On                                                      |
| Default     | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default     | IE7 Redirect      | On                                                      |
| Default     | Demo Styling      | On                                                      |
| Default     | K2 Styling        | Off                                                     |

### Assignments

| Style       | Option      | Setting     |
| :---------- | :---------- | :---------- |
| Home        | Main Menu   | Home        |

[demo25]: assets/tessellate.jpg
[menu]: ../../start/menu.md
[Tessellate2]: assets/tessellate2.jpg
[assignments]: assets/assignments_settings.jpeg
[style]: assets/setstyle.jpeg
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[menu2]: assets/setmenu.jpeg
[features]: assets/setfeatures.jpeg
[setsocial]: assets/setsocial.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
