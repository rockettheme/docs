---
title: Audacity: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/audacity:Audacity

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Audacity Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation](http://docs.gantry.org/gantry4/configure).

### Style

![Style Settings](assets/setstyle.jpeg)

| Style   | Option               | Position | Setting                                                                        |
| :------ | :------------------- | :------- | :----------------------------------------------------------------              |
| Default | Logo                 | header-a | Show: On, Type: Audacity Template                                              |
| Default | Demo Body Class      |          | Preset 1                                                                       |
| Default | Accent Style         |          | Accent 1 Color: `#e10a30`, Accent 2 Color: `#f0600b`                           |
| Default | PageSurround Style   |          | Background Color: `#e8e8e8`                                                    |
| Default | Body Style           |          | Overlay: Light                                                                 |
| Default | Header Style         |          | Text Color: `#ffffff`, Background Color: `#000000`, Header Type: Normal Header |
| Default | Showcase Style       |          | Text Color: `#ffffff`, Background Color: `#3f3f3f`                             |
| Default | Utility Style        |          | Text Color: `#ffffff`, Background Color: `#e10a30`                             |
| Default | Feature Style        |          | Text Color: `#8f8f8f`, Background Color: `#ffffff`                             |
| Default | MainTop Style        |          | Text Color: `#8f8f8f`, Background Color: `#ffffff`                             |
| Default | MainBottom Style     |          | Text Color: `#8f8f8f`, Background Color: `#ffffff`                             |
| Default | Extension Style      |          | Text Color: `#ffffff`, Background Color: `#000000`                             |
| Default | Bottom Style         |          | Text Color: `#8f8f8f`, Background Color: `#ffffff`                             |
| Default | Footer Style         |          | Text Color: `#686868`, Background Color: `#f5f5f5`                             |
| Default | Copyright Style      |          | Text Color: `#828282`, Background Color: `#000000`                             |
| Default | Font Settings        |          | Font Family: Audacity, Font Size: Default                                      |

### Features

![Features Settings](assets/setfeatures.jpeg)

| Style   | Option             | Position    | Setting                                                                                                                                      |
| :------ | :----------------- | :---------- | :-------------------------------------------------------------------------                                                                   |
| Default | Social Buttons     | header-b    | Show: On                                                                                                                                     |
| Default | Chart              |             | Show: On                                                                                                                                     |
| Default | Coming Soon Page   |             | Show: Off                                                                                                                                    |
| Default | Email Subscription |             | Show: On                                                                                                                                     |
| Default | Feedburner URI     |             | Blank                                                                                                                                        |
| Default | System Messages    | drawer      | On                                                                                                                                           |
| Default | Date               | utility-a   | Show: Off, Client-Side Date: Off                                                                                                             |
| Default | Font-Sizer         | utility-b   | Show: Off                                                                                                                                    |
| Default | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                                                   |
| Default | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                                                                                 |
| Default | Branding           | copyright-a | Show: On                                                                                                                                     |
| Default | Copyright          | copyright-b | Show: On, Text: `Developed by <a href="http://www.rockettheme.com">RocketTheme</a>. Photos by <a href="https://tookapic.com/">tookapic</a>.` |
| Default | To-Top Scroller    | copyright-c | Show: On                                                                                                                                     |
| Default | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                                                                                            |
| Default | Google Analytics   |             | Enable: Off                                                                                                                                  |

#### Social Buttons

| Option | Setting                                          |
| :----- | :-----                                           |
| Icon 1 | `fa fa-twitter`                                  |
| Icon 2 | `fa fa-facebook`                                 |
| Text 1 |                                                  |
| Text 2 |                                                  |
| Link 1 | `https://twitter.com/rockettheme`                |
| Link 2 | `https://www.facebook.com/RocketTheme`           |
| Icon 3 | `fa fa-google-plus`                              |
| Icon 4 | `fa fa-rss`                                      |
| Text 3 |                                                  |
| Text 4 |                                                  |
| Link 3 | `https://plus.google.com/+rockettheme`           |
| Link 4 | `http://www.rockettheme.com/product-updates?rss` |

### Menu

![Menu Settings](assets/setmenu.jpeg)

| Style       | Option          | Setting                       |
| :---------- | :----------     | :----------                   |
| Default     | Menu Control    | Show: On, Type: Dropdown-Menu |
| Default     | Select a Menu   | Main Menu                     |
| Default     | Position        | header-c                      |
| Default     | Responsive Menu | Panel                         |
| Default     | Enable ID       | Off                           |
| Default     | Module Cache    | On                            |

### Layouts

![Layouts Settings](assets/setlayouts.jpeg)

| Style   | Option                   | Setting                   |
| :------ | :----------------------- | :--------------------     |
| Default | Top Positions            | Positions: 4, 3:3:3:3     |
| Default | Header Positions         | Positions: 4, 2:2:6:2     |
| Default | Showcase Positions       | Positions: 1, 12          |
| Default | Utility Positions        | Positions: 1, 12          |
| Default | Feature Positions        | Positions: 2, 6:6         |
| Default | MainTop Positions        | Positions: 2, 6:6         |
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3     |
| Default | MainBody Positions       | Positions: 1, 12          |
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3     |
| Default | MainBottom Positions     | Positions: 4, 3:3:3:3     |
| Default | Extension Positions      | Positions: 1, 12          |
| Default | Bottom Positions         | Positions: 3, 4:4:4       |
| Default | Footer Positions         | Positions: 6, 2:2:2:2:2:2 |
| Default | Copyright Positions      | Positions: 3, 3:6:3       |
| Home    | Feature Positions        | Positions: 2, 9:3         |
| Home    | MainTop Positions        | Positions: 2, 9:3         |

### Advanced

![Advanced Settings](assets/setadvanced.jpeg)

| Style   | Option            | Setting                                                 |
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
| Default | Animate           | Off                                                     |
| Home    | Mainbody Enabled  | Off                                                     |

### Assignments

![](assets/setassignments.jpeg)

| Style |   Option  | Setting |
| :---- | :-------- | :------ |
| Home  | Main Menu | Home    |
