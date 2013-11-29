---
title: Kirigami: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Kirigami Template for WordPress
breadcrumb: /joomla:Joomla/!templates:Templated/kirigami:Kirigami

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Kirigami Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][kirigami2]

:   1. **Logo**  [6%, 10%, se]
    2. **Menu**  [6%, 50%, se]
    3. **Social Buttons** [10%, 90%, sw]
    4. **Copyright**  [92%, 10%, se]
    5. **To Top**  [92%, 90%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option          | Position | Setting                                  |  
| :------ | :-------------- | :------- | :--------------------------------------- |  
| Default | Load Transition |          | Off                                      |  
| Default | Web Fonts       |          | Show: Off                                |  
| Default | Font Settings   |          | Font Family: Kirigami, Font Size: Default |   

### Features
| Style   | Option           | Position    | Setting                                                                    |  
| :------ | :--------------- | :---------- | :------------------------------------------------------------------------- |  
| Default | Logo             | header-a    | Show: On                                                                   |  
| Default | Social Buttons   |             | Show: Off                                                                  |  
| Default | Date             | utility-a   | Show: Off                                                                  |  
| Default | Font-Sizer       | utility-b   | Show: Off                                                                  |  
| Default | Login Panel      | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel      | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding         | copyright-c | Show: Off                                                                  |  
| Default | Copyright        | copyright-a | Show: On, Text: `Designed by RocketTheme`                                  |  
| Default | SmartLoad        |             | Show: Off                                                                  |  
| Default | More Artices     |             | Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller  | copyright-c | Show: On                                                                   |  
| Default | System Messages  | drawer      | Show: On                                                                   |  
| Default | Reset Settings   | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics |             | Enable: Off                                                                |  
| Home    | Social Buttons   |             | Show: On, Social Text: Follow                                              |  

### Menu
| Style   | Option            | Setting                     |  
| :------ | :---------------- | :-------------------------- |  
| Default | Menu Control      | Show: On, Type: Fusion-Menu |  
| Default | Select a Menu     | Main Menu                   |  
| Default | Position          | header-b                    |  
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
| Default | Header Positions     | Positions: 2, 3:9     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 1, 12      |  
| Default | MainBody Positions   | Positions: 2, 9:3     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 3, 4:6:2   |  

### Advanced
| Style   | Option           | Setting                                |  
| :------ | :--------------- | :------------------------------------- |  
| Default | Gantry Cache     | Enabled: Off, Cache Timeout: 900       |  
| Default | Display Content  | On                                     |  
| Default | Mainbody Enabled | On                                     |  
| Default | RTL Support      | On                                     |  
| Default | Module Overlays  | On                                     |  
| Default | Page Suffix      | Off                                    |  
| Default | Page Suffix      | On                                     |  
| Default | RT Typography    | Enabled: On, Typography Styling: Light |  
| Default | K2 Styling       | On                                     |  
| Default | Selectivizr      | Off                                    |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Kirigami.jpg
[menu]: ../../start/menu.md
[Style]: http://www.gantry-framework.org/documentation/joomla/configure
[kirigami2]: assets/kirigami.jpeg