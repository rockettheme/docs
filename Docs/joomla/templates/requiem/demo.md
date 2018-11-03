---
title: Requiem: Recreating the Demo
description: Your Guide to Recreating Elements of the Requiem Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/requiem:Requiem

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Requiem can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Requiem Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/requiem2.png)

:   1. **Navigation** MainNav Left - Icon Menu (Particle) [1%, 13%, se]
    2. **Navigation** Menu (Particle) [1%, 38%, se]
    3. **Navigation** MainNav Right - Icon Menu (Particle) [1%, 83%, se]
    4. **Header** Promo Content (Particle) [4%, 25%, se]
    5. **Showcase** Grid Statistic (Particle) [18%, 20%, se]
    6. **Above** Promo Content (Particle) [23%, 20%, se]
    7. **Utility** Animated Block (Particle) [28%, 12%, se]
    8. **Feature** Testimonial (Particle) [44%, 12%, se]
    9. **Expanded** Info List (Particle) [54%, 13%, se]
    10. **Expanded** Grid Promo (Particle) [54%, 45%, se]
    11. **Extension** Promo Content (Particle) [67%, 13%, se]
    12. **Bottom** Grid Content (particle) [80%, 13%, se]
    13. **Footer** Info List (Particle) [91%, 13%, se]
    14. **Footer** Info List (Particle) [91%, 32%, se]
    15. **Footer** Custom HTML (Module) [91%, 50%, se]
    16. **Footer** Contact (Particle) [91%, 70%, se]
    17. **Copyright** Branding (Particle) [99%, 13%, se]
    18. **Copyright** Copyright (Particle) [99%, 40%, se]
    19. **Copyright** To Top (Particle) [99%, 85%, se]

We have detailed how to recreate the individual modules and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Header](demo_header.md)
4. [Showcase](demo_showcase.md)
5. [Above](demo_above.md)
5. [Utility](demo_utility.md)
6. [Feature](demo_feature.md)
7. [Expanded](demo_expanded.md)
8. [Extension](demo_extension.md)
9. [Bottom](demo_bottom.md)
10. [Footer](demo_footer.md)
11. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

There is also a **FixedSide** position which contains a smaller version of the logo as well as social icons which are fixed and scroll down the page with you. This section is covered in detail [here](demo_fixedside.md).

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Requiem:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/joomla/extensions/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket](http://www.rockettheme.com/joomla/extensions/roksprocket)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Requiem RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Requiem demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Requiem demo.

Menu Editor
-----

![](assets/menu_1.png)

Requiem has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Requiem > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Requiem** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
