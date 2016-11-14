---
title: Somaxiom: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

Template Settings
-----

One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Somaxiom Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style

![Style](setstyle.jpeg)

|  Style  |     Option    | Position |                  Setting                   |
| :------ | :------------ | :------- | :----------------------------------------- |
| Defualt | Body Level    |          | High                                       |
| Default | Body Style    |          | Circles                                    |
| Default | CSS Style     |          | Style 1                                    |
| Default | Link Color    |          | #cd5a1c                                    |
| Default | Article Style |          | Default                                    |
| Default | Font Settings |          | Font Family: Helvetica, Font Size: Default |

### Features

![Features](setfeatures.jpeg)

|  Style  |      Option      |  Position |                                                     Setting                                                      |
| :------ | :--------------- | :-------- | :--------------------------------------------------------------------------------------------------------------- |
| Default | Logo             | header-b  | Show: On, Auto Size: On                                                                                          |
| Default | Date             | top-d     | Client-side Date: Off                                                                                            |
| Default | Font-Sizer       | feature-b | Show: Off                                                                                                        |
| Default | Login Panel      | top-c     | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                       |
| Default | Branding         | copyright | Show: On                                                                                                         |
| Default | Copyright        | copyright | Show: Off                                                                                                        |
| Default | Smartload        |           | Show: On, Offset Y: `10`, Component Ignores: `com_community,com_contact`, XPath Ignores: `ul.menutop span.image` |
| Default | To-Top Scroller  | Copyright | Show: Off, Scroll To Top                                                                                         |
| Default | System Messages  | feature-a | Show: On                                                                                                         |
| Default | Reset Settings   | Copyright | Show: Off, Text: `Reset Settings`                                                                                |
| Default | Google Analytics |           | Enable: Off                                                                                                      |

### Menu

![Menu](setmenu.jpeg)

|  Style  |       Option      |                        Setting                        |
| :------ | :---------------- | :---------------------------------------------------- |
| Default | Menu Control      | Show: On, Type: Fusion-Menu                           |
| Default | Select a Menu     | Main Menu                                             |
| Default | Position          | Navigation                                            |
| Default | Enable JavaScript | On                                                    |
| Default | Menu Opacity      | `1`                                                   |
| Default | Menu Effect       | Slide + Fade                                          |
| Default | Menu Delay        | `500`                                                 |
| Default | Menu Animation    | Circ.easeOut                                          |
| Default | Menu Duration     | `300`                                                 |
| Default | Pill              | Enable: Off, Duration: `200`, Animation: Quad.easeOut |
| Default | Enable ID         | Off                                                   |
| Default | Module Cache      | On                                                    |

### Layouts

![Layouts](setlayouts.jpeg)

|  Style  |        Option        |        Setting        |
| :------ | :------------------- | :-------------------- |
| Default | Top Positions        | Positions: 2, 5:7     |
| Default | Header Positions     | Positions: 3, 3:6:3   |
| Default | Showcase Positions   | Positions: 1, 12      |
| Default | Feature Positions    | Positions: 3, 4:4:4   |
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions    | Positions: 3, 4:4:4   |
| Default | MainBody Positions   | Positions: 2, 4:8     |
| Default | MainBottom Positions | Positions: 2, 4:8     |
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default | Footer Positions     | Positions: 3, 4:4:4   |

### Mobile

![Mobile](setmobile.jpeg)

|  Style  |        Option        |      Position     |                              Setting                              |
| :------ | :------------------- | :---------------- | :---------------------------------------------------------------- |
| Default | iPhone Custom Theme  |                   | On                                                                |
| Default | Scalable Content     |                   | Off                                                               |
| Default | Standard View Switch | mobile-copyright  | Enable: On                                                        |
| Default | iPhone Menu          |                   | Menu: Main Menu, Menu Animation: Slide                            |
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25%                      |
| Default | Header Background    |                   | From: `#89B6B6`, To: `#89B6B6`, Start: Left Top, End: Left Bottom |
| Default | Positions Aliases    | mobile-drawer     | drawer                                                            |
| Default | Positions Aliases    | mobile-top        | top-a                                                             |
| Default | Positions Aliases    | mobile-header     | header-b                                                          |
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                                                 |
| Default | Positions Aliases    | mobile-showcase   | header-a                                                          |
| Default | Positions Aliases    | mobile-footer     | footer-a                                                          |
| Default | Positions Aliases    | mobile-copyright  | copyright                                                         |

### Advanced

![Advanced](setadvanced.jpeg)

|  Style  |        Option       |                               Setting                                |
| :------ | :------------------ | :------------------------------------------------------------------- |
| Default | Gantry Cache        | Enabled: On, Cache Timeout: `900`                                    |
| Default | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |
| Default | Display Component   | On                                                                   |
| Default | Display MainBody    | On                                                                   |
| Default | RTL Support         | On                                                                   |
| Default | Page Suffix         | On                                                                   |
| Default | Third Party Styling | Off                                                                  |
| Default | IE7 Redirect        | On                                                                   |

[demo25]: assets/Somaxiom.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Somaxiom2]: assets/Somaxiom.jpeg