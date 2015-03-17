---
title: Sirocco: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Sirocco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/sirocco:Sirocco

---

Copyright Section
-----

![Copyright](assets/demo_13.jpeg)

:   1. **Gantry Copyright** [30%, 5%, se]
    2. **Gantry Menu** [30%, 65%, se]

Here is the widget breakdown for the Footer section:

* Gantry Copyright
* Gantry Divider
* Gantry Menu

#### Gantry Copyright

The Gantry Copyright widget places a tiny Copyright notification at the bottom of the page. The only thing you need to change in this widget to match the demo is the text field, which includes: `&copy; %YEAR%. Sirocco. Powered by RocketTheme.`.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu

The **Custom Menu** widget allows us to add an extra menu somewhere on the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

| Option            | Setting                                                 |
| :---------------- | :------------------------------------------------------ |
| Select Menu       | (Choose the menu you wish to have appear in the widget) |
| Widget Variations | RT-Center                                               |
| Custom Variations | `rt-horizmenu hidden-phone wow fadeInUp`                |

Leaving all other options at their default settings, click **Save**.
