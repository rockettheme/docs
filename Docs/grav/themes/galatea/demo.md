---
title: Galatea: Recreating the Demo
description: Your Guide to Recreating Elements of the Galatea Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/galatea:Galatea

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Galatea can be done fairly easily. All you need are the right particles and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Galatea Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/galatea2.jpeg)

:   1. **Navigation** OffSidebar Toggle (Particle) [1%, 5%, se]
    2. **Navigation** Logo / Image (Particle) [1%, 40%, se]
    3. **Navigation** Social (Particle) [1%, 85%, se]
    4. **Slideshow** Owl Carousel (Particle) [5%, 7%, se]
    5. **Header** Mosaic Grid (Particle) [10%, 7%, se]
    6. **Showcase** Custom HTML (Particle) [42%, 7% se]
    7. **Showcase** Logo / Image (Particle) [42%, 50%, se]
    8. **Utility** Block Content  (Particle) [53%, 7%, se]
    9. **Feature** Pricing Table (Particle) [65%, 7%, se]
    10. **Bottom** Info List (Particle) [85%, 7%, se]
    11. **Bottom** Info List (Particle) [85%, 33%, se]
    12. **Bottom** Custom HTML (Particle) [85%, 65%, se]
    13. **Footer** Newsletter (Particle) [95%, 35%, se]
    14. **Copyright** Branding (Particle) [99%, 7%, se]
    15. **Copyright** Copyright (Particle) [99%, 33%, se]
    16. **Copyright** To Top (Particle) [99%, 90%, se]

We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Slideshow](demo_slideshow.md)
3. [Header](demo_header.md)
3. [Showcase](demo_showcase.md)
4. [Utility](demo_utility.md)
5. [Feature](demo_feature.md)
6. [Bottom](demo_bottom.md)
7. [Footer](demo_footer.md)
8. [Copyright](demo_copyright.md)
9. [Swiper](particle_swiper.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

![](assets/offsidebar.jpeg)

There is also an **Offsidebar** position which contains the **Menu** particle. You can find a breakdown of this position [here](demo_offsidebar.md).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Galatea:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Galatea RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Galatea demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Galatea demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Galatea has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
