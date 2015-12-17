---
title: Vermilion: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Vermilion Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Vermilion2]

:   1. **Logo**  [6%, 18%, se]
    2. **Menu**  [6%, 80%, sw]
    3. **Copyright** [92%, 18%, se]
    4. **To-Top Scroller** [92%, 80%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style

![Style Settings][style2]

| Style       | Option              | Position    | Setting                                    |
| :---------- | :----------         | :---------- | :----------                                |
| Default     | Logo                | header-a    | Show: On, Type: Vermilion Template         |
| Default     | Main Menu Animation |             | Enable: On                                 |
| Default     | Font Settings       |             | Font Family: Vermilion, Font Size: Default |

### Features

![Features Settings][features]

| Style       | Option             | Position    | Setting                                                                                                                      |
| :---------- | :----------        | :---------- | :----------                                                                                                                  |
| Default     | Social Buttons     | copyright-a | Show: Off                                                                                                                    |
| Default     | Chart              |             | Show: On                                                                                                                     |
| Default     | Coming Soon Page   |             | Show: Off                                                                                                                    |
| Default     | Email Subscription |             | Show: On                                                                                                                     |
| Default     | Feedburner URI     |             | Blank                                                                                                                        |
| Default     | System Messages    | drawer      | On                                                                                                                           |
| Default     | Date               | utility-a   | Show: Off, Client-Side Date: Off                                                                                             |
| Default     | Font-Sizer         | utility-b   | Show: Off                                                                                                                    |
| Default     | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                                   |
| Default     | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                                                                 |
| Default     | Branding           | extension-b | Show: Off                                                                                                                    |
| Default     | Copyright          | copyright-a | Show: On, Text: `Copyright &copy; 2014 - Powered by <a href="http://www.rockettheme.com/"><strong>RocketTheme</strong></a>.` |
| Default     | To-Top Scroller    | copyright-b | Show: On                                                                                                                     |
| Default     | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                                                                            |
| Default     | Google Analytics   |             | Enable: Off                                                                                                                  |
| Home        | Social Buttons     | utility-b   | Show: On                                                                                                                     |

### Social Icons Used in Home Override

![][setsocial]

| Social Network / Link Type | Icon                | Text     |  
| :------------------------- | :------------------ | :------- |  
| Facebook                   | `fa fa-facebook`    | Facebook |  
| Google+                    | `fa fa-google-plus` | Google + |  
| Twitter                    | `fa fa-twitter`     | Twitter  |  
| RSS                        | `fa fa-rss`         | RSS      |  

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
| Default     | Header Positions         | Positions: 2, 2:10    |
| Default     | Top Positions            | Positions: 4, 3:3:3:3 |
| Default     | Utility Positions        | Positions: 1, 12      |
| Default     | Showcase Positions       | Positions: 1, 12      |
| Default     | Feature Positions        | Positions: 1, 12      |
| Default     | MainTop Positions        | Positions: 1, 12      |
| Default     | ExpandedTop Positions    | Positions: 1, 12      |
| Default     | MainBody Positions       | Positions: 1, 12      |
| Default     | MainBottom Positions     | Positions: 1, 12      |
| Default     | ExpandedBottom Positions | Positions: 1, 12      |
| Default     | Extension Positions      | Positions: 2, 6:6     |
| Default     | Bottom Positions         | Positions: 1, 12      |
| Default     | Footer Positions         | Positions: 2, 6:6     |
| Default     | Copyright Positions      | Positions: 2, 6:6     |
| Home        | Utility Positions        | Positions: 2, 7:5     |

### Advanced

![Advanced Settings][advanced]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Layout Mode       | Responsive                                              |
| Default     | Load Transition   | Off                                                     |
| Default     | Display Component | On                                                      |
| Default     | Mainbody Enabled  | On                                                      |
| Default     | RTL Support       | Off                                                     |
| Default     | Page Suffix       | On                                                      |
| Default     | Selectivizr       | On                                                      |
| Default     | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default     | IE7 Redirect      | On                                                      |
| Default     | Demo Styling      | On                                                      |
| Default     | K2 Styling        | On                                                      |
| Home        | Display Component | Off                                                     |


### Assignments

| Style       | Option      | Setting     |
| :---------- | :---------- | :---------- |
| Home        | Main Menu   | Home        |

[demo25]: assets/Vermilion.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Vermilion2]: assets/vermilion2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style2]: assets/style_settings.jpeg
[advanced]: assets/advanced_settings.jpeg
[layouts]: assets/layouts_settings.jpeg
[menu2]: assets/menu_settings.jpeg
[features]: assets/features_settings.jpeg
[setsocial]: assets/setsocial.jpg
