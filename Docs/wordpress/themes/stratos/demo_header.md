---
title: Stratos: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Stratos Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/stratos:Stratos

---

Header Section
-----

![][demo]

Here's the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu
* Gantry Divider
* Gantry Login Button

The header section remains the same across the entire demo site. For this reason, it exists in the default **Widget Override** menu. It's also a fairly simple section to set up.

#### Gantry Logo

The first thing you'll need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there. 

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting   |  
| :---------------- | :-------- |  
| Menu              | Main Menu |  
| Menu Theme        | Dropdown  |  
| SplitMenu Style   | None      |  
| Limit Levels      | No        |  
| Start Level       | 0         |  
| End Level         | 0         |  
| Show All Children | Yes       |  
| Show Empty Menu   | No        |  
| Maximum Depth     | 10        |  
| Custom Chrome     | Menu      |  

#### Gantry Login Button

The **Gantry Login Button** widget activates the **Login** pop-up which allows members to log in to their accounts on the frontend of the site. Simply drag this widget to the widget section (there's a separate widget section for the **Gantry Login Form**) and complete the following to replicate the demo.

* Enter `Member Login` in the **Login Text** field.
* Enter `Logout` in the **Logout Text** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_1.jpeg
[faq]: faq.md