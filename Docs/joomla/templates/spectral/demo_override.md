---
title: Spectral: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Spectral Template for Joomla
breadcrumb: /joomla:Joomla/!Templates:Templates/spectral:Spectral

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Spectral Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Spectral2]

:   1. **Logo**  [6%, 14%, se]
    2. **Menu**  [6%, 46%, se]
    3. **Social Buttons** [12%, 91%, sw]
    4. **Copyright** [91%, 15%, se]
    5. **To Top**  [91%, 87%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style

| Style   | Option           | Position | Setting                                   |  
| :------ | :--------------- | :------- | :---------------------------------------- |  
| Default | Logo             | header-a | Show: On                                  |  
| Default | Font Settings    |          | Font Family: Spectral, Font Size: Default |  
| Default | Mainbody Overlap |          | Off                                       |  
| Home    | Mainbody Overlap |          | On                                        |  

### Features

| Style   | Option              | Position    | Setting                                                                    |  
| :------ | :------------------ | :---------- | :------------------------------------------------------------------------- |  
| Default | Social Buttons      | social      | Show: On                                                                   |  
| Default | Chart               |             | On                                                                         |  
| Default | Coming Soon Page    |             | Off                                                                        |  
| Default | Email Subscriptions |             | On                                                                         |  
| Default | Date                | utility-a   | Show: Off                                                                  |  
| Default | Font-Sizer          | utility-b   | Show: Off                                                                  |  
| Default | Login Panel         | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel         | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding            | copyright-a | Show: On                                                                   |  
| Default | Copyright           | copyright-a | Show: On, Text: `Designed by <strong>RocketTheme</strong>`                 |  
| Default | To-Top Scroller     | copyright-c | Show: On                                                                   |  
| Default | System Messages     | drawer      | Show: On                                                                   |  
| Default | Reset Settings      | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics    |             | Enable: Off                                                                |  

### Menu

| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | header-b                      |  
| Default | Responsive Menu | Panel                         |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts

| Style   | Option                   | Setting               |  
| :------ | :----------------------- | :-------------------- |  
| Default | Top Positions            | Positions: 2, 3:9     |  
| Default | Header Positions         | Positions: 4, 3:3:3:3 |  
| Default | Showcase Positions       | Positions: 1, 12      |  
| Default | Feature Positions        | Positions: 2, 6:6     |  
| Default | Utility Positions        | Positions: 2, 6:6     |  
| Default | MainTop Positions        | Positions: 1, 12      |  
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions       | Positions: 3, 8:4     |  
| Default | MainBottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions      | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions         | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions         | Positions: 2, 6:6     |  
| Default | Copyright Positions      | Positions: 3, 4:6:2   |  
| Home    | Showcase Positions       | Positions: 1, 12      |  
| Home    | Utility Positions        | Positions: 2, 6:6     |  
| Home    | Feature Positions        | Positions: 2, 6:6     |  
| Home    | Footer Positions         | Positions: 2, 7:5     |  

### Advanced

| Style   | Option            | Setting                                                 |  
| :------ | :---------------- | :------------------------------------------------------ |  
| Default | Layout Mode       | Responsive                                              |  
| Default | Load Transition   | Off                                                     |  
| Default | Display Component | On                                                      |  
| Default | Mainbody Enabled  | On                                                      |  
| Default | RTL Support       | On                                                      |  
| Default | Page Suffix       | On                                                      |  
| Default | Selectivizr       | Off                                                     |  
| Default | Less Compiler     | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect      | On                                                      |  
| Default | Demo Styling      | On                                                      |  
| Default | K2 Styling        | Off                                                     | 

### Assignments

| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/spectral.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Spectral2]: assets/spectral.jpeg