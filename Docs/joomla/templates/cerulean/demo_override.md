---
title: Cerulean: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Cerulean Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Cerulean Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][cerulean2]

:   1. **Logo**  [6%, 13%, se]
    2. **Menu**  [8%, 47%, sw]
    4. **Copyright**  [91%, 13%, se]
    5. **To Top**  [91%, 80%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option        | Position | Setting                                   |  
| :------ | :------------ | :------- | :---------------------------------------- |  
| Default | Logo          | top-a    | Show: On                                  |  
| Default | Font Settings |          | Font Family: Cerulean, Font Size: Default |  

### Features
| Style   | Option           | Position    | Setting                                                                    |  
| :------ | :--------------- | :---------- | :------------------------------------------------------------------------- |  
| Default | Social Buttons   |             | Show: Off                                                                  |  
| Default | Date             | top-d       | Show: Off                                                                  |  
| Default | Font-Sizer       | feature-b   | Show: Off                                                                  |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding         | copyright-a | Show: Off                                                                  |  
| Default | Copyright        | copyright-a | Show: On, Text: `Designed by RocketTheme`                                  |  
| Default | To-Top Scroller  | copyright-b | Show: On, Text: `TOP`                                                      |  
| Default | System Messages  | drawer      | Show: On                                                                   |  
| Default | Reset Settings   | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics |             | Enable: Off                                                                |   

### Menu
| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | header-a                      |  
| Default | Responsive Menu | Panel                         |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 4:8     |  
| Default | Header Positions     | Positions: 1, 12      |  
| Default | Showcase Positions   | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 3, 5:3:4   |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 2, 10:2    |  

### Advanced
| Style   | Option           | Setting                                                 |  
| :------ | :--------------- | :------------------------------------------------------ |  
| Default | Layout Mode      | Responsive                                              |  
| Default | Load Transition  | Off                                                     |  
| Default | Display Content  | On                                                      |  
| Default | Mainbody Enabled | On                                                      |  
| Default | RTL Support      | On                                                      |  
| Default | Page Suffix      | On                                                      |  
| Default | Selectivizr      | Off                                                     |  
| Default | Less Compiler    | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect     | On                                                      |  
| Default | K2 Styling       | On                                                      |   

[demo25]: assets/Cerulean.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[cerulean2]: assets/cerulean.jpeg