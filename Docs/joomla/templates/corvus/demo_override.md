---
title: Corvus: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Corvus Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][corvus2]

:   1. **Logo**  [7%, 13%, se]
    2. **Menu**  [8%, 52%, se]
    3. **Social Buttons** [6%, 62%, sw]
    4. **To Top**  [90%, 88%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option        | Position | Setting                                 |  
| :------ | :------------ | :------- | :-------------------------------------- |  
| Default | Logo          | header-a | Show: On                                |  
| Default | Font Settings |          | Font Family: Corvus, Font Size: Default |  

### Features
| Style   | Option           | Position    | Setting                                                                    |  
| :------ | :--------------- | :---------- | :------------------------------------------------------------------------- |  
| Default | Social Buttons   | top-a       | Show: On                                                                   |  
| Default | Date             | top-d       | Show: Off                                                                  |  
| Default | Font-Sizer       | feature-b   | Show: Off                                                                  |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding         | copyright-a | Show: Off                                                                  |  
| Default | Copyright        | copyright-a | Show: Off, Text: `Designed by RocketTheme`                                 |  
| Default | To-Top Scroller  | copyright-a | Show: On                                                                   |  
| Default | System Messages  | drawer      | Show: On                                                                   |  
| Default | Reset Settings   | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics |             | Enable: Off                                                                |  

### Menu
| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | header-b                      |  
| Default | Responsive Menu | Selectbox                     |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 8:4     |  
| Default | Header Positions     | Positions: 2, 3:9     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 3, 6:3:3   |  
| Default | MainBottom Positions | Positions: 2, 6:6     |  
| Default | Extension Positions  | Positions: 1, 12      |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 1, 12      |  
| Home    | MainBody Positions   | Positions: 3, 4:5:3   |  
| Home    | MainBottom Positions | Positions: 2, 4:8     |  

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

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Corvus.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[corvus2]: assets/corvus.jpeg