---
title: Modulus: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Modulus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/modulus:Modulus

---

Header Section
-----

![][demo]

:   1. **Gantry Logo** [30%, 6%, se]
    2. **Gantry Menu** [30%, 22%, se]
    3. **Gantry Login Button** [30%, 87%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu
* Gantry Divider
* Gantry Login Button

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

In this instance, the **Per Style Logo** options is selected.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option             | Setting         |  
| :----------------- | :-------------- |  
| Menu               | Main Menu       |  
| Menu Theme         | Fusion          |  
| Limit Levels       | No              |  
| Start Level        | 0               |  
| End Level          | 0               |  
| Show All Children  | Yes             |  
| Show Empty Menu    | No              |  
| Maximum Depth      | 10              |  
| Menu Classes       | Main Navigation |  
| Load CSS           | No              |  
| Enable JavaScript  | Yes             |  
| Menu Opacity       | 1               |  
| Menu Effect        | Slide and Fade  |  
| Hide Delay         | 500             |  
| Menu Animation     | Circ.easeOut    |  
| Menu Duration      | 300             |  
| Enable Pill        | No              |  
| Pill Animation     | Back.easeOut    |  
| Pill Duration      | 400             |  
| Centered Dropdowns | No              |  
| Level 2 X Offset   | -5              |  
| Level 2 Y Offset   | -18             |  
| Submenus X Offset  | 1               |  
| Submenus X Offset  | -6              |  
| Enable Active ID   | No              |  

#### Gantry Login Button and Gantry Login Form

The **Gantry Login Button** widget activates the **Login** pop-up which allows members to log in to their accounts on the frontend of the site. Simply drag this widget to the widget section (there's a separate widget section for the **Gantry Login Form**) and complete the following to replicate the demo.

* Enter `Login` in the **Login Text** field.
* Enter `Logout` in the **Logout Text** field.
* Leaving everything else at its default setting, select **Save**.

The **Gantry Login Form** widget is placed in the **Login** widget position. Here are the options used in this widget.

| Option        | Setting      |  
| :------------ | :----------- |  
| Title         | `Login Form` |  
| User Greeting | `Hi,`        |  

[demo]: assets/demo_1.jpeg
[faq]: faq.md
