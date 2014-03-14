---
title: Mercado: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Mercado Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/mercado:Mercado

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Mercado Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Mercado2]

:   1. **Logo** [6%, 14%, se]
    2. **Menu** [12%, 33%, se]
    3. **Branding** [91%, 46%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

| Style   | Option              | Position | Setting                                    |  
| :------ | :------------------ | :------- | :----------------------------------------- |  
| Default | Layout Mode         |          | Standard                                   |  
| Default | Background Level    |          | High                                       |  
| Default | Body Level          |          | High                                       |  
| Default | Side Panel Position |          | Left                                       |  
| Default | Read More Style     |          | Button                                     |  
| Default | Font Settings       |          | Font Family: Titillium, Font Size: Default |  

### Features

| Style   | Option              | Position  | Setting                                                                                 |  
| :------ | :------------------ | :-------- | :-------------------------------------------------------------------------------------- |  
| Default | Logo                | top-a     | Show: On, Auto Size: On, Centered: Off                                                  |  
| Default | MainTop Scroller    |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  
| Default | MainBottom Scroller |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  
| Default | Bottom Scroller     |           | Enable: On, Duration: 600, Autoplay: Off, Delay: 5000, Animation: Expo.easeInOut        |  
| Default | Date                | utility-a | Show: Off                                                                               |  
| Default | Font-Sizer          | utility-b | Show: Off                                                                               |  
| Default | Login Panel         | utility-c | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |  
| Default | Popup Panel         | utility-d | Show: Off, Popup Button Text: `Popup Module`                                            |  
| Default | Branding            | copyright | Show: On                                                                                |  
| Default | Copyright           | copyright | Show: Off, Text: `Designed by RocketTheme`                                              |  
| Default | SmartLoad           |           | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles       |           | Enable: Off, Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller     | copyright | Show: Off, Text: `Back to Top`                                                          |  
| Default | System Messages     | drawer    | Show: On                                                                                |  
| Default | Reset Settings      | footer-b  | Show: Off, Text: `Reset Settings`                                                       |  
| Default | Google Analytics    |           | Enable: Off                                                                             |  

### Menu

| Style   | Option                | Setting                                          |  
| :------ | :-------------------- | :----------------------------------------------- |  
| Default | Menu Control          | Show: On, Type: Split-Menu                       |  
| Default | Select a Menu         | Main Menu                                        |  
| Default | Module Cache          | On                                               |  
| Default | Main Menu Position    | navigation                                       |  
| Default | Sub Menu Position     | sidepanel                                        |  
| Default | Sub Menu Class Suffix | Blank                                            |  
| Default | First Level Pill      | Show: On, Duration: 200, Animation: Sine.easeOut |  

### Layouts

| Style   | Option                     | Setting               |  
| :------ | :------------------------- | :-------------------- |  
| Default | Top Positions              | Positions: 3, 4:4:4   |  
| Default | Header Positions           | Positions: 4, 3:3:3:3 |  
| Default | Showcase Positions         | Positions: 1, 12      |  
| Default | Feature Positions          | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions          | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions          | Positions: 3, 3:3:3   |  
| Default | MainBody Positions         | Positions: 2, 6:3     |  
| Default | MainBottom Positions       | Positions: 2, 5:4     |  
| Default | Bottom Positions           | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions           | Positions: 3, 4:4:4   |  
| Default | Component Top Positions    | Positions: 4, 3:3:3:3 |  
| Default | Component Bottom Positions | Positions: 4, 3:3:3:3 |  
| Home    | MainBottom Positions       | Positions: 2, 6:3     |  
| Home    | Footer Positions           | Positions: 3, 2:4:6   |  

### Mobile

| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide       |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | top-a                                        |  
| Default | Positions Aliases    | mobile-header     | header-b                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-showcase   | header-a                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright                                    |  

### Advanced

| Style   | Option             | Setting                                                              |  
| :------ | :----------------- | :------------------------------------------------------------------- |  
| Default | Gantry Cache       | Enabled: On, Cache Timeout: 900                                      |  
| Default | Input Styling      | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |  
| Default | Display Component  | On                                                                   |  
| Default | Display Mainbody   | On                                                                   |  
| Default | RT Typography      | Enabled: On                                                          |  
| Default | RT Extensions      | On                                                                   |  
| Default | Ecwid Styling      | On                                                                   |  
| Default | Tienda Styling     | Off                                                                  |  
| Default | Redshop Styling    | Off                                                                  |  
| Default | RTL Support        | On                                                                   |  
| Default | Build Titles Spans | Off                                                                  |  
| Default | Page Suffix        | On                                                                   |  
| Default | IE6 Redirect       | On                                                                   |  

[demo25]: assets/Mercado.jpg
[menu]: ../../start/menu.md
[Style]: http://www.gantry-framework.org/documentation/joomla/configure
[Mercado2]: assets/mercado2.jpeg