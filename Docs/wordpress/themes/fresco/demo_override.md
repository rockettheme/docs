---
title: Fresco: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Fresco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/Fresco:Fresco

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Fresco Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you've selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style
| Override | Option | Setting |
|:--------|------:|-------:|
| Default | Logo | Fresco |
| Default | Main Style | Community A |
| Default | Background Level | High |
| Default | Pagination | Style: Full, Side Pages: 8 |
| Default | Thumbnail Size | Width: 142, Height: 88, Position: Left
| Default | Web Fonts | Show: Off, WebFonts Source: Google Font Directory |
| Default | Font Settings | Font Family: Fresco, Font Size: Default |
| Default | Use WordPress Comments | On |
| Default | Custom CSS | Blank |

### Gizmos
| Override | Option | Setting |
|:--------|------:|-------:|
| Default | Page Suffix | Enabled: Off, Class: Blank | 
| Default | Feed Links | On | 
| Default | Load Images | Show: On, Offset Y: 200, XPath Ignores: Blank |
| Default | Custom Title Tag | Blank | 
| Default | Typography Shortcodes | On |
| Default | Shortcodes in Widgets | On |
| Default | RokStyle | On |
| Default | Google Analytics | Enabled: Off, UA Code: Blank |
| Front Page | Page Suffix | Enabled: On, Class: `menu-home` | 

### Layouts
| Override | Option | Setting |
|:--------|------:|-------:|
| Default | Top Positions | Positions: 4, 3:3:3:3 |
| Default | Navigation Positions | Positions: 1, 12 |
| Default | Header Positions | Positions: 3, 4:5:3 |
| Default | Showcase Positions | Positions: 4, 3:3:3:3 |
| Default | Feature Positions | Positions: 4, 3:3:3:3 |
| Default | Utility Positions | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions | Positions: 4, 3:3:3:3 |
| Default | MainBody Positions | Positions: 2, 9:3 |
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default | Extension Positions | Positions: 4, 3:3:3:3 |
| Default | Bottom Positions | Positions: 4, 3:3:3:3 |
| Default | Footer Positions | Positions: 3, 4:4:4 |
| Default | Copyright Positions | Positions: 2, 6:6 |

### Advanced
| Override | Option | Setting |
|:--------|------:|-------:|
| Default | Layout Mode | Responsive |
| Default | Maintenance Mode | Off |
| Default | Gantry Cache | Enabled: On, Cache Time: 900 |
| Default | Gantry GZipper | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On |
| Default | Display Content | On |
| Default | Display Mainbody | On |
| Default | RTL Support | On |
| Default | RT Typography | Enabled: On, Typography Style: Light |
| Default | Disable Auto Paragraphs | Enabled: On, Content Type: Both |
| Default | Disable Texturize | Off |

### Assignments
| Override | Option | Setting |
|:--------|------:|-------:|
| Front Page | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/