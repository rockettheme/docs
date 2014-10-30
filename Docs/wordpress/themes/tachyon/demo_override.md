---
title: Tachyon: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Tachyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tachyon:Tachyon

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Tachyon Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![Style][style]

| Override | Option                 | Setting                                           |  
| :------- | :--------------------- | :------------------------------------------------ |  
| Default  | Body Level             | Full                                              |  
| Default  | Header Style           | Dark                                              |  
| Default  | Headler Link Color     | `#63b8f9`                                         |  
| Default  | Body Text Color        | `#555555`                                         |  
| Defualt  | Body Link Color        | `#0B86E5`                                         |  
| Default  | Accent Style           | Orange                                            |  
| Default  | Footer Style           | Dark                                              |  
| Default  | Font Link Color        | `#63B8F9`                                         |  
| Default  | Widget Hovers          | On                                                |  
| Default  | Readon Style           | Button                                            |  
| Default  | Fixed Header           | Off                                               |  
| Default  | Thumbnail Size         | Width: `170`, Height: `138`, Position: Left       |  
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |  
| Default  | Font Settings          | Font Family: Helvetica, Font Size: Default        |  
| Default  | Use WordPress Comments | On                                                |  
| Default  | Comments Style         | Standard                                          |  
| Default  | Custom CSS             | Blank                                             |  

### Gizmos

![gizmos][gizmos]

| Override | Option                | Setting                                                                                                                                                                                                                                                     |  
| :------- | :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Default  | Showcase Scroller     | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut                                                                                                                                                                        |  
| Default  | Feature Scroller      | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut                                                                                                                                                                        |  
| Default  | Page Suffix           | Enable: Off                                                                                                                                                                                                                                                 |  
| Default  | Feed Links            | Show: On                                                                                                                                                                                                                                                    |  
| Default  | Smart-Load Images     | Show: On, Offset Y: 200, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper,.module-content ul.menu .image,.roknewspager-div a,#rokintroscroller,.feature-block .image-full, .controls .up, .controls .down, .rt-gallery` |  
| Default  | Custom Title Tag      | Blank                                                                                                                                                                                                                                                       |  
| Default  | Typography Shortcodes | On                                                                                                                                                                                                                                                          |  
| Default  | Shortcodes in Widgets | On                                                                                                                                                                                                                                                          |  
| Default  | RokStyle              | On                                                                                                                                                                                                                                                          |  
| Default  | Google Analytics      | Enabled: Off, UA Code: Blank                                                                                                                                                                                                                                |  

### Layouts

![layouts][layouts]

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 5:7     |
| Default    | Header Positions     | Positions: 1, 12      |
| Default    | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default    | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default    | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 9:3     |
| Default    | MainBottom Positions | Positions: 1, 12      |
| Default    | Bottom Positions     | Positions: 3, 4:4:4   |
| Default    | Footer Positions     | Positions: 4, 3:3:3:3 |
| Front Page | MainBody Positions   | Positions: 2, 8:4     |

### iPhone

![mobile][mobile]

| Override | Option                                     | Setting                                     |  
| :------- | :----------------------------------------- | :------------------------------------------ |  
| Default  | iPhone Custom Theme                        | On                                          |  
| Default  | Android Custom Theme                       | On                                          |  
| Default  | Scalable Content                           | Off                                         |  
| Default  | Images Resize                              | Enabled: On, Min-Width: 80, Percentage: 25% |  
| Default  | Positions Aliases - Mobile Drawer          | drawer                                      |  
| Default  | Positions Aliases - Mobile Top             | top-a                                       |  
| Default  | Positions Aliases - Mobile Header          | header-a                                    |  
| Default  | Positions Aliases - Mobile Navigation      | mobile-navigation                           |  
| Default  | Positions Aliases - Mobile Showcase        | mobile-showcase                             |  
| Default  | Positions Aliases - Mobile Footer Position | drawer                                      |  
| Default  | Positions Aliases - Mobile Copyright       | copyright                                   |  

### Advanced

![advanced][advanced]

| Override   | Option                  | Setting                                                                       |  
| :--------- | :---------------------- | :---------------------------------------------------------------------------- |  
| Default    | Gantry Cache            | Enabled: On, Cache Time: 900                                                  |  
| Default    | Gantry GZipper          | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On             |  
| Default    | Input Styiling          | Enabled: On, Exclusions: `'.content_vote','\#rt-popup','\#send_message_form'` |  
| Default    | Display Content         | On                                                                            |  
| Default    | Display Mainbody        | On                                                                            |  
| Default    | Typography Styling      | On                                                                            |  
| Default    | RT Plugins Styling      | On                                                                            |  
| Default    | RTL Support             | Enabled: On                                                                   |  
| Default    | Title Spans             | On                                                                            |  
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                               |  
| Default    | Disable Texturize       | Off                                                                           |  
| Default    | IE6 Redirect            | On                                                                            |  
| Front Page | Display Content         | Off                                                                           |  

### Assignments

![assignments][assignments]

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/
[style]: assets/setstyle.jpeg
[assignments]: assets/setassignments.jpg
[advanced]: assets/setadvanced.jpeg
[mobile]: assets/setiphone.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
