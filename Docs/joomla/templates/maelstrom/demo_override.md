---
title: Maelstrom: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Maelstrom Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/maelstrom:Maelstrom

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Maelstrom Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][maelstrom2]

:   1. **Logo** [6%, 18%, se]
    2. **Menu** [11%, 18%, se]
    3. **Branding** [92%, 46%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

| Style   | Option               | Position | Setting                                                            |  
| :------ | :------------------- | :------- | :----------------------------------------------------------------- |  
| Default | Background Level     |          | High                                                               |  
| Default | Body Level           |          | High                                                               |  
| Default | CSS Style            |          | Style 1                                                            |  
| Default | Header Animation     |          | Enable: On, Delay: 7000, Duration: 2000, Animation: Quad.easeInOut |  
| Default | Vertical Direction   |          | Top Down                                                           |  
| Default | Horizontal Direction |          | Right to Left                                                      |  
| Default | Read More Style      |          | Button                                                             |  
| Default | Fixed Header         |          | Off                                                                |  
| Default | Font Settings        |          | Font Family: Maelstrom, Font Size: Default                         |    
| Home    | Fixed Header         |          | On                                                                 |  

### Features

| Style   | Option            | Position  | Setting                                                                                 |  
| :------ | :---------------- | :-------- | :-------------------------------------------------------------------------------------- |  
| Default | Logo              | header-a  | Show: On, Auto Size: On, Centered: Off                                                  |  
| Default | Date              | top-a     | Show: Off                                                                               |  
| Default | Font-Sizer        | utility-a | Show: Off                                                                               |  
| Default | Login Panel       | utility-a | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |  
| Default | Popup Panel       | utility-a | Show: Off, Popup Button Text: `Popup Module`                                            |  
| Default | Branding          | copyright | Show: On                                                                                |  
| Default | Copyright         | footer-b  | Show: Off, Text: `Designed by RocketTheme`                                              |  
| Default | SmartLoad         |           | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles     |           | Enable: Off, Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller   | footer-b  | Show: Off, Text: `Top`                                                                  |  
| Default | System Messages   | drawer    | Show: On                                                                                |  
| Default | Reset Settings    | footer-b  | Show: Off, Text: `Reset Settings`                                                       |  
| Default | IE6 Warning       |           | Show: On, Delay: 2000                                                                   |  
| Default | Google Analytics  |           | Enable: Off                                                                             |  
| Default | Showcase Scroller |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  
| Default | Feature Scroller  |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  
| Default | Bottom Scroller   |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  

### Menu

| Style   | Option                | Setting                                          |
| :------ | :-------------------- | :----------------------------------------------- |
| Default | Menu Control          | Show: On, Centering: Off, Type: Fusion-Menu      |
| Default | Select a Menu         | Main Menu                                        |
| Default | Position              | navigation                                       |
| Default | Enable JavaScript     | On                                               |
| Default | Menu Opacity          | 1                                                |
| Default | Menu Effect           | Slide + Fade                                     |
| Default | Menu Delay            | 500                                              |
| Default | Menu Animation        | Circ.easeOut                                     |
| Default | Menu Duration         | 300                                              |
| Default | Enable ID             | Off                                              |
| Default | Module Cache          | On                                               |

### Layouts

| Style   | Option                     | Setting               |  
| :------ | :------------------------- | :-------------------- |  
| Default | Top Positions              | Positions: 2, 6:6     |  
| Default | Header Positions           | Positions: 1, 12      |  
| Default | Showcase Positions         | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions          | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions          | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions          | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions         | Positions: 2, 9:3     |  
| Default | MainBottom Positions       | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions           | Positions: 3, 4:4:4   |  
| Default | Footer Positions           | Positions: 3, 4:4:4   |  
| Home    | MainBody Positions         | Positions: 2, 8:4     |  

### Mobile

| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide       |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | top-a                                        |  
| Default | Positions Aliases    | mobile-header     | header-b                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-showcase   | header-a                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright                                    |  

### Advanced

| Style   | Option              | Setting                                                              |  
| :------ | :------------------ | :------------------------------------------------------------------- |  
| Default | Gantry Cache        | Enabled: On, Cache Timeout: 900                                      |  
| Default | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |  
| Default | Display Component   | On                                                                   |  
| Default | Display Mainbody    | On                                                                   |  
| Default | RT Typography       | Enabled: On                                                          |  
| Default | RT Extensions       | On                                                                   |  
| Default | Third Party Support | On                                                                   |  
| Default | RTL Support         | On                                                                   |  
| Default | Build Titles Spans  | Off                                                                  |  
| Default | Page Suffix         | On                                                                   |  
| Default | IE6 Redirect        | On                                                                   |  

[demo25]: assets/Maelstrom.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[maelstrom2]: assets/maelstrom2.jpeg