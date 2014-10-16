---
title: Nuance: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Header Section
-----

![][demo]

:   1. **Gantry Logo** [40%, 6%, se]
    2. **Gantry Menu** [40%, 40%, se]
    3. **Text** [40%, 74%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu
* Gantry Divider
* Text

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting      |  
| :---------------- | :----------- |  
| Menu              | Main Menu    |  
| Menu Theme        | Dropdown     |  
| SplitMenu Style   | Sidebar Menu |  
| Limit Levels      | No           |  
| Start Level       | 0            |  
| End Level         | 0            |  
| Show All Children | Yes          |  
| Show Empty Menu   | No           |  
| Maximum Depth     | 10           |  
| Custom Chrome     | Menu         |  

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<span class="rt-floatleft"><img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-header/img-01.jpg" alt="image"></span>
<span class="rt-floatright hidden-tablet"><i class="fa fa-chevron-down"></i></span>
<span>
    <small><span class="hidden-tablet">Template by</span><span class="visible-tablet">By</span></small><br />
    <span>RocketTheme<span class="hidden-tablet"> LLC</span></span>
</span> 
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-header-c` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_2.jpeg
[faq]: faq.md
