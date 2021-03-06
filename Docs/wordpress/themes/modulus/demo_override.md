---
title: Modulus: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Modulus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/modulus:Modulus

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Modulus Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override | Option                 | Setting                                                |  
| :------- | :--------------------- | :----------------------------------------------------- |  
| Default  | Top Section            | Background: `#7c1e21`, Link: `#ffffff`, Overlay: Dark  |  
| Default  | Showcase Section       | Background: `#3b5472`, Link: `#f8bc46`, Overlay: Dark  |  
| Default  | Body Section           | Overlay: Light, Link: `#7c1e21`                        |  
| Default  | Footer Section         | Background: `#ffffff`, Link: `#7c1e21`, Overlay: Light |  
| Default  | Load Transition        | On                                                     |  
| Default  | Fixed Header           | On                                                     |  
| Default  | Read More Style        | Button                                                 |  
| Default  | Thumbnail Size         | Width: 120, Height: 120, Position: Left                |  
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory      |  
| Default  | Font Settings          | Font Family: Modulus, Font Size: Default               |  
| Default  | Use WordPress Comments | On                                                     |  
| Default  | Comments Style         | Standard                                               |  
| Default  | Custom CSS             | Blank                                                  |  

### Gizmos

![][gizmos]

| Override | Option                | Setting                                       |  
| :------- | :-------------------- | :-------------------------------------------- |  
| Default  | Page Class Suffix     | Enable: Off                                   |  
| Default  | Feed Links            | On                                            |  
| Default  | Load Images           | Show: On, Offset Y: 200, XPath Ignores: Blank |  
| Default  | Custom Title Tag      | Blank                                         |  
| Default  | Typography Shortcodes | On                                            |  
| Default  | Shortcodes in Widgets | On                                            |  
| Default  | RokStyle              | On                                            |  
| Default  | Google Analytics      | Enabled: Off, UA Code: Blank                  |  
| Default  | Page Class Suffix     | Enable: On, Class: `jan12-home`               |

### Layouts

![][layouts]

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 5:7     |  
| Default | Header Positions     | Positions: 3, 2:8:2   |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 3, 4:4:4   |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 2, 8:4     |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 4, 4:4:4   |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 2, 8:4     |  

### Mobile

![][layouts]

| Override    | Option                                     | Setting                                     |
| :---------- | :----------                                | :----------                                 |
| Default     | iPhone Custom Theme                        | On                                          |
| Default     | Android Custom Theme                       | On                                          |
| Default     | Scalable Content                           | Off                                         |
| Default     | Images Resize                              | Enabled: On, Min-Width: 80, Percentage: 25% |
| Default     | Positions Aliases - Mobile Drawer          | drawer                                      |
| Default     | Positions Aliases - Mobile Top             | top-a                                       |
| Default     | Positions Aliases - Mobile Header          | header-b                                    |
| Default     | Positions Aliases - Mobile Navigation      | mobile-navigation                           |
| Default     | Positions Aliases - Mobile Showcase        | mobile-showcase                             |
| Default     | Positions Aliases - Mobile Feature         | feature-a                                   |
| Default     | Positions Aliases - Mobile Bottom          | mainbottom-b                                |
| Default     | Positions Aliases - Mobile Footer Position | footer-position-c                           |
| Default     | Positions Aliases - Mobile Copyright       | copyright                                   |

### Advanced

![][advanced]

| Override | Option                  | Setting                                                                       |  
| :------- | :---------------------- | :---------------------------------------------------------------------------- |  
| Default  | Gantry Cache            | Enabled: On, Cache Time `900`                                                 |  
| Default  | Gantry GZipper          | Enabled: On, Cache Time `600`, Expires Time: `1440`, Strip Whitespace: On     |  
| Default  | Layout Mode             | Responsive                                                                    |  
| Default  | Input Styling           | Enabled: On, Exclusions: `'.content_vote','\#rt-popup','\#send_message_form'` |  
| Default  | Display Content         | On                                                                            |  
| Default  | Display Mainbody        | On                                                                            |  
| Default  | RTL Support             | On                                                                            |  
| Default  | Title Spans             | On                                                                            |  
| Default  | Additional Typography   | Enabled: On, Typography Style: Light                                          |  
| Default  | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                               |  
| Default  | Disable Texturize       | Off                                                                           |  
| Default  | IE6 Redirect            | On                                                                            |  

### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Theme Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
