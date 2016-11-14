---
title: Ionosphere: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Ionosphere Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ionosphere:Ionosphere

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Ionosphere Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][ionosphere2]

:   1. **Logo**  [6%, 21%, se]
    2. **Menu**  [9%, 60%, sw]
    4. **Copyright**  [92%, 20%, se]
    5. **To Top**  [92%, 52%, sw]
    6. **Branding** [92%, 80%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site which is built on the fixed version of the template.

### Style
| Style   | Option          | Position | Setting                                     |  
| :------ | :-------------- | :------- | :------------------------------------------ |  
| Default | Load Transition |          | On                                          |  
| Default | Style Panel     | Panel    | Show: On                                    |  
| Default | Header Width    |          | Full                                        |  
| Defau;t | Footer Width    |          | Full                                        |  
| Default | Font Settings   |          | Font Family: Ionosphere, Font Size: Default |  

### Features
| Style   | Option           | Position    | Setting                                                                                                |  
| :------ | :--------------- | :---------- | :----------------------------------------------------------------------------------------------------- |  
| Default | Logo             | header-a    | Show: On, Logo Text: On, Show Icon: On, Auto Size: On                                                  |  
| Default | Social Buttons   | social      | Show: On                                                                                               |  
| Default | Date             | utility-a   | Show: Off                                                                                              |  
| Default | Font-Sizer       | utility-b   | Show: Off                                                                                              |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                             |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                                           |  
| Default | Branding         | copyright-c | Show: On                                                                                               |  
| Default | Copyright        | copyright-a | Show: On, Text: `Designed by RocketTheme`                                                              |  
| Default | More Articles    |             | Enable: Off, Text: Load More Articles, Hide Pagination: On                                             |  
| Default | SmartLoad        |             | Show: On, Offset Y: 200, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | To-Top Scroller  | copyright-b | Show: On                                                                                               |  
| Default | System Messages  | drawer      | Show: On                                                                                               |  
| Default | Reset Settings   | copyright-d | Show: Off, Text: `Reset Settings`                                                                      |  
| Default | Google Analytics |             | Enable: Off                                                                                            |  

### Menu
| Style   | Option            | Setting                     |  
| :------ | :---------------- | :-------------------------- |  
| Default | Menu Control      | Show: On, Type: Fusion-Menu |  
| Default | Select a Menu     | Main Menu                   |  
| Default | Position          | navigation-a                |  
| Default | Enable JavaScript | On                          |  
| Default | Menu Opacity      | 1                           |  
| Default | Menu Effect       | Slide + Fade                |  
| Default | Menu Delay        | 500                         |  
| Default | Menu Animation    | Circ.easeOut                |  
| Default | Menu Duration     | 300                         |  
| Default | Enable ID         | Off                         |  
| Default | Module Cache      | On                          | 

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Navigation Positions | Positions: 1, 12      |  
| Default | Header Positions     | Positions: 2, 5:7     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 3, 4:4:4   |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 3, 4:4:4   |  

### Mobile
| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Swap        |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 12% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | mobile-top                                   |  
| Default | Positions Aliases    | mobile-header     | header-a                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-extension  | extension-a                                  |  
| Default | Positions Aliases    | mobile-bottom     | bottom-b                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright-c                                  |   

### Advanced
| Style   | Option            | Setting                                                                                                 |  
| :------ | :---------------- | :------------------------------------------------------------------------------------------------------ |  
| Default | Gantry Cache      | Enabled: Off, Cache Timeout: 900                                                                        |  
| Default | Input Styling     | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin','#vmMainPage','#community-wrap'` |  
| Default | Display Component | On                                                                                                      |  
| Default | Display Mainbody  | On                                                                                                      |  
| Default | RTL Support       | On                                                                                                      |  
| Default | Module Overlays   | On                                                                                                      |  
| Default | Page Suffix       | On                                                                                                      |  
| Default | RT Typography     | Enabled: On, Typography Styling: Light                                                                  |  
| Default | K2 Styling        | On                                                                                                      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Ionosphere.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[ionosphere2]: assets/ionosphere.jpeg