---
title: Lexicon: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Lexicon Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][lexicon2]

:   1. **Logo**  [7%, 18%, se]
    2. **Menu**  [7%, 75%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style

![Style Settings][style2]

| Style   | Option        | Position | Setting                                             |  
| :------ | :------------ | :------- | :-------------------------------------------------- |  
| Default | Logo          | header-a | Show: On, Type: Preset 1, Background Color: #1A1C1E |  
| Default | Demo Style    |          | Preset 1                                            |  
| Default | Font Settings |          | Font Family: Lexicon, Font Size: Default            |  

### Features

![Features Settings][features]

| Style   | Option             | Position    | Setting                                                                    |  
| :------ | :----------------- | :---------- | :------------------------------------------------------------------------- |  
| Default | Social Buttons     | copyright-a | Show: Off                                                                  |  
| Default | Chart              |             | Show: On                                                                   |  
| Default | Coming Soon Page   |             | Show: Off                                                                  |  
| Default | Email Subscription |             | Show: On                                                                   |  
| Default | Feedburner URI     |             | Blank                                                                      |  
| Default | System Messages    | drawer      | On                                                                         |  
| Default | Date               | utility-a   | Show: Off, Client-Side Date: Off                                           |  
| Default | Font-Sizer         | utility-b   | Show: Off                                                                  |  
| Default | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding           | copyright-a | Show: Off                                                                  |  
| Default | Copyright          | copyright-a | Show: Off, Text: `Designed by RocketTheme`                                 |  
| Default | To-Top Scroller    | bottom-b    | Show: Off, Text: `Back to Top`                                             |  
| Default | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics   |             | Enable: Off                                                                |  

### Menu

![Menu Settings][menu2]

| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | header-b                      |  
| Default | Responsive Menu | Panel                         |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts

![Layouts Settings][layouts]

| Style   | Option                   | Setting               |  
| :------ | :----------------------- | :-------------------- |  
| Default | Header Positions         | Positions: 2, 4:8     |  
| Default | Top Positions            | Positions: 4, 3:3:3:3 |  
| Default | Showcase Positions       | Positions: 1, 12      |  
| Default | Utility Positions        | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions        | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions        | Positions: 4, 3:3:3:3 |  
| Default | ExpandedTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions       | Positions: 2, 4:8     |  
| Default | ExpandedBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | MainBottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions      | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions         | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions         | Positions: 3, 4:4:4   |  
| Default | Copyright Positions      | Positions: 4, 3:3:3:3 |  
| Home    | Header Positions         | Positions: 2, 3:9     |  
| Home    | MainBody Positions       | Positions: 2, 3:9     |  

### Advanced

![Advanced Settings][advanced]

| Style   | Option           | Setting                                                 |  
| :------ | :--------------- | :------------------------------------------------------ |  
| Default | Layout Mode      | Responsive                                              |  
| Default | Load Transition  | Off                                                     |  
| Default | Display Component  | On                                                      |  
| Default | Mainbody Enabled | On                                                      |  
| Default | RTL Support      | Off                                                     |  
| Default | Page Suffix      | On                                                      |  
| Default | Selectivizr      | On                                                      |  
| Default | Less Compiler    | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect     | On                                                      |  
| Default | Demo Styling     | On                                                      |  
| Default | K2 Styling       | On                                                      |  
| Home    | Display Component | Off                                                     |
  

### Assignments

![Assignments Settings][assignments]

| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Lexicon.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[lexicon2]: assets/lexicon2.jpeg
[assignments]: assets/assignments_settings.jpeg
[style2]: assets/style_settings.jpeg
[advanced]: assets/advanced_settings.jpeg
[layouts]: assets/layouts_settings.jpeg
[menu2]: assets/menu_settings.jpeg
[features]: assets/features_settings.jpeg