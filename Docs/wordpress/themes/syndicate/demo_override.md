---
title: Syndicate: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Syndicate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/syndicate:Syndicate

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Syndicate Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override | Option                 | Setting                                                                                          |  
| :------- | :--------------------- | :----------------------------------------------------------------------------------------------- |  
| Default  | Static CSS             | Use Static: Off, Check Changes: On                                                               |  
| Default  | Body Level             | Highest                                                                                          |  
| Default  | Main                   | Background: `#ffffff`                                                                            |  
| Default  | Logo Block             | Background: `#1e1e1e`, Overlay: Dark, Text: `#ffffff`, Link: `#cf3f1b`, Logo Style: Logo Style 3 |  
| Default  | Header                 | Background: `#b10d00`, Overlay: Light, Text: `#ffffff`, Link: `#ffffff`, Header Image: Header 5  |  
| Default  | Subnavigation          | Background: `#ebebeb`, Overlay: Light, Text: `#333333`, Link: `#333333`                          |  
| Default  | Body                   | Background: `#ffffff`, Overlay: Light, Text: `#444444`, Link: `#a50c0f`                          |  
| Default  | Footer                 | Background: `#f1f1f1`, Overlay: Light, Text: `#666666`, Link: `#a50c0f`                          |  
| Default  | Alert                  | Background: `#fef49c`, Text: `#000000`                                                           |  
| Default  | Read More Style        | Button                                                                                           |  
| Default  | Article Style          | `title7`                                                                                         |  
| Default  | Article Info Style     | Layout 2                                                                                         |  
| Default  | Header Width           | Full                                                                                             |  
| Default  | Footer Width           | Full                                                                                             |  
| Default  | Thumbnail Size         | Width: `150`, Height: `131`, Position: `Left`                                                    |  
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                                                |  
| Default  | Font Settings          | Font Family: Syndicate, Font Size: Default                                                       |  
| Default  | Use WordPress Comments | On                                                                                               |  
| Default  | Comments Style         | Standard                                                                                         |  
| Default  | Custom CSS             | Blank                                                                                            |  

### Gizmos

![gizmos][gizmos]

| Override | Option                | Setting                                                                                                                                                                                                         |  
| :------- | :-------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Default  | Page Suffix           | Enable: Off                                                                                                                                                                                                     |  
| Default  | Feed Links            | Show: On                                                                                                                                                                                                        |  
| Default  | IE6 Warning           | Show: On, Delay: `2000`                                                                                                                                                                                         |  
| Default  | Smart-Load Images     | Show: Off, Offset Y: 200, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper,.module-content ul.menu .image,.roknewspager-div a,#rokintroscroller,.feature-block .image-full` |  
| Default  | Custom Title Tag      | Blank                                                                                                                                                                                                           |  
| Default  | Typography Shortcodes | On                                                                                                                                                                                                              |  
| Default  | Shortcodes in Widgets | On                                                                                                                                                                                                              |  
| Default  | RokStyle              | On                                                                                                                                                                                                              |  
| Default  | Google Analytics      | Enabled: Off, UA Code: Blank                                                                                                                                                                                    |  

### Layouts

![layouts][layouts]

| Override   | Option               | Setting               |  
| :--------- | :------------------- | :-------------------- |  
| Default    | Top Positions        | Positions: 4, 4:4:4:4 |  
| Default    | Header Positions     | Positions: 4, 4:4:4:4 |  
| Default    | Showcase Positions   | Positions: 4, 4:4:4:4 |  
| Default    | Feature Positions    | Positions: 4, 4:4:4:4 |  
| Default    | Utility Positions    | Positions: 4, 4:4:4:4 |  
| Default    | MainTop Positions    | Positions: 4, 4:4:4:4 |  
| Default    | MainBody Positions   | Positions: 2, 12:4    |  
| Default    | MainBottom Positions | Positions: 4, 4:4:4:4 |  
| Default    | Bottom Positions     | Positions: 4, 4:4:4:4 |  
| Default    | Lower Ad Positions   | Positions: 4, 4:4:4:4 |  
| Default    | Footer Positions     | Positions: 3, 4:4:8   |  
| Front Page | Bottom Positions     | Positions: 3, 8:4:4   |  

### iPhone

![mobile][mobile]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | iPhone Scalable                            | Off                                         |
| Default     | iPhone Images                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default     | Positions Aliases - Mobile Top             | top-a                                       |
| Default     | Positions Aliases - Mobile Header          | header-a                                    |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Footer Position | drawer                                      |
| Default     | Positions Aliases - Mobile Copyright       | copyright                                   |

### Advanced

![advanced][advanced]

| Override   | Option                  | Setting                                                           |  
| :--------- | :---------------------- | :---------------------------------------------------------------- |  
| Default    | Gantry Cache            | Enabled: On, Cache Time: 900                                      |  
| Default    | Gantry GZipper          | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On |  
| Default    | Input Styiling          | Enabled: On, Exclusions: `'.content_vote','\#rt-popup'`           |  
| Default    | Display Content         | On                                                                |  
| Default    | Display Mainbody        | On                                                                |  
| Default    | RTL Support             | On                                                                |  
| Default    | Build Title Spans       | On                                                                |  
| Default    | RT Typography           | Enabled: On, Typography Style: Light                              |  
| Default    | RT Plugins Styling      | On                                                                |  
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                   |  
| Default    | Disable Texturize       | Off                                                               |  
| Front Page | Display Content         | Off                                                               |  

### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpeg
[mobile]: assets/setmobile.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
