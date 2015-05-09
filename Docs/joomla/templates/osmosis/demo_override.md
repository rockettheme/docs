---
title: Osmosis: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Osmosis Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Osmosis2]

:   1. **Logo**  [6%, 11%, se]
    2. **Menu**  [6%, 90%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][gantrydocs].

### Style

![Style Settings][style]

| Style       | Option              | Position    | Setting                                                |
| :---------- | :----------         | :---------- | :----------                                            |
| Default     | Logo                | header-a    | Show: On, Type: Osmosis Template                       |
| Default     | Main Menu Animation |             | Enable: On                                             |
| Default     | Font Settings       |             | Font Family: Osmosis, Font Size: Default               |
| Default     | SidePanel Style     |             | Off                                                    |
| Default     | SidePanel Logo      |             | Off                                                    |
| Default     | SidePanel Menu      |             | Off                                                    |
| Home        | SidePanel Style     |             | On, Text Color: `#807878`, Background Color: `#121212` |
| Home        | SidePanel Logo      |             | On                                                     |
| Home        | SidePanel Menu      |             | On                                                     |

### Features

![Features Settings][features]

|  Style  |       Option       |   Position  |                                  Setting                                   |
| :------ | :----------------- | :---------- | :------------------------------------------------------------------------- |
| Default | Social Buttons     | copyright-a | Show: Off                                                                  |
| Default | Chart              |             | Show: On                                                                   |
| Default | Coming Soon Page   |             | Show: Off                                                                  |
| Default | Email Subscription |             | Show: On                                                                   |
| Default | Feedburner URI     |             | Blank                                                                      |
| Default | System Messages    | drawer      | On                                                                         |
| Default | Date               | utility-a   | Show: Off, Client-Side Date: Off                                           |
| Default | Font-Sizer         | utility-b   | Show: Off                                                                  |
| Default | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |
| Default | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |
| Default | Branding           | extension-b | Show: Off                                                                  |
| Default | Copyright          | copyright-a | Show: On, Text: `Designed by RocketTheme`                                  |
| Default | To-Top Scroller    | copyright-c | Show: Off                                                                  |
| Default | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                          |
| Default | Google Analytics   |             | Enable: Off                                                                |

### Menu

![Menu Settings][menu2]

|  Style  |      Option     |            Setting            |
| :------ | :-------------- | :---------------------------- |
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |
| Default | Select a Menu   | Main Menu                     |
| Default | Position        | header-b                      |
| Default | Responsive Menu | Panel                         |
| Default | Enable ID       | Off                           |
| Default | Module Cache    | Off                           |

### Layouts

![Layouts Settings][layouts]

| Style       | Option                   | Setting               |
| :---------- | :----------              | :----------           |
| Default     | Header Positions         | Positions: 2, 3:9     |
| Default     | Top Positions            | Positions: 1, 12      |
| Default     | Utility Positions        | Positions: 4, 3:3:3:3 |
| Default     | Showcase Positions       | Positions: 1, 12      |
| Default     | Feature Positions        | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions        | Positions: 4, 3:3:3:3 |
| Default     | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainBody Positions       | Positions: 1, 12      |
| Default     | MainBottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Extension Positions      | Positions: 4, 3:3:3:3 |
| Default     | Bottom Positions         | Positions: 4, 3:3:3:3 |
| Default     | Footer Positions         | Positions: 3, 4:4:4   |
| Default     | Copyright Positions      | Positions: 4, 3:3:3:3 |

### Advanced

![Advanced Settings][advanced]

|  Style  |       Option      |                         Setting                         |
| :------ | :---------------- | :------------------------------------------------------ |
| Default | Layout Mode       | Fluid Responsive                                        |
| Default | Display Component | On                                                      |
| Default | Mainbody Enabled  | On                                                      |
| Default | RTL Support       | Off                                                     |
| Default | Page Suffix       | On                                                      |
| Default | Selectivizr       | On                                                      |
| Default | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default | IE7 Redirect      | On                                                      |
| Default | Demo Styling      | On                                                      |
| Default | K2 Styling        | Off                                                     |

### Assignments

| Style |   Option  | Setting |
| :---- | :-------- | :------ |
| Home  | Main Menu | Home    |

[demo25]: assets/osmosis.jpg
[menu]: ../../start/menu.md
[Osmosis2]: assets/osmosis2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style]: assets/style_settings.jpeg
[advanced]: assets/advanced_settings.jpeg
[layouts]: assets/setlayouts.jpg
[menu2]: assets/menu_settings.jpeg
[features]: assets/features_settings.jpeg
[setsocial]: assets/setsocial.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
