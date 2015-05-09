---
title: Plethora: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Plethora Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Plethora2]

:   1. **Logo**  [7%, 11%, se]
    2. **Social Buttons** [5%, 88%, sw]
    3. **Menu**  [7%, 43%, se]
    4. **Branding** [91%, 11%, se]
    5. **Copyright** [91%, 25%, se]
    6. **To Top** [91%, 88%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][gantrydocs].

### Style

![Style Settings][style]

| Style       | Option             | Position    | Setting                                              |
| :---------- | :----------        | :---------- | :----------                                          |
| Default     | Logo               | header-a    | Show: On, Type: Plethora Template                    |
| Default     | Accent Style       |             | Accent 1 Color: `#e35614`, Accent 2 Color: `#338de0` |
| Default     | Demo Style         |             | Preset 1                                             |
| Default     | PageSurround Style |             | Background Color: `#f5f5f5`                          |
| Default     | Top Style          |             | Text Color: `#808080`, Background Color: `#1c1d1f`   |
| Default     | Header Style       |             | Text Color: `#1c1d1f`, Background Color: `#ffffff`   |
| Default     | Feature Style      |             | Text Color: `#ffffff`, Background Color: `#1c1d1f`   |
| Default     | MainTop Style      |             | Text Color: `#a8a8a8`, Background Color: `#ffffff`   |
| Default     | MainBody Style     |             | Light                                                |
| Default     | Bottom Style       |             | Text Color: `#ffffff`, Background Color: `#e35614`   |
| Default     | Bottom Style       |             | Text Color: `#ffffff`, Background Color: `#1c1d1f`   |
| Default     | Footer Style       |             | Text Color: `#808080`, Background Color: `#1c1d1f`   |
| Default     | Font Settings      |             | Font Family: Plethora, Font Size: Default            |

### Features

![Features Settings][features]

| Style       | Option             | Position    | Setting                                                                    |
| :---------- | :----------        | :---------- | :----------                                                                |
| Default     | Social Buttons     | top-c       | Show: On                                                                   |
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
| Default     | Copyright          | copyright-b | Show: On, Text: **See Below**                                              |
| Default     | To-Top Scroller    | copyright-c | Show: On, Text: `Top`                                                      |
| Default     | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                          |
| Default     | Google Analytics   |             | Enable: Off                                                                |

##### Copyright Text

~~~ .html
<div class="rt-text-small rt-center">All demo content is for sample purposes only, intended to show a live site. All images are licensed from ShutterStock &amp; PhotoDune for exclusive use on this demo site only. Use the Plethora RocketLauncher for demo replication.</div>
~~~

##### Social Buttons Settings

| Option      | Setting          |
| :---------- | :----------      |
| Target      | New Window       |
| Icon 1      | `fa fa-twitter`  |
| Text 1      |                  |
| Link 1      | #                |
| Icon 2      | `fa fa-facebook` |
| Text 2      |                  |
| Link 2      | #                |
| Icon 3      | `fa fa-rss`      |
| Text 3      |                  |
| Link 3      | #                |
| Icon 4      |                  |
| Text 4      |                  |

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
| Default     | Top Positions            | Positions: 3, 6:4:2   |
| Default     | Header Positions         | Positions: 3, 2:7:3   |
| Default     | Showcase Positions       | Positions: 2, 6:6     |
| Default     | Feature Positions        | Positions: 3, 4:4:4   |
| Default     | Utility Positions        | Positions: 4, 3:3:3:3 |
| Default     | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default     | MainTop Positions        | Positions: 3, 4:4:4   |
| Default     | MainBody Positions       | Positions: 1, 12      |
| Default     | MainBottom Positions     | Positions: 4, 3:3:3:3 |
| Default     | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default     | Extension Positions      | Positions: 4, 3:3:3:3 |
| Default     | Bottom Positions         | Positions: 1, 12      |
| Default     | Footer Positions         | Positions: 3, 4:4:4   |
| Default     | Copyright Positions      | Positions: 3, 2:8:2   |
| Home        | Showcase Positions       | Positions: 2, 8:4     |
| Home        | Feature Positions        | Positions: 3, 6:2:4   |
| Home        | MainTop Positions        | Positions: 3, 6:2:4   |

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
| Home        | Mainbody Enabled  | Off                                                     |

### Assignments

| Style       | Option      | Setting     |
| :---------- | :---------- | :---------- |
| Home        | Main Menu   | Home        |

[demo25]: assets/plethora.jpg
[menu]: ../../start/menu.md
[Plethora2]: assets/plethora2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style]: assets/setstyle.jpeg
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[menu2]: assets/setmenu.jpeg
[features]: assets/setfeatures.jpeg
[setsocial]: assets/setsocial.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
