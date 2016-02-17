---
title: Antares: Recreating the Demo
description: Your Guide to Recreating Elements of the Antares Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/antares:Antares

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Antares can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Antares Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/antares2.png)

:   1. **Navigation** Logo (Particle) [1%, 5%, se]
    2. **Navigation** Menu (Particle) [1%, 30%, se]
    3. **Slideshow** FlexSlider (Particle) [3%, 7%, se]
    4. **Above** Grid Promo Gallery (Particle) [23%, 7%, se]
    5. **Above** Grid Promo Gallery (Particle) [23%, 53% se]
    6. **Above** Grid Promo Gallery (Particle) [28%, 7%, se]
    7. **Above** Grid Promo Gallery (Particle) [28%, 53%, se]
    8. **Showcase** Promo Content (Particle) [35%, 7%, se]
    9. **Showcase** Content Tabs (Particle) [42%, 7%, se]
    10. **Utility** Promo Content (Particle) [49%, 7%, se]
    11. **Utility** Block Content (Particle) [53%, 7%, se]
    12. **Utility** Animated Block (Particle) [58%, 7%, se]
    13. **Feature** Promo Content (Particle) [65%, 7%, se]
    14. **Feature** Block Content (Particle) [68%, 7%, se]
    15. **Expanded** Block Content (Particle) [72%, 7%, se]
    16. **Extension** Block Content (Particle) [80%, 7%, se]
    17. **Extension** Promo Content (Particle) [80%, 52%, se]
    18. **Bottom** Newsletter (Particle) [90%, 25%, se]
    19. **Footer** Logo (Particle) [95%, 7%, se]
    20. **Footer** HorizontalMenu (Particle) [95%, 40%, se]
    21. **Footer** Social (Particle) [95%, 75%, se]
    22. **Copyright** Copyright (Particle) [97%, 7%, se]
    23. **Copyright** Horizontal Menu (Particle) [97%, 70%, se]
    23. **Copyright** To Top (Particle) [99%, 40%, se]

We have detailed how to recreate the individual modules and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Slideshow](demo_slideshow.md)
3. [Above](demo_above.md)
4. [Header](demo_header.md)
4. [Showcase](demo_showcase.md)
5. [Utility](demo_utility.md)
6. [Feature](demo_feature.md)
7. [Expanded](demo_expanded.md)
8. [Extension](demo_extension.md)
9. [Bottom](demo_bottom.md)
10. [Footer](demo_footer.md)
11. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

![FixedSide](fixedside.png)

There is also an **FixedSide** position which contains the **FixedSide Social Icons** particle. You can find a breakdown of this position [here](demo_fixedside.md).

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Antares:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/joomla/extensions/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket](http://www.rockettheme.com/joomla/extensions/roksprocket)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Antares RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Antares demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Antares demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.png)

In order to make it really easy to replicate the home page, we included two layout presets for the home page with the theme. The first, **Home - Particles** includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout. If you downloaded the theme and not a RocketLauncher, this is the best option for you if you want a copy of the front page with minimal effort.

The other preset is called **Home - Positions** and this is used in our demo by default in the RocketLauncher. This option creates module positions which give you a little more flexibility to swap out demo particles with standard Joomla modules. Keep in mind that this Layout Preset will not fill in the **Gantry 5 Particle** modules, only the module positions we used in the layout for the demo. We've included this documentation to help you recreate specific elements if you opt to go with this layout preset on an existing site.

You can access the presets by selecting **Load** in the **Layout Manager**.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a **Home outline** which is commonly referred to in Joomla as a **Style Override**. This can be done by navigating to **Components > Gantry 5 Themes** and finding the theme you wish to create a new outline based in. Once you have done this, you can select the blue **Configure** button and then navigate to **Outlines**. This page gives you a quick overview of any configurations for this theme.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an override, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Antares - Home** as it would be used only for the front page of your site. In our own Demo and in the RocketLauncher we have named this Style **Antares - Demo** instead of **Antares - Home**.

Menu Editor
-----

![](assets/menu_1.png)

Antares has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Antares > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Antares** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
