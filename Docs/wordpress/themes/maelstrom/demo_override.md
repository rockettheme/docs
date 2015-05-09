---
title: Maelstrom: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Maelstrom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/maelstrom:Maelstrom

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Maelstrom Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override   | Option                 | Setting                                                                |  
| :--------- | :--------------------- | :--------------------------------------------------------------------- |  
| Default    | Background Level       | High                                                                   |  
| Default    | Body Level             | High                                                                   |  
| Default    | CSS Style              | Style 1                                                                |  
| Default    | Header Animation       | Enable: On, Delay: `7000`, Duration: `2000`, Animation: Quad.easeInOut |  
| Default    | Vertical Direction     | Top Down                                                               |  
| Default    | Horizontal Direction   | Right to Left                                                          |  
| Default    | Header Text Color      | `#2d3235`                                                              |  
| Default    | Header Link Color      | `#5acbff`                                                              |  
| Default    | Body Text Color        | `#cacbcb`                                                              |  
| Default    | Body Link Color        | `#66aa08`                                                              |  
| Default    | Read More Style        | Button                                                                 |  
| Default    | Article Style          | Surround Style 1                                                       |  
| Default    | Article Date Badge     | On                                                                     |  
| Default    | Fixed Header           | Off                                                                    |  
| Default    | Thumbnail Size         | Width: 140, Height: 98, Position: Left                                 |  
| Default    | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                      |  
| Default    | Font Settings          | Font Family: Maelstrom, Font Size: Default                             |  
| Default    | Use WordPress Comments | On                                                                     |  
| Default    | Comments Style         | Standard                                                               |  
| Default    | Custom CSS             | Blank                                                                  |  
| Front Page | Fixed Header           | On                                                                     |  

### Gizmos

![][gizmos]

| Override | Option                | Setting                                                                                                                                                                                                        |  
| :------- | :-------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Default  | Page Class Suffix     | Enable: Off                                                                                                                                                                                                    |  
| Default  | Feed Links            | On                                                                                                                                                                                                             |  
| Default  | IE6 Warning           | Show: On, Delay: 2000                                                                                                                                                                                          |  
| Default  | Smart-Load Images     | Show: Off, Offset Y: 200, XPath Ignores: `ul.menutop,div.roktabs-wrapper,span.image,div.fusion-submenu-wrapper,.module-content ul.menu .image,.roknewspager-div a,#rokintroscroller,.feature-block .image-full` |  
| Default  | Custom Title Tag      | Blank                                                                                                                                                                                                          |  
| Default  | Typography Shortcodes | On                                                                                                                                                                                                             |  
| Default  | Shortcodes in Widgets | On                                                                                                                                                                                                             |  
| Default  | RokStyle              | On                                                                                                                                                                                                             |  
| Default  | Analytics             | Enabled: Off, UA Code: Blank                                                                                                                                                                                   |  

### Scrolling Widgets

![][scrolling]

| Override | Option            | Setting                                                                              |  
| :------- | :---------------- | :----------------------------------------------------------------------------------- |  
| Default  | Showcase Position | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  
| Default  | Feature Position  | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  
| Default  | Bottom Position   | Enable: On, Duration: `600`, Autoplay: Off, Delay: `5000`, Animation: Expo.easeInOut |  

### Layouts

![][layouts]

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 6:6     |
| Default    | Header Positions     | Positions: 1, 12      |
| Default    | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default    | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default    | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 9:3     |
| Default    | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default    | Bottom Positions     | Positions: 3, 4:4:4   |
| Default    | Footer Positions     | Positions: 3, 4:4:4   |
| Front Page | MainBody Positions   | Positions: 2, 8:4     |


### iPhone

![][mobile]

| Override | Option                                     | Setting                                     |  
| :------- | :----------------------------------------- | :------------------------------------------ |  
| Default  | iPhone Enabled                             | On                                          |  
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

| Override | Option                  | Setting                                                                   |  
| :------- | :---------------------- | :------------------------------------------------------------------------ |  
| Default  | Gantry Cache            | Enabled: On, Cache Time `900`                                             |  
| Default  | Gantry GZipper          | Enabled: On, Cache Time `600`, Expires Time: `1440`, Strip Whitespace: On |  
| Default  | Layout Mode             | Responsive                                                                |  
| Default  | Input Styling           | Enabled: On, Exclusions: `'.content_vote','\#rt-popup'`                   |  
| Default  | Display Content         | On                                                                        |  
| Default  | Display Mainbody        | On                                                                        |  
| Default  | RTL Support             | On                                                                        |  
| Default  | Title Spans             | On                                                                        |  
| Default  | RT Plugins Styling      | Enabled: On                                                               |  
| Default  | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                           |  
| Default  | Disable Texturize       | Off                                                                       |  

### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://docs.gantry.org/gantry4/configure
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
[scrolling]: assets/setscrolling.jpeg
