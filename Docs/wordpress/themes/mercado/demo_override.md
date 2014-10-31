---
title: Mercado: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Mercado Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/mercado:Mercado

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Mercado Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override | Option                 | Setting                                           |  
| :------- | :--------------------- | :------------------------------------------------ |  
| Default  | Layout Mode            | Standard                                          |  
| Default  | Background Level       | High                                              |  
| Default  | Body Level             | High                                              |  
| Default  | CSS Style              | Style 1                                           |  
| Default  | Read More Style        | Button                                            |  
| Default  | Thumbnail Size         | Width: 170, Height: 138, Position: Left           |  
| Default  | WebFonts               | Show: Off, WebFonts Source: Google Font Directory |  
| Default  | Font Settings          | Font Family: Titillium, Font Size: Default        |  
| Default  | Use WordPress Comments | On                                                |  
| Default  | Comments Style         | Standard                                          |  
| Default  | Custom CSS             | Blank                                             |

### Gizmos

![][gizmos]

| Override | Option                | Setting                                                                                                                                                                                                                                                     |  
| :------- | :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Default  | Page Class Suffix     | Enable: Off                                                                                                                                                                                                                                                 |  
| Default  | Feed Links            | On                                                                                                                                                                                                                                                          |  
| Default  | Load Images           | Show: On, Offset Y: 200, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper,.module-content ul.menu .image,.roknewspager-div a,#rokintroscroller,.feature-block .image-full, .controls .up, .controls .down, .rt-gallery` |  
| Default  | Custom Title Tag      | Blank                                                                                                                                                                                                                                                       |  
| Default  | Typography Shortcodes | On                                                                                                                                                                                                                                                          |  
| Default  | Shortcodes in Widgets | On                                                                                                                                                                                                                                                          |  
| Default  | RokStyle              | On                                                                                                                                                                                                                                                          |  
| Default  | Google Analytics      | Enabled: Off, UA Code: Blank                                                                                                                                                                                                                                |  

### Scrolling Widgets

![][setscrolling]

| Override | Option               | Setting                                                                              |  
| :------- | :------------------- | :----------------------------------------------------------------------------------- |  
| Default  | Main Top Position    | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  
| Default  | Main Bottom Position | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  
| Default  | Bottom Position      | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  

### Layouts

![][layouts]

|   Style    |           Option           |        Setting        |
| :--------- | :------------------------- | :-------------------- |
| Default    | Top Positions              | Positions: 3, 4:4:4   |
| Default    | Header Positions           | Positions: 4, 3:3:3:3 |
| Default    | Showcase Positions         | Positions: 1, 12      |
| Default    | Feature Positions          | Positions: 4, 3:3:3:3 |
| Default    | Utility Positions          | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions          | Positions: 3, 3:3:3   |
| Default    | MainBody Positions         | Positions: 2, 6:3     |
| Default    | MainBottom Positions       | Positions: 2, 5:4     |
| Default    | Bottom Positions           | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions           | Positions: 3, 4:4:4   |
| Default    | Component Top Positions    | Positions: 4, 3:3:3:3 |
| Default    | Component Bottom Positions | Positions: 4, 3:3:3:3 |
| Front Page | MainBottom Positions       | Positions: 2, 6:3     |
| Front Page | Footer Positions           | Positions: 3, 2:4:6   |


### iPhone

![][mobile]

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

![][advanced]

| Override   | Option                  | Setting                                                                   |  
| :--------- | :---------------------- | :------------------------------------------------------------------------ |  
| Default    | Gantry Cache            | Enabled: On, Cache Time `900`                                             |  
| Default    | Gantry GZipper          | Enabled: On, Cache Time `600`, Expires Time: `1440`, Strip Whitespace: On |  
| Default    | Layout Mode             | Responsive                                                                |  
| Default    | Input Styling           | Enabled: On, Exclusions: `'.content_vote','\#rt-popup'`                   |  
| Default    | Display Content         | On                                                                        |  
| Default    | Display Mainbody        | On                                                                        |  
| Default    | RTL Support             | On                                                                        |  
| Default    | Title Spans             | On                                                                        |  
| Default    | Typography Styling      | Enabled: On                                                               |  
| Default    | RT Plugins Styling      | On                                                                        |  
| Default    | Ecwid Styling           | On                                                                        |  
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                           |  
| Default    | Disable Texturize       | Off                                                                       |  
| Default    | IE6 Redirect            | On                                                                        |  
| Front Page | Display Content         | Off                                                                       |  


### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/
[advanced]: assets/setadvanced.jpeg
[setscrolling]: assets/setscrolling.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
