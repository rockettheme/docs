---
title: Fracture: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Fracture Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fracture:Fracture

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Fracture Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][fracture2]

:   1. **Logo**  [6%, 11%, se]
    2. **Menu**  [6%, 55%, se]
    3. **Social Buttons** [91%, 60%, se]
    4. **Copyright**  [91%, 10%, se]
    5. **To Top**  [91%, 90%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option          | Position | Setting                                   |  
| :------ | :-------------- | :------- | :---------------------------------------- |  
| Default | Load Transition |          | Off                                       |  
| Default | Font Settings   |          | Font Family: Fracture, Font Size: Default |   

### Features
| Style   | Option           | Position     | Setting                                                                                                 |  
| :------ | :--------------- | :----------- | :------------------------------------------------------------------------------------------------------ |  
| Default | Logo             | navigation-a | Show: On                                                                                                |  
| Default | Social Buttons   | copyright-c  | Show: On                                                                                                |  
| Default | Date             | utility-a    | Show: Off                                                                                               |  
| Default | Font-Sizer       | utility-b    | Show: Off                                                                                               |  
| Default | Login Panel      | utility-c    | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                              |  
| Default | Popup Panel      | utility-d    | Show: Off, Popup Button Text: `Popup Module`                                                            |  
| Default | Branding         | copyright-c  | Show: Off                                                                                               |  
| Default | Copyright        | copyright-a  | Show: On, Text: `Designed by RocketTheme`                                                               |  
| Default | SmartLoad        |              | Show: Off, Offset Y: 200, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles    |              | Text: Load More Articles, Hide Pagination: On                                                           |  
| Default | To-Top Scroller  | copyright-d  | Show: On                                                                                                |  
| Default | System Messages  | drawer       | Show: On                                                                                                |  
| Default | Reset Settings   | footer-b     | Show: Off, Text: `Reset Settings`                                                                       |  
| Default | Google Analytics |              | Enable: Off                                                                                             |  

### Menu
| Style   | Option            | Setting                     |  
| :------ | :---------------- | :-------------------------- |  
| Default | Menu Control      | Show: On, Type: Fusion-Menu |  
| Default | Select a Menu     | Main Menu                   |  
| Default | Position          | navigation-b                |  
| Default | Enable Menu Count | On                          |  
| Default | Enable JavaScript | On                          |  
| Default | Menu Opacity      | 1                           |  
| Default | Menu Effect       | Slide and Fade              |  
| Default | Menu Delay        | 500                         |  
| Default | Menu Animation    | Circ.easeOut                |  
| Default | Menu Duration     | 300                         |  
| Default | Enable ID         | Off                         |  
| Default | Module Cache      | On                          |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Header Positions     | Positions: 4, 3:3:3:3 |  
| Default | Navigation Positions | Positions: 2, 3:9     |  
| Default | Showcase Positions   | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 1, 12      |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 1, 12      |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 4, 3:4:3:2 |   

### Advanced
| Style   | Option            | Setting                                                 |  
| :------ | :---------------- | :------------------------------------------------------ |  
| Default | Layout Mode       | Responsive                                              |  
| Default | Display Component | On                                                      |  
| Default | Display Mainbody  | On                                                      |  
| Default | RTL Support       | On                                                      |  
| Default | Page Suffix       | On                                                      |  
| Default | RT Typography     | Enabled: On, Styling: Light                             |  
| Default | Selectivizr       | Off                                                     |  
| Default | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect      | On                                                      |  
| Default | K2 Styling        | Off                                                     |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[menu]: ../../start/menu.md
[Style]: http://www.gantry-framework.org/documentation/joomla/configure
[fracture2]: assets/fracture.jpeg