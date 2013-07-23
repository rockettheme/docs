---
title: Stratos: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Stratos Template for WordPress
breadcrumb: /joomla:Joomla/templates:Templated/stratos:Stratos

---

Template Settings
-----
One of the most important central features of any Gantry Template is the ability to be set up within the Template Settings menu. These settings can be adjusted by navigating to **Administration -> Stratos Template**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

![][stratos2]

:   1. **Logo**  [9%, 20%, se]
    2. **Menu**  [9%, 60%, sw]
    3. **Login Panel**  [9%, 81%, sw]
    4. **Copyright**  [88%, 20%, se]
    5. **To-Top Scroller**  [88%, 82%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you've selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style | Option | Setting |
|:-----|:------|:-------|
| Default | Font Settings | Font Family: Stratos, Font Size: Default |

### Features
| Style | Option | Position |  Setting |
|:-----|:------|:-------|:-------|
| Default | Social Buttons |  | Show: Off |
| Default | Date | top-d | Show: Off |
| Default | Font-Sizer | feature-b | Show: Off |
| Default | Login Panel | header-c | Show: On, Login Button Text: `<span class="hidden-tablet">Member </span>Login <span class="icon-angle-right medmarginleft"></span>`, Logout Button Text: `<span class="hidden-tablet">Member </span>Logout <span class="icon-angle-right medmarginleft"></span>` |
| Default | Popup Panel | utility-d | Show: Off, Popup Button Text: `Popup Module` |
| Default | Branding | copyright-a | Show: Off |
| Default | Copyright | copyright-a | Show: On, Text: `Designed by <a href="http://www.rockettheme.com">RocketTheme</a>.` |
| Default | To-Top Scroller | copyright-c | Show: On, Text: `<span class="icon-angle-up"></span>` |
| Default | System Messages | drawer | Show: On |
| Default | Reset Settings | copyright-d | Show: Off, Text: `Reset Settings` |
| Default | Google Analytics |  | Enable: Off |

### Menu
| Style | Option | Setting |
|:-----|:------|:-------|
| Default | Menu Control | Show: On, Type: Dropdown-Menu |
| Default | Select a Menu | Main Menu |
| Default | Position | header-b |
| Default | Responsive Menu | Panel |
| Default | Enable ID | Off |
| Default | Module Cache | On |

### Layouts
| Style | Option | Setting |
|:-----|:------|:-------|
| Default | Top Positions | Positions: 4, 3:3:3:3 |
| Default | Header Positions | Positions: 3, 3:7:2 |
| Default | Showcase Positions | Positions: 1, 12 |
| Default | Feature Positions | Positions: 4, 3:3:3:3 |
| Default | Utility Positions | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions | Positions: 4, 3:3:3:3 |
| Default | MainBody Positions | Positions: 2, 8:4 |
| Default | MainBottom Positions | Positions: 1, 12 |
| Default | Extension Positions | Positions: 2, 6:6 |
| Default | Bottom Positions | Positions: 4, 3:3:3:3 |
| Default | Footer Positions | Positions: 2, 6:6 |
| Default | Copyright Positions | Positions: 3, 3:7:2 |
| Home | Mainbody Positions | Positions 2, 9:3 |
| Home | Extension Positions | Positions 2, 8:4 |
| Home | Footer Positions | Positions 2, 8:4 |

### Advanced
| Style | Option | Setting |
|:-----|:------|:-------|
| Default | Layout Mode | Responsive |
| Default | Load Transition | Off |
| Default | Display Content | On |
| Default | Mainbody Enabled | On |
| Default | RTL Support | On |
| Default | Page Suffix | On |
| Default | Selectivizr | On |
| Default | Less Compiler | CSS Compression: On, Compile Wait: 2, Debug Header: Off |
| Default | IE7 Redirect | On |
| Default | K2 Styling | On |

### Assignments
| Style | Option | Setting |
|:-----|:------|:-------|
| Home | Main Menu | Home |

[demo25]: assets/stratos.jpg
[menu]: ../../start/menu.md
[Style]: http://gantry-framework.org/documentation/wordpress/configure/
[stratos2]: assets/stratos2.jpg