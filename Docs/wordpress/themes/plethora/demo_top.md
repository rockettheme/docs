---
title: Plethora: Recreating the Demo - Top
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Top Section
-----

![][demo]

:   1. **Custom Menu** [35%, 20%, se]
    2. **Gantry Social Buttons** [35%, 72%, se]

Here is the widget breakdown for the Top section:

* Gantry Breadcrumbs
* Gantry Divider
* Custom Menu
* Gantry Divider
* Gantry Social Buttons

The **Gantry Breadcrumbs** module is invisible on the front page because that is considered home. However, as you navigate around the demo site, you will see the breadcrumbs appear. The **Top** module position is set in the default widget settings so it remains consistent throughout the site.

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position. We entered `fp-breadcrumbs` in the **Custom Variations** field.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu

The **Custom Menu** widget allows us to add an extra menu somewhere on the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Set the **Custom Variations** field to `rt-horizmenu fp-topmenu`.
* Leaving all other options at their default settings, click **Save**. 

#### Gantry Social Buttons

The Gantry Social Buttons widget creates a set of social buttons on the top of the page. Filling this out is fairly straightforward. Once you have clicked and dragged the **Gantry Social Buttons** widget in place, you will want to add your various social URLs to their respective fields. Once this is done, simply hit **Save** and check the site. 

Here is a breakdown of the settings we used:

| Field       | Setting          |
| :---------- | :----------      |
| Icon 1      | `fa fa-twitter`  |
| Text 1      |                  |
| Link 1      | `#`              |
| Icon 2      | `fa fa-facebook` |
| Text 2      |                  |
| Link 2      | `#`              |
| Icon 3      | `fa fa-rss`      |
| Text 3      |                  |
| Link 3      | `#`              |


[demo]: assets/demo_1.jpeg
