---
title: Callisto: Recreating the Demo
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Callisto can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Callisto Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/callisto2.jpeg)

:   1. **Header - Logo** [5%, 12%, se]
    2. **Header - Icon Menu** [5%, 55%, se]
    3. **Navigation - Menu** [8%, 12%, se]
    4. **Navigation - Social** [9%, 80%, se]
    5. **Showcase - Widget Position (showcase)** [12%, 13%, se]
    6. **Mainfeature - Content List** [25%, 12%, se]
    7. **Sidefeature - Widget Position (sidefeature-a)** [25%, 65%, se]
    8. **Sidefeature - Widget Position (sidefeature-b)** [30%, 65%, se]
    9. **Main - Content List** [42%, 12%, se]
    10. **Main - Custom HTML** [42%, 63%, se]
    11. **Extension - Widget Position (extension-a)** [51%, 12%, se]
    12. **Extension - Widget Position (extension-b)** [55%, 12%, se]
    13. **Extension - Promo Image** [70%, 12%, se]
    14. **Extension - Widget Position (extension-c)** [70%, 38%, se]
    15. **Extension - Image Grid** [70%, 65%, se]
    16. **Footer - Info List** [80%, 12%, se]
    17. **Footer - Custom HTML** [80%, 38%, se]
    18. **Footer - Contact** [80%, 63%, se]
    19. **Copyright - Copyright** [91%, 38%, se]

We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Header](demo_header.md)
2. [Navigation](demo_navigation.md)
3. [Showcase](demo_showcase.md)
4. [Mainfeature](demo_mainfeature.md)
5. [Sidefeature](demo_sidefeature.md)
6. [Main](demo_main.md)
7. [Extension](demo_extension.md)
8. [Footer](demo_footer.md)
9. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Callisto:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/wordpress/plugins/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/wordpress/plugins/rokbox)
* [RokSprocket](http://www.rockettheme.com/wordpress/plugins/roksprocket)

Several of these plugins may be included with the Callisto RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Callisto demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Callisto demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a **Home outline** which is commonly referred to in WordPress as a **Style Override**. This can be done by navigating to **Admin > Callisto Theme** and finding the theme you wish to create a new outline based in. Once you have done this, you can select the blue **Configure** button and the navigate to **outlines**. This page gives you a quick overview of any configurations for this theme.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an override, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Callisto - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.jpeg)

Callisto has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any chances made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Callisto Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Callisto Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
