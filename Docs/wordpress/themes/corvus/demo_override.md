---
title: Corvus: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Corvus Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs.

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

| Override   | Option                 | Setting                                     |  
| :--------- | :--------------------- | :------------------------------------------ |  
| Default    | Logo                   | Corvus                                      |  
| Default    | Responsive Menu        | Panel                                       |  
| Default    | Featured Image Size    | Width: 141, Height: 146, Position: Left     |  
| Default    | Font Settings          | Font Family: Corvus, Font Size: Default     |  
| Default    | Pagination             | Enabled: On, Show Count: On, Side Pages: 8  |  
| Default    | Use WordPress Comments | On                                          |  
| Default    | Custom CSS             | Blank                                       |  
| Front Page | Pagination             | Enabled: Off, Show Count: On, Side Pages: 8 |  

### Gizmos

| Override   | Option                | Setting                                     |  
| :--------- | :-------------------- | :------------------------------------------ |  
| Default    | Page Suffix           | Enabled: Off, Class: Blank                  |  
| Default    | Feed Links            | On                                          |  
| Default    | Custom Title Tag      | Blank                                       |  
| Default    | Shortcodes in Widgets | On                                          |  
| Default    | RokStyle              | On                                          |  
| Default    | Google Analytics      | Enabled: Off, UA Code: Blank                |  
| Front Page | Page Suffix           | Enabled: On, Class: `-jan14-home menu-home` |  

### Layouts

| Override   | Option               | Setting               |
| :--------- | :------------------- | :-------------------- |
| Default    | Top Positions        | Positions: 2, 8:4     |
| Default    | Header Positions     | Positions: 2, 3:9     |
| Default    | Showcase Positions   | Positions: 4, 3:3:3:3 |
| Default    | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default    | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainTop Positions    | Positions: 4, 3:3:3:3 |
| Default    | MainBody Positions   | Positions: 2, 9:3     |
| Default    | MainBottom Positions | Positions: 4, 3:3:3:3 |
| Default    | Extension Positions  | Positions: 4, 3:3:3:3 |
| Default    | Bottom Positions     | Positions: 4, 3:3:3:3 |
| Default    | Footer Positions     | Positions: 3, 4:4:4   |
| Default    | Copyright Positions  | Positions: 1, 12      |
| Front Page | Header Positions     | Positions: 4, 4:2:2:2 |
| Front Page | MainBottom Positions | Positions: 2, 4:8     |
| Front Page | MainBody Positions   | Positions: 3, 4:5:3   |

### Advanced

| Override   | Option                  | Setting                                     |  
| :--------- | :---------------------- | :------------------------------------------ |  
| Default    | Layout Mode             | Responsive                                  |  
| Default    | Maintenance Mode        | Off                                         |  
| Default    | Load Transition         | Off                                         |  
| Default    | Display Content         | On                                          |  
| Default    | Display Mainbody        | On                                          |  
| Default    | RTL Support             | On                                          |  
| Default    | Disable Auto Paragraphs | Enabled: On, Content Type: Both             |  
| Default    | Disable Texturize       | Off                                         |  
| Default    | Selectivizr             | Off                                         |  
| Default    | Less Compiler           | CSS Compression: On, Compile: 2, Debug: Off |  
| Default    | IE7 Redirect            | On                                          |  

### Assignments

| Override   | Option | Setting    |  
| :--------- | :----- | :--------- |  
| Front Page | Page   | Front Page |  
| Front Page | Page   | Home Page  |  

[demo]: assets/Corvus2.jpeg
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/