---
title: Graffito: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Graffito Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/graffito:Graffito

---

Header Section
-----
![][demo1]

Here's the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu
* Gantry Divider
* Gantry Social Buttons

The header section remains the same across the entire demo site. For this reason, it exists in the default **Widget Override** menu. It's also a fairly simple section to set up.

#### Gantry Logo
The first thing you'll need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu
The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there. 

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             |        Setting |  
| :----------------- | -------------: |  
| Menu               |      Main Menu |  
| Menu Theme         |         Fusion |  
| Limit Levels       |             No |  
| Start Level        |              0 |  
| End Level          |              0 |  
| Show All Children  |            Yes |  
| Show Empty Menu    |             No |  
| Maximum Depth      |             10 |  
| Enable JavaScript  |            Yes |  
| Menu Opacity       |              1 |  
| Menu Effect        | Slide and Fade |  
| Hide Delay         |            500 |  
| Menu Animation     |   Circ.easeOut |  
| Menu Duration      |            300 |  
| Centered Dropdowns |             No |  
| Level 2 X Offset   |            -10 |  
| Level 2 Y Offset   |            -10 |  
| Submenus X Offset  |              0 |  
| Submenus Y Offset  |              0 |  
| Enable ActiveID    |             No |  
| Custom Chrome      |           Menu |  

#### Gantry Social Buttons
The Gantry Social Buttons widget creates a floating set of social buttons on the left side of the page. We placed it in the Header widget section so it's present in all of the demo pages. Filling this out is fairly straightforward as you'll want to add your various social URLs to their respective fields before hitting **Save**.

[demo1]: assets/wp_graffito_demo_1.jpeg
[faq]: faq.md