---
title: Diametric: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Diametric Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/diametric:Diametric

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Diametric Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][diametric2]

:   1. **Logo**  [6%, 47%, se]
    2. **Menu**  [6%, 25%, se]
    5. **Branding**  [91%, 20%, se]
    6. **To-Top** [91%, 51%, sw]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site which is built on the fixed version of the template.

### Style
| Style   | Option          | Position | Setting                                    |  
| :------ | :-------------- | :------- | :----------------------------------------- |  
| Default | Text Shadows    |          | On                                         |  
| Default | Load Transition |          | On                                         |  
| Default | Font Settings   |          | Font Family: Diametric, Font Size: Default |  

### Features
| Style   | Option           | Position     | Setting                                                                    |  
| :------ | :--------------- | :----------- | :------------------------------------------------------------------------- |  
| Default | Logo             | navigation-a | Show: Off                                                                  |  
| Default | Social Buttons   |              | Show: Off                                                                  |  
| Default | Date             | controls     | Show: Off                                                                  |  
| Default | Font-Sizer       | controls     | Show: Off                                                                  |  
| Default | Login Panel      | controls     | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Popup Panel      | controls     | Show: Off, Popup Button Text: `Popup Module`                               |  
| Default | Branding         | copyright-a  | Show: On                                                                   |  
| Default | Copyright        | copyright-a  | Show: Off, Text: `Designed by RocketTheme`                                 |  
| Default | SmartLoad        |              | Show: On, Offset Y: 200                                                    |  
| Default | More Articles    |              | Enable: Off, Text: Load More Articles, Hide Pagination: On                 |  
| Default | To-Top Scroller  | copyright-b  | Show: On                                                                   |  
| Default | System Messages  | drawer       | Show: On                                                                   |  
| Default | Reset Settings   | copyright-d  | Show: Off, Text: `Reset Settings`                                          |  
| Default | Google Analytics |              | Enable: Off                                                                |  

### Menu
| Style   | Option            | Setting                                                 |  
| :------ | :---------------- | :------------------------------------------------------ |  
| Default | Menu Control      | Show: On, Centering: Off, Offset: 48, Type: Fusion-Menu |  
| Default | Select a Menu     | Main Menu                                               |  
| Default | Position          | navigation-b                                            |  
| Default | Enable JavaScript | On                                                      |  
| Default | Menu Opacity      | 1                                                       |  
| Default | Menu Effect       | Slide + Fade                                            |  
| Default | Menu Delay        | 500                                                     |  
| Default | Menu Animation    | Circ.easeOut                                            |  
| Default | Menu Duration     | 300                                                     |  
| Default | Enable ID         | Off                                                     |  
| Default | Module Cache      | On                                                      |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Navigation Positions | Positions: 1, 12      |  
| Default | Header Positions     | Positions: 1, 12      |  
| Default | Showcase Positions   | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions    | Positions: 2, 6:6     |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 1, 12      |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 1, 12      |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 2, 6:6     |  
| Home    | Feature Positions    | Positions: 2, 8:4     |  

### Mobile
| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Swap        |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 12% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | mobile-top                                   |  
| Default | Positions Aliases    | mobile-showcase   | showcase-a                                   |  
| Default | Positions Aliases    | mobile-feature    | feature-a                                    |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-utility    | mobile-utility                               |  
| Default | Positions Aliases    | mobile-extension  | extension-a                                  |  
| Default | Positions Aliases    | mobile_bottom     | bottom-a                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright-a                                  |  

### Advanced
| Style   | Option            | Setting                                                                                                 |  
| :------ | :---------------- | :------------------------------------------------------------------------------------------------------ |  
| Default | Gantry Cache      | Enabled: Off, Cache Timeout: 900                                                                        |  
| Default | Input Styling     | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin','#vmMainPage','#community-wrap'` |  
| Default | Input JS File     | Off                                                                                                     |  
| Default | Display Component | On                                                                                                      |  
| Default | Display Mainbody  | On                                                                                                      |  
| Default | RTL Support       | On                                                                                                      |  
| Default | Build Title Spans | On                                                                                                      |  
| Default | Page Suffix       | On                                                                                                      |  
| Default | RT Typography     | Enabled: On, Typography Styling: Light                                                                  |  
| Default | RT Extensions     | On                                                                                                      |  
| Default | IE6 Redirect      | On                                                                                                      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Diametric.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[diametric2]: assets/diametric.jpeg