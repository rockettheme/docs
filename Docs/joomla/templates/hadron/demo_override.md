---
title: Hadron: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Hadron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hadron:Hadron

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Hadron Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Hadron2]

:   1. **Logo**  [6%, 43%, se]
    2. **Menu**  [9%, 15%, se]
    3. **Social Buttons** [9%, 84%, sw]
    4. **Branding** [89%, 45%, se]
    5. **Copyright**  [92%, 41%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style

| Style   | Option        | Position | Setting                                   |  
| :------ | :------------ | :------- | :---------------------------------------- |  
| Default | Logo          | header-a | Show: On                                  |  
| Default | Font Settings |          | Font Family: Hadron, Font Size: Default |  

### Features

| Style   | Option             | Position     | Setting                                                                                                                                   |  
| :------ | :----------------- | :----------- | :---------------------------------------------------------------------------------------------------------------------------------------- |  
| Default | Social Buttons     | navigation-b | Show: On                                                                                                                                  |  
| Default | Chart              |              | Show: On                                                                                                                                  |  
| Default | Coming Soon Page   |              | Show: Off                                                                                                                                 |  
| Default | Email Subscription |              | Show: On                                                                                                                                  |  
| Default | Feedburner URI     |              | Blank                                                                                                                                     |  
| Default | Date               | utility-a    | Show: Off, Client-Side Date: Off                                                                                                          |  
| Default | Font-Sizer         | utility-b    | Show: Off                                                                                                                                 |  
| Default | Login Panel        | utility-c    | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                                                                |  
| Default | Popup Panel        | utility-d    | Show: Off, Popup Button Text: `Popup Module`                                                                                              |  
| Default | Branding           | copyright-a  | Show: Off                                                                                                                                 |  
| Default | Copyright          | copyright-a  | Show: On, Text: `<div class="rt-small-text">&copy; Copyright 2014. Powered by <a href="http://www.rockettheme.com">RocketTheme</a>.</div>`|  
| Default | To-Top Scroller    | bottom-b     | Show: Off                                                                                                                                 |  
| Default | System Messages    | drawer       | Show: On                                                                                                                                  |  
| Default | Reset Settings     | copyright-d  | Show: Off, Text: `Reset Settings`                                                                                                         |  
| Default | Google Analytics   |              | Enable: Off                                                                                                                               |  
| Home    | Branding           | copyright-a  | Show: On                                                                                                                                  |
| Home    | To-Top Scroller    | bottom-b     | Show: On, Text: `<span class="icon-angle-up"></span>`                                                                                     |

![][socialbuttons]

>> NOTE: The look of the **Social Buttons** and **RokAjaxSearch** module presented in our demo is only possible because the search suffix was put in the Feature Suffix field in the Social Buttons feature. The RokAjaxSearch module position is also set to navigation-c.

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

| Style   | Option                   | Setting               |  
| :------ | :----------------------- | :-------------------- |  
| Default | Top Positions            | Positions: 4, 3:3:3:3 |  
| Default | Header Positions         | Positions: 1, 12      |  
| Default | Navigation Positions     | Positions: 3, 8:2:2   |  
| Default | Showcase Positions       | Positions: 1, 12      |  
| Default | Utility Positions        | Positions: 1, 12      |  
| Default | Feature Positions        | Positions: 1, 12      |  
| Default | MainTop Positions        | Positions: 2, 6:6     |  
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions       | Positions: 1, 12      |  
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions      | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions         | Positions: 1, 12      |  
| Default | Footer Positions         | Positions: 1, 12      |  
| Default | Copyright Positions      | Positions: 1, 12      |  
| Home    | Navigation Positions     | Positions: 3, 8:2:2   |
| Home    | MainTop Positions        | Positions: 2, 8:4     |
| Home    | Bottom Positions         | Positions: 1, 12      |

### Advanced
| Style   | Option           | Setting                                                 |  
| :------ | :--------------- | :------------------------------------------------------ |  
| Default | Layout Mode      | Responsive                                              |  
| Default | Load Transition  | Off                                                     |  
| Default | Display Content  | On                                                      |  
| Default | Mainbody Enabled | On                                                      |  
| Default | RTL Support      | Off                                                     |  
| Default | Page Suffix      | On                                                      |  
| Default | Selectivizr      | On                                                      |  
| Default | Less Compiler    | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect     | On                                                      |  
| Default | Demo Styling     | On                                                      |  
| Default | K2 Styling       | On                                                      |  
| Home    | Display Content  | Off                                                     |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/hadron.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Hadron2]: assets/hadron2.jpeg
[socialbuttons]: assets/socialbuttons.jpg
