---
title: Photon: Recreating the Demo
description: Your Guide to Recreating Elements of the Photon Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/photon:Photon

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Photon can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Galatea Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/photon2.jpeg)

:   1. **Navigation** Logo / Image (Particle) [1%, 8%, se]
    2. **Navigation** Menu (Particle) [1%, 25%, se]
    3. **Navigation** Social (Particle) [1%, 85%, se]
    4. **Slideshow** News Slider (Particle) [5%, 8%, se]
    5. **Header** Image Grid (Particle) [25%, 8%, se]
    6. **Header** Pricing Table (Particle) [25%, 65% se]
    8. **Showcase** Accordion (Particle) [38%, 8%, se]
    8. **Showcase** Custom HTML (Particle) [38%, 65%, se]
    9. **Showcase** Grid Content (Particle) [44%, 65%, se]
    10. **Expanded** Content Tabs (Particle) [59%, 8%, se]
    11. **Expanded** Owl Carousel (Particle) [59%, 65%, se]
    12. **Expanded** Simple Content (Particle) [70%, 66%, se]
    13. **Widget** Owl Carousel (Particle) [81%, 8%, se]
    14. **Copyright** Logo / Image (Particle) [93%, 8%, se]
    15. **Copyright** Newsletter (Particle) [93%, 60%, se]
    16. **Copyright** Copyright (Particle) [96%, 8%, se]
    17. **Copyright** Custom HTML (Particle) [96%, 60%, se]


We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Slideshow](demo_slideshow.md)
3. [Header](demo_header.md)
4. [Showcase](demo_showcase.md)
5. [Expanded](demo_expanded.md)
6. [Widget](demo_widget.md)
7. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Widgets
-----

Here is a list of RocketTheme widgets used to create the demo version of Photon:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/wordpress/widgets/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/wordpress/widgets/rokbox)

Many of these widgets are included with the Photon RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Photon demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Photon demo.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting outline. This can be done by navigating to **Admin -> Photon Theme -> Outlines** and selecting the **+** icon.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an outline, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Photon - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.png)

Photon has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Photon Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Admin. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Photon Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, we used the **Front Page** page, which is a blank page we created.
