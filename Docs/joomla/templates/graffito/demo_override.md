---
title: Graffito: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Graffito Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/graffito:Graffito

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Graffito Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][graffito2]

:   1. **Logo**  [6%, 10%, se]
    2. **Menu**  [6%, 42%, se]
    3. **Social Buttons** [6%, 90%, sw]
    4. **Copyright**  [91%, 10%, se]
    5. **To Top**  [91%, 90%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option        | Position | Setting                                   |  
| :------ | :------------ | :------- | :---------------------------------------- |  
| Default | Logo          | header-a | Show: On                                  |  
| Default | Font Settings |          | Font Family: Graffito, Font Size: Default |  

### Features
| Style   | Option           | Position    | Setting                                                                    |  
| :------ | :--------------- | :---------- | :------------------------------------------------------------------------- |  
| Default | Social Buttons   | header-c    | Show: On                                                                   |  
| Default | Date             | top-d       | Show: Off                                                                  |  
| Default | Font-Sizer       | feature-b   | Show: Off                                                                  |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding         | copyright-a | Show: Off                                                                  |  
| Default | Copyright        | copyright-a | Show: On, Text: `Designed by RocketTheme`                                  |  
| Default | To-Top Scroller  | copyright-c | Show: On                                                                   |  
| Default | System Messages  | drawer      | Show: On                                                                   |  
| Default | Reset Settings   | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics |             | Enable: Off                                                                |  

### Menu
| Style   | Option            | Setting                     |  
| :------ | :---------------- | :-------------------------- |  
| Default | Menu Control      | Show: On, Type: Fusion-Menu |  
| Default | Select a Menu     | Main Menu                   |  
| Default | Position          | header-b                    |  
| Default | Enable JavaScript | On                          |  
| Default | Menu Effect       | Slide and Fade              |  
| Default | Menu Delay        | 500ms                       |  
| Default | Menu Animation    | Circ.easeOut                |  
| Default | Menu Duration     | 300ms                       |  
| Default | Enable ID         | Off                         |  
| Default | Module Cache      | On                          |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Header Positions     | Positions: 3, 3:7:2   |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 2, 4:8     |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 3, 4:6:2   |  

### Advanced
| Style   | Option           | Setting                                                 |  
| :------ | :--------------- | :------------------------------------------------------ |  
| Default | Layout Mode      | Responsive                                              |  
| Default | Load Transition  | Off                                                     |  
| Default | Display Content  | On                                                      |  
| Default | Mainbody Enabled | On                                                      |  
| Default | RTL Support      | On                                                      |  
| Default | Page Suffix      | Off                                                     |  
| Default | Selectivizr      | Off                                                     |  
| Default | Less Compiler    | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect     | On                                                      |  
| Default | K2 Styling       | On                                                      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Graffito.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[graffito2]: assets/graffito.jpeg