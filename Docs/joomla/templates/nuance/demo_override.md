---
title: Nuance: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Nuance Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Nuance2]

:   1. **Logo**  [7%, 17%, se]
    2. **Social Buttons**  [5%, 77%, se]
    3. **Menu** [7%, 40%, se]
    4. **Copyright** [92%, 55%, sw]
    5. **Branding** [92%, 16%, se]
    6. **To-Top Scroller** [92%, 80%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][gantrydocs].

### Style

![Style Settings][style]

| Style       | Option                    | Position    | Setting                                                                                                 |
| :---------- | :----------               | :---------- | :----------                                                                                             |
| Default     | Logo                      | header-a    | Show: On, Type: Nuance Template                                                                         |
| Default     | Accent Style              |             | Accent 1 Color: `#00afe9`, Accent 2 Color: `#766396`                                                    |
| Default     | Page Surround Style       |             | Background Color Top: `#746496`, Background Color Middle: `#6c7db4`, Background Color Bottom: `#32306e` |
| Default     | Header Surround Style     |             | Background Color: `#09053f`, Type: Preset 1                                                             |
| Default     | MainTop Style             |             | Text Color: `#a8a8a8`, Background Color: `f5f5f5`                                                       |
| Default     | MainBody Style            |             | Overlay: Light                                                                                          |
| Default     | ExpandedBottom Style      |             | Text color: `#f8f8f8`, Background Color: `#09053f`, Type: Nuance                                        |
| Default     | Extension Style           |             | Text Color: `#f8f8f8`, Background Color: `#111111`                                                      |
| Default     | Bottom Style              |             | Text Color: `#a8a8a8`, Background Color: `#ffffff`                                                      |
| Default     | Footer Style              |             | Text Color: `#a8a8a8`, Background Color: `#f5f5f5`                                                      |
| Default     | Font Settings             |             | Font Family: Nuance, Font Size: Default                                                                 |

>> NOTE: The font used in the default logo is called [**Nunito**](http://www.fontsquirrel.com/fonts/nunito).

### Features

![Features Settings][features]

| Style       | Option             | Position    | Setting                                                                    |
| :---------- | :----------        | :---------- | :----------                                                                |
| Default     | Social Buttons     | top-b       | Show: On                                                                   |
| Default     | Chart              |             | Show: On                                                                   |
| Default     | Coming Soon Page   |             | Show: Off                                                                  |
| Default     | Email Subscription |             | Show: On                                                                   |
| Default     | Feedburner URI     |             | Blank                                                                      |
| Default     | System Messages    | drawer      | On                                                                         |
| Default     | Date               | utility-a   | Show: Off, Client-Side Date: Off                                           |
| Default     | Font-Sizer         | utility-b   | Show: Off                                                                  |
| Default     | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |
| Default     | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |
| Default     | Branding           | copyright-a | Show: On                                                                   |
| Default     | Copyright          | copyright-b | Show: On, Text: `Designed by RocketTheme`  |
| Default     | To-Top Scroller    | copyright-c | Show: On, Text: `Top`                                                      |
| Default     | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                          |
| Default     | Google Analytics   |             | Enable: Off                                                                |

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
| Default     | Position        | header-b                      |
| Default     | Responsive Menu | Panel                         |
| Default     | Enable ID       | Off                           |
| Default     | Module Cache    | On                            |

### Layouts

![Layouts Settings][layouts]

| Style       | Option                   | Setting               |
| :---------- | :----------              | :----------           |
| Default     | Top Positions            | Positions: 2, 6:6     |
| Default     | Header Positions         | Positions: 3, 3:6:3   |
| Default     | Showcase Positions       | Positions: 1, 12      |
| Default     | Feature Positions        | Positions: 2, 6:6     |
| Default     | Utility Positions        | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions        | Positions: 1, 12      |
| Default     | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainBody Positions       | Positions: 1, 12      |
| Default     | MainBottom Positions     | Positions: 1, 12      |
| Default     | ExpandedBottom Positions | Positions: 1, 12      |
| Default     | Extension Positions      | Positions: 2, 6:6     |
| Default     | Bottom Positions         | Positions: 3, 4:4:4   |
| Default     | Footer Positions         | Positions: 3, 4:4:4   |
| Default     | Copyright Positions      | Positions: 3, 4:4:4   |
| Home        | Header Positions         | Positions: 3, 3:6:3   |
| Home        | Feature Positions        | Positions: 2, 9:3     |
| Home        | Extension Positions      | Positions: 2, 3:9     |

### Advanced

![Advanced Settings][advanced]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Layout Mode       | Responsive                                              |
| Default     | Display Component | On                                                      |
| Default     | Mainbody Enabled  | On                                                      |
| Default     | RTL Support       | On                                                      |
| Default     | Page Suffix       | On                                                      |
| Default     | Selectivizr       | On                                                      |
| Default     | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default     | IE7 Redirect      | On                                                      |
| Default     | Demo Styling      | On                                                      |
| Default     | K2 Styling        | Off                                                     |
| Home        | Mainbody Enabled  | Off                                                     |

### Assignments

| Style       | Option      | Setting     |
| :---------- | :---------- | :---------- |
| Home        | Main Menu   | Home        |

[demo25]: assets/nuance.jpeg
[menu]: ../../start/menu.md
[Nuance2]: assets/nuance2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style]: assets/setstyle.jpeg
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[menu2]: assets/setmenu.jpeg
[features]: assets/setfeatures.jpeg
[setsocial]: assets/setsocial.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
