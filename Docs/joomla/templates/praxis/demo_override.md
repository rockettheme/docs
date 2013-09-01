---
title: Praxis: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Praxis Template for WordPress
breadcrumb: /joomla:Joomla/!templates:Templated/praxis:Praxis

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Praxis Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Praxis2]

:   1. **Logo**  [9%, 20%, se]
    2. **Menu**  [6%, 50%, sw]
    4. **Copyright**  [91%, 82%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you've selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option        | Position | Setting                                 |  
| :------ | :------------ | :------- | :-------------------------------------- |  
| Default | Logo          | header-a | Show: On                                |  
| Default | Font Settings |          | Font Family: Praxis, Font Size: Default |  

### Features
| Style   | Option           | Position                        | Setting                                                                                                                                 |  
| :------ | :--------------- | :------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------- |  
| Default | Social Buttons   | navigation-b                    | Show: On                                                                                                                                |  
| Default | Side Module      | Inside Left                     | Show: Off                                                                                                                               |  
| Default | Date             | top-d                           | Show: Off                                                                                                                               |  
| Default | Font-Sizer       | feature-b                       | Show: Off                                                                                                                               |  
| Default | Login Panel      | utility-c                       | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                                              |  
| Default | Popup Panel      | utility-d                       | Show: Off, Popup Button Text: `Popup Module`                                                                                            |  
| Default | Branding         | copyright-b                     | Show: Off                                                                                                                               |  
| Default | Copyright        | copyright-b                     | Show: On, Text: `<div class="fp-copyright">&copy; Copyright 2013. Powered by <a href="http://www.rockettheme.com">RocketTheme</a></div>`|  
| Default | To-Top Scroller  | copyright-b                     | Show: Off, Text: `Back to Top`                                                                                                          |  
| Default | System Messages  | drawer                          | Show: On                                                                                                                                |  
| Default | Reset Settings   | copyright-d                     | Show: Off, Text: `Reset Settings`                                                                                                       |  
| Default | Google Analytics |                                 | Enable: Off                                                                                                                             |  
| Home    | Side Module      | Show: On, Position: Inside Left |                                                                                                                                         |  

### Menu
| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | navigation-a                  |  
| Default | Responsive Menu | Panel                         |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Navigation Positions | Positions: 3, 7:2:3   |  
| Default | Header Positions     | Positions: 2, 2:10    |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 1, 12      |  
| Default | MainTop Positions    | Positions: 1, 12      |  
| Default | MainBody Positions   | Positions: 1, 12      |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 1, 12      |  
| Default | Footer Positions     | Positions: 2, 6:6     |  
| Default | Copyright Positions  | Positions: 2, 6:6     |  
| Home    | Footer Positions     | Positions 2, 7:5      |  

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
| Home    | Display Content  | Off                                                     |  
| Home    | Page Suffix      | On                                                      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Praxis.jpg
[menu]: ../../start/menu.md
[Style]: http://gantry-framework.org/documentation/wordpress/configure/
[Praxis2]: assets/praxis.jpeg