---
title: Myriad: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Myriad Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][Myriad2]

:   1. **Menu** [6%, 25%, se]
    2. **Branding**  [92%, 17%, se]
    3. **Copyright**  [92%, 45%, se]
    4. **To-Top Scroller** [92%, 76%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][gantrydocs].

### Style

![Style Settings][style]

|  Style  |         Option        | Position |                                      Setting                                      |
| :------ | :-------------------- | :------- | :-------------------------------------------------------------------------------- |
| Default | Logo                  | header-a | Show: On, Type: Myriad Template                                                   |
| Default | Accent Style          |          | Accent 1 Color: `#0085f6`, Accent 2 Color: `#34a1fc`                              |
| Default | Demo Style            | Preset 1 |                                                                                   |
| Default | Body Style            |          | Light                                                                             |
| Default | Header Style          |          | Text Color: `#ffffff`, Background Color: `#090d0f`, Header Type: Normal Header    |
| Default | SlideShow Style       |          | Text Color: `#ffffff`, Background Color: `#090d0f`, Overlay Opacity: `0.5`        |
| Default | Showcase Style        |          | Text Color: `#bfc3c5`, Background Color: `#504b52`                                |
| Default | FullStrip Style       |          | Text Color: `#686868`, Background Color: `#ffffff`                                |
| Default | FirstFullWidth Style  |          | Text Color: `#686868`, Background Color: `#ffffff`                                |
| Default | Feature Style         |          | Text Color: `#9d9a9e`, Background Color: `#3a353c`                                |
| Default | Utility Style         |          | Text Color: `#9d9a9e`, Background Color: `#3a353c`                                |
| Default | SecondFullWidth Style |          | Text Color: `#ffffff`, Background Color: `#3a353c`, Background Image: Preset 1    |
| Default | MainTop Style         |          | Text Color: `#686868`, Background Color: `#ffffff`                                |
| Default | Extension Style       |          | Text Color: `#090d0f`, Background Color: `#ffffff`, Background Image: Preset 1    |
| Default | Bottom Style          |          | Text Color: `#686868`, Background Color: `#090d0f`                                |
| Default | Footer Style          |          | Text Color: `#686868`, Background Color: `#090d0f`                                |
| Default | Copyright Style       |          | Text Color: `#686868`, Background Color: `#090d0f`                                |
| Default | Font Settings         |          | Font Family: Myriad, Font Size: Default                                           |

Myriad's logo, as it appears in our RocketLauncher, is partially text based. You can find more information about changing this logo to meet your needs [here](faq.md#how-to-change-the-logo-as-it-appears-in-the-main-menu).

### Features

![Features Settings][features]

|  Style  |       Option       |   Position  |                                  Setting                                   |
| :------ | :----------------- | :---------- | :------------------------------------------------------------------------- |
| Default | Social Buttons     | copyright-c | Show: Off                                                                  |
| Default | Chart              |             | Show: On                                                                   |
| Default | Coming Soon Page   |             | Show: Off                                                                  |
| Default | Email Subscription |             | Show: On                                                                   |
| Default | Feedburner URI     |             | Blank                                                                      |
| Default | System Messages    | drawer      | On                                                                         |
| Default | Date               | utility-a   | Show: Off, Client-Side Date: Off                                           |
| Default | Font-Sizer         | utility-b   | Show: Off                                                                  |
| Default | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |
| Default | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |
| Default | Branding           | copyright-a | Show: On                                                                   |
| Default | Copyright          | copyright-b | Show: On, Text: `&copy; 2014 by RocketTheme`                               |
| Default | To-Top Scroller    | copyright-c | Show: On, Text: Blank                                                      |
| Default | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                          |
| Default | Google Analytics   |             | Enable: Off                                                                |

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

|  Style  |          Option          |        Setting        |
| :------ | :----------------------- | :-------------------- |
| Default | Header Positions         | Positions: 1, 12      |
| Default | Top Positions            | Positions: 4, 3:3:3:3 |
| Default | Showcase Positions       | Positions: 4, 3:3:3:3 |
| Default | Feature Positions        | Positions: 2, 6:6     |
| Default | Utility Positions        | Positions: 1, 12      |
| Default | MainTop Positions        | Positions: 1, 12      |
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |
| Default | MainBody Positions       | Positions: 2, 8:4     |
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |
| Default | MainBottom Positions     | Positions: 4, 3:3:3:3 |
| Default | Extension Positions      | Positions: 1, 12      |
| Default | Bottom Positions         | Positions: 3, 4:4:4   |
| Default | Footer Positions         | Positions: 1, 12      |
| Default | Copyright Positions      | Positions: 3, 4:4:4   |

### Advanced

![Advanced Settings][advanced]

|  Style  |       Option      |                         Setting                         |
| :------ | :---------------- | :------------------------------------------------------ |
| Default | Layout Mode       | Responsive                                              |
| Default | Display Component | On                                                      |
| Default | Mainbody Enabled  | On                                                      |
| Default | RTL Support       | Off                                                     |
| Default | Page Suffix       | On                                                      |
| Default | Selectivizr       | On                                                      |
| Default | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default | IE7 Redirect      | On                                                      |
| Default | Demo Styling      | On                                                      |
| Default | K2 Styling        | Off                                                     |
| Default | Animate           | On                                                      |

[demo25]: assets/myriad.jpeg
[menu]: ../../start/menu.md
[Myriad2]: assets/myriad2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style]: assets/setstyle.jpeg
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[menu2]: assets/setmenu.jpeg
[features]: assets/setfeatures.jpeg
[setsocial]: assets/setsocial.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
