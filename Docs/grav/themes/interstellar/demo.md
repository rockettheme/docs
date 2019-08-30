---
title: Interstellar: Recreating the Demo
description: Your Guide to Recreating Elements of the Interstellar Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/interstellar:Interstellar

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Interstellar can be done fairly easily. All you settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Interstellar Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Here is a list of particles that are available in Interstellar, as well as links to documentation to help you get started:

![](assets/interstellar2.jpeg)

:   1. **Navigation** Logo (Particle) [1%, 7%, se]
    2. **Navigation** Social (Particle) [1%, 18%, se]
    3. **Navigation** Menu (Particle) [1%, 55%, se]
    4. **Header** Custom HTML (Particle) [5%, 8%, se]
    5. **Header** Custom HTML (Particle) [5%, 68%, se]
    6. **Slideshow** Owl Carousel (Particle) [11%, 5% se]
    8. **Above** Simple Content (Particle) [30%, 43%, se]
    8. **Above** Simple Content (Particle) [30%, 68%, se]
    9. **Feature** Owl Carousel (Particle) [40%, 5%, se]
    10. **Expanded** Simple Content (Particle) [52%, 5%, se]
    11. **Expanded** Image Grid (Particle) [52%, 42%, se]
    12. **Extension** Simple Content (Particle) [65%, 40%, se]
    13. **Extension** Block Content (Particle) [68%, 8%, se]
    14. **Bottom** Pricing Table (Particle) [80%, 8%, se]
    15. **Footer** Custom HTML (Particle) [93%, 5%, se]
    16. **Footer** Newsletter (Particle) [93%, 60%, se]
    17. **Copyright** Copyright (Particle) [99%, 5%, se]


We have detailed how to recreate the individual particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Header](demo_header.md)
3. [Slideshow](demo_slideshow.md)
4. [Above](demo_above.md)
5. [Feature](demo_feature.md)
6. [Expanded](demo_expanded.md)
7. [Extension](demo_extension.md)
8. [Bottom](demo_bottom.md)
9. [Footer](demo_footer.md)
10. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Interstellar:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Interstellar RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Interstellar demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Interstellar demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Interstellar has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
