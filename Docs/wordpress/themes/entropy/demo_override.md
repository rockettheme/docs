---
title: Entropy: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Entropy Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/entropy:Entropy

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Entropy Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

![][style]

| Override   | Option                 | Setting                                                                                                                                     |  
| :--------- | :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------ |  
| Default    | CSS Style              | Style 1                                                                                                                                     |  
| Default    | Header Panel           | Headline: Blank, Pattern: Pattern 2, Divider: Divider 2, Subline: Blank, Typography: Retro, Title Alignment: Center                         |  
| Default    | Showcase Panel         | Headline: Blank, Title Alignment: Center, Typography: Retro, Subline: Blank                                                                 |  
| Default    | Feature Panel          | Headline: Blank, Divider: Divider 1, Title Alignment: Center, Subline: Blank, Typography: Retro                                             |  
| Default    | MainBody Panel         | Headline: Blank, Divider: Divider 1, Title Alignment: Left, Subline: Blank, Typography: Retro                                               |  
| Default    | Bottom Panel           | Headline: Blank, Pattern: Pattern 1, Divider: Divider 5, Subline: Blank, Typography: Retro, Title: Center                                   |  
| Default    | Footer Panel           | Headline: Blank, Divider: Divider 1, Title Alignment: Center, Subline: Blank, Typography: Retro                                             |  
| Default    | Read More Style        | Button                                                                                                                                      |  
| Default    | Panel Back To Top      | On                                                                                                                                          |  
| Default    | Fixed Header           | On                                                                                                                                          |  
| Default    | Thumbnail Size         | Width: 150, Height: 150, Position: Left                                                                                                     |  
| Default    | WebFonts               | Show: Off, WebFonts Source: Google Font Directory                                                                                           |  
| Default    | Font Settings          | Font Family: Helvetica, Font Size: Default                                                                                                  |  
| Default    | Use WordPress Comments | On                                                                                                                                          |  
| Default    | Comments Style         | Standard                                                                                                                                    |  
| Default    | Custom CSS             | Blank                                                                                                                                       |  
| Front Page | Showcase Panel         | Headline: `Conference Schedule`, Title Alignment: Center, Typography: Retro, Subline: `Find the sessions that interest you`                 |  
| Front Page | Feature Panel          | Headline: `Guest Speakers`, Divider: Divider 1, Title Alignment: Center, Subline: `Experts in their Field`, Typography: Retro               |  
| Front Page | Bottom Panel           | Headline: `How to Attend`, Pattern: Pattern 1, Divider: Divider 5, Subline: `Location, Prices, etc...`, Typography: Retro, Title: Center    |  
| Front Page | Footer Panel           | Headline: `Theme Features`, Divider: Divider 1, Title Alignment: Center, Subline: `Packed full of goodies and fun stuff`, Typography: Retro |  

### Gizmos

![][gizmos]

| Override | Option                  | Setting                                                                              |  
| :------- | :---------------------- | :----------------------------------------------------------------------------------- |
| Default  | Page Class Suffix       | Enable: Off                                                                          |  
| Default  | Feed Links              | On                                                                                   |  
| Default  | Load Images             | Show: On, Offset Y: 200, XPath Ignores: Blank                                        |  
| Default  | Custom Title Tag        | Blank                                                                                |  
| Default  | Typography Shortcodes   | On                                                                                   |  
| Default  | Shortcodes in Widgets   | On                                                                                   |  
| Default  | RokStyle                | On                                                                                   |  
| Default  | Google Analytics        | Enabled: Off, UA Code: Blank                                                         |  

### Layouts

![][layouts]

|   Style    |        Option        |        Setting        |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 3:9     |
| Default    | Header Positions     | Positions: 2, 6:6     |
| Default    | Showcase Positions   | Positions: 1, 12      |
| Default    | Feature Positions    | Positions: 1, 12      |
| Default    | Utility Positions    | Positions: 1, 12      |
| Default    | MainTop Positions    | Positions: 2, 6:6     |
| Default    | MainBody Positions   | Positions: 2, 7:5     |
| Default    | MainBottom Positions | Positions: 1, 12      |
| Default    | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions     | Positions: 4, 3:3:3:3 |
| Front Page | MainBody Positions   | Positions: 2, 7:5     |

### Mobile

![][layouts]

| Override | Option                                     | Setting                                     |  
| :------- | :----------------------------------------- | :------------------------------------------ |  
| Default  | iPhone Custom Theme                        | On                                          |  
| Default  | Android Custom Theme                       | On                                          |  
| Default  | iPhone Scalable                            | Off                                         |  
| Default  | Images Resize                              | Enabled: On, Min-Width: 80, Percentage: 25% |  
| Default  | Positions Aliases - Mobile Drawer          | drawer                                      |  
| Default  | Positions Aliases - Mobile Top             | top-a                                       |  
| Default  | Positions Aliases - Mobile Header          | header-b                                    |  
| Default  | Positions Aliases - Mobile Navigation      | mobile-navigation                           |  
| Default  | Positions Aliases - Mobile Showcase        | mobile-showcase                             |  
| Default  | Positions Aliases - Mobile Feature         | feature-a                                   |  
| Default  | Positions Aliases - Mobile Bottom          | mainbottom-a                                |  
| Default  | Positions Aliases - Mobile Footer Position | footer-position-c                           |  
| Default  | Positions Aliases - Mobile Copyright       | copyright                                   |  

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
| Default  | Typography Styling      | Enabled: On                                                                   |  
| Default  | Disable Auto Paragraphs | Enabled: On, Content Type: Both                                               |  
| Default  | Disable Texturize       | Off                                                                           |  
| Default  | IE6 Redirect            | On                                                                            |  


### Assignments

| Override    | Option              | Setting               |
| :---------- | :----------         | :----------           |
| Front Page  | Template Page Types | Home Page, Front Page |

[override]: http://gantry-framework.org/documentation/wordpress/configure/
[advanced]: assets/setadvanced.jpeg
[layouts]: assets/setlayouts.jpeg
[gizmos]: assets/setgizmos.jpeg
[style]: assets/setstyle.jpeg
[mobile]: assets/setmobile.jpeg
