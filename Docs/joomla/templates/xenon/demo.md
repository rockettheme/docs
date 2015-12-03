---
title: Xenon: Recreating the Demo
description: Your Guide to Recreating Elements of the Xenon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/xenon:Xenon

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Xenon can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Xenon Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/xenon2.jpeg)

:   1. **Top** Logo (Particle) [1%, 3%, se]
    2. **Top** Overlay Toggle (Particle) [1%, 85%, se]
    3. **Top** Social (Particle) [5%, 5%, se]
    4. **Navigation** Menu (Particle) [13%, 5%, se]
    5. **Navigation** Popup Module (Particle) [21%, 40% se]
    6. **Header** FlexSlider (Particle) [25%, 5%, se]
    7. **Above** News Ticker (Particle) [40%, 5%, se]
    8. **Showcase** Popup Grid (Particle) [50%, 5%, se]
    9. **Utility** FlexSlider (Particle) [60%, 5%, se]
    10. **Feature** Image Grid (Particle) [75%, 5%, se]
    11. **Expanded** News Slider (Particle) [85%, 5%, se]
    12. **Extension** Chartist (Particle) [93%, 5%, se]
    13. **Extension** Chartist (Particle) [93%, 25%, se]
    14. **Extension** Chartist (Particle) [93%, 50%, se]
    15. **Bottom** Testimonial (Particle) [93%, 75%, se]
    16. **Bottom** Promo Content (Particle) [99%, 5%, se]
    17. **Footer** Info List (Particle) [99%, 45%, se]
    18. **Footer** Info List (Particle) [99%, 95%, se]
    19. **Footer** Custom HTML (Particle) [95%, 5%, se]
    20. **Footer** Newsletter (Particle) [95%, 15%, se]
    21. **Copyright** Branding (Particle) [95%, 15%, se]
    22. **Copyright** Copyright (Particle) [95%, 15%, se]
    23. **Copyright** To Top (Particle) [95%, 15%, se]

We have detailed how to recreate the individual modules and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

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

![Overlay](overlay.jpeg)

There is also an **Overlay** position which appears when activated via the **Overlay Toggle** particle. We have detailed this part of our demo [here](demo_overlay.md).

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Xenon:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/joomla/extensions/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket](http://www.rockettheme.com/joomla/extensions/roksprocket)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Xenon RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Xenon demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Xenon demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a **Home outline** which is commonly referred to in Joomla as a **Style Override**. This can be done by navigating to **Components > Gantry 5 Themes** and finding the theme you wish to create a new outline based in. Once you have done this, you can select the blue **Configure** button and then navigate to **Outlines**. This page gives you a quick overview of any configurations for this theme.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an override, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Xenon - Home** as it would be used only for the front page of your site. In our own Demo and in the RocketLauncher we have named this Style **Xenon - Demo** instead of **Xenon - Home**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Xenon has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Xenon > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Xenon** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
