---
title: Xenon: Recreating the Demo
description: Your Guide to Recreating Elements of the Xenon Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/xenon:Xenon

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Xenon can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Xenon Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/xenon2.jpeg)

:   1. **Top** Logo (Particle) [1%, 5%, se]
    2. **Top** Overlay Toggle (Particle) [1%, 62%, se]
    3. **Top** Social (Particle) [1%, 85%, se]
    4. **Navigation** Menu (Particle) [3%, 7%, se]
    5. **Navigation** Popup Widget (Particle) [3%, 85% se]
    6. **Header** FlexSlider (Particle) [7%, 25%, se]
    7. **Above** News Ticker (Particle) [13%, 7%, se]
    8. **Showcase** Popup Grid (Particle) [15%, 7%, se]
    9. **Utility** FlexSlider (Particle) [46%, 7%, se]
    10. **Feature** Image Grid (Particle) [54%, 7%, se]
    11. **Expanded** News Slider (Particle) [69%, 7%, se]
    12. **Extension** Chartist (Particle) [80%, 7%, se]
    13. **Extension** Chartist (Particle) [80%, 40%, se]
    14. **Extension** Chartist (Particle) [80%, 68%, se]
    15. **Bottom** Testimonial (Particle) [88%, 7%, se]
    16. **Bottom** Promo Content (Particle) [93%, 7%, se]
    17. **Footer** Info List (Particle) [95%, 7%, se]
    18. **Footer** Info List (Particle) [95%, 25%, se]
    19. **Footer** Custom HTML (Particle) [95%, 50%, se]
    20. **Footer** Newsletter (Particle) [95%, 75%, se]
    21. **Copyright** Branding (Particle) [99%, 7%, se]
    22. **Copyright** Copyright (Particle) [99%, 35%, se]
    23. **Copyright** To Top (Particle) [99%, 85%, se]

We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Top](demo_top.md)
2. [Navigation](demo_navigation.md)
3. [Header](demo_header.md)
4. [Above](demo_above.md)
5. [Showcase](demo_showcase.md)
6. [Utility](demo_utility.md)
7. [Feature](demo_feature.md)
8. [Expanded](demo_expanded.md)
9. [Extension](demo_extension.md)
10. [Bottom](demo_bottom.md)
11. [Footer](demo_footer.md)
12. [Copyright](demo_copyright.md)
13. [Overlay](demo_overlay.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Xenon:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Xenon RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Xenon demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Xenon demo.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting outline. This can be done by navigating to **Admin -> Xenon Theme -> Outlines** and selecting the **+** icon.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an outline, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Xenon - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.jpeg)

Xenon has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Xenon Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Admin. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Xenon Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, we used the **Front Page** page, which is a blank page we created.
