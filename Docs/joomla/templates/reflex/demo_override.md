---
title: Reflex: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Reflex Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reflex:Reflex

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Reflex Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][reflex2]

:   1. **Logo** [7%, 47%, se]
    2. **Menu** [10%, 20%, se]
    3. **Copyright** [92%, 19%, se]
    4. **To-Top** [92%, 48%, se]
    3. **Branding** [92%, 73%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

| Style   | Option          | Position | Setting                                 |  
| :------ | :-------------- | :------- | :-------------------------------------- |  
| Default | Load Transition |          | On                                      |  
| Default | Read More Style |          | Button                                  |  
| Default | Font Settings   |          | Font Family: Reflex, Font Size: Default |   

### Features

| Style   | Option           | Position    | Setting                                                                                 |  
| :------ | :--------------- | :---------- | :-------------------------------------------------------------------------------------- |  
| Default | Logo             | header-c    | Show: On, Auto Size: On, Centered: On                                                   |  
| Default | Date             | utility-a   | Show: Off                                                                               |  
| Default | Font-Sizer       | utility-b   | Show: Off                                                                               |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                            |  
| Default | Branding         | copyright-c | Show: On                                                                                |  
| Default | Copyright        | copyright-a | Show: On, Text: `Designed by RocketTheme`                                               |  
| Default | SmartLoad        |             | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles    |             | Enable: Off, Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller  | copyright-b | Show: On, Text: `Back to Top`                                                           |  
| Default | System Messages  | drawer      | Show: On                                                                                |  
| Default | Reset Settings   | footer-b    | Show: Off, Text: `Reset Settings`                                                       |  
| Default | Google Analytics |             | Enable: Off                                                                             |  

### Menu

| Style   | Option             | Setting                     |  
| :------ | :----------------- | :-------------------------- |  
| Default | Menu Control       | Show: On, Type: Fusion-Menu |  
| Default | Enable ID          | Off                         |  
| Default | Select a Menu      | Main Menu                   |  
| Default | Main Menu Position | navigation-a                |  
| Default | Enable JavaScript  | On                          |  
| Default | Menu Opacity       | 1                           |  
| Default | Menu Effect        | Slide and Fade              |  
| Default | Menu Animation     | Circ.easeOut                |  
| Default | Enable ID          | Off                         |  
| Default | Module Cache       | On                          |  

### Layouts

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 5:7     |  
| Default | Header Positions     | Positions: 1, 12      |  
| Default | Navigation Positions | Positions: 1, 9:3     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 3, 4:4:4   |  
| Default | MainBody Positions   | Positions: 2, 9:3     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 1, 12      |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 3, 4:4:4   |  
| Home    | MainBody Positions   | Positions: 2, 8:4     |
| Home    | Footer Positions     | Positions: 3, 5:3:4   |

### Mobile

| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Cube        |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | header-a                                     |  
| Default | Positions Aliases    | mobile-header     | header-b                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-showcase   | mobile-showcase                              |  
| Default | Positions Aliases    | mobile-feature    | feature-a                                    |  
| Default | Positions Aliases    | mobile-bottom     | mainbottom-b                                 |  
| Default | Positions Aliases    | mobile-footer     | footer-c                                     |  
| Default | Positions Aliases    | mobile-copyright  | mobile-copyright                             |  

### Advanced

| Style   | Option              | Setting                                                              |  
| :------ | :------------------ | :------------------------------------------------------------------- |  
| Default | Gantry Cache        | Enabled: On, Cache Timeout: 900                                      |  
| Default | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |  
| Default | Inline JS File      | Off                                                                  |  
| Default | Display Component   | On                                                                   |  
| Default | Display Mainbody    | On                                                                   |  
| Default | RTL Support         | On                                                                   |  
| Default | Module Overlays     | On                                                                   |  
| Default | Page Suffix         | On                                                                   |  
| Default | RT Typography       | Enabled: On, Typography Styling: Light                               |  
| Default | RT Extensions       | On                                                                   |  
| Default | Third Party Support | Off                                                                  |  
| Default | IE6 Redirect        | On                                                                   |  

### Assignments

| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/reflex.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[reflex2]: assets/reflex2.jpeg