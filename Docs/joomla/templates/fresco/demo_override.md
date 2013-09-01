---
title: Fresco: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Fresco Template for WordPress
breadcrumb: /joomla:Joomla/!templates:Templated/fresco:Fresco

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Fresco Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][fresco2]

:   1. **Logo**  [9%, 19%, se]
    2. **Menu**  [6%, 65%, sw]
    3. **Copyright**  [91%, 40%, se]
    4. **To Top**  [92%, 80%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you've selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site which is built on the fixed version of the template.

### Style
| Style   | Option           | Position | Setting                                 |  
| :------ | :--------------- | :------- | :-------------------------------------- |  
| Default | Load Transition  |          | Off                                     |  
| Default | Background Level |          | High                                    |  
| Default | Font Settings    |          | Font Family: Fresco, Font Size: Default |  

### Features
| Style   | Option           | Position    | Setting                                                                                        |  
| :------ | :--------------- | :---------- | :--------------------------------------------------------------------------------------------- |  
| Default | Logo             | header-a    | Show: On, Type: Fresco                                                                         |  
| Default | Date             | utility-a   | Show: Off                                                                                      |  
| Default | Font-Sizer       | utility-b   | Show: Off                                                                                      |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                     |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                                   |  
| Default | Branding         | copyright-a | Show: Off                                                                                      |  
| Default | Copyright        | copyright-b | Show: On, Text: `&copy; 2012 Fresco - Designed by RocketTheme<br />Powered by Gantry Framework`|  
| Default | To-Top Scroller  | copyright-c | On                                                                                             |  
| Default | System Messages  | drawer      | Show: On                                                                                       |  
| Default | Reset Settings   | footer-b    | Show: Off, Text: `Reset Settings`                                                              |  
| Default | Google Analytics |             | Enable: Off                                                                                    |  

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
| Default | Header Positions     | Positions: 3, 4:5:3   |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 1, 12      |  
| Default | Footer Positions     | Positions: 4, 3:3:3:3 |  
| Default | Copyright Positions  | Positions: 2, 6:6     |  
| Home    | MainBody Positions   | Positions: 2, 9:3     |  

### Mobile
| Style   | Option               | Position              | Setting                                      |  
| :------ | :------------------- | :-------------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                       | On                                           |  
| Default | Android Custom Theme |                       | On                                           |  
| Default | Scalable Content     |                       | Off                                          |  
| Default | Standard View Switch | mobile-copyright      | Enable: On                                   |  
| Default | Mobile Menu          |                       | Menu: Main Menu, Menu Animation: Swap        |  
| Default | Image Resize         |                       | Enabled: On, Min-Width: 80, % of Resize: 12% |  
| Default | Positions Aliases    | mobile-drawer         | drawer                                       |  
| Default | Positions Aliases    | mobile-navigation     | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-top            | mobile-top                                   |  
| Default | Positions Aliases    | mobile-content-top    | content-top-b                                |  
| Default | Positions Aliases    | mobile-content-bottom | content-bottom-b                             |  
| Default | Positions Aliases    | mobile-footer         | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright      | mobile-copyright                             |  

### Advanced
| Style   | Option           | Setting                          |  
| :------ | :--------------- | :------------------------------- |  
| Default | Gantry Cache     | Enabled: Off, Cache Timeout: 900 |  
| Default | Display Content  | On                               |  
| Default | Display Mainbody | On                               |  
| Default | RTL Support      | On                               |  
| Default | Page Suffix      | On                               |  
| Default | RT Typography    | Enabled: On, Styling: Light      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[menu]: ../../start/menu.md
[Style]: http://gantry-framework.org/documentation/wordpress/configure/
[fresco2]: assets/fresco.jpeg