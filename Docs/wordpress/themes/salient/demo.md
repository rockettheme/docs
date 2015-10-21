---
title: Salient: Recreating the Demo
description: Your Guide to Recreating Elements of the Salient Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/salient:Salient

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Salient can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Salient Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/salient2.png)

:   1. **Logo (Particle)** [1%, 3%, se]
    2. **Menu (Particle)** [1%, 23%, se]
    3. **Custom HTML** [1%, 72%, se]
    4. **Social (Particle)** [1%, 83%, se]
    5. **Promo Content (Particle)** [4%, 4%, se]
    6. **Animated Block (Particle)** [8%, 3%, se]
    7. **Animated Block (Particle)** [14%, 3%, se]
    8. **Animated Block (Particle)** [8%, 28%, se]
    9. **Custom HTML (Widget)** [8%, 72%, se]
    10. **Animated Block (Particle)** [10%, 72%, se]
    11. **Animated Block (Particle)** [14%, 72%, se]
    12. **Promo Content (Particle)** [22%, 5%, se]
    13. **Block Content (Particle)** [25%, 5%, se]
    14. **Promo Content (Particle)** [30%, 50%, se]
    15. **Promo Content (Particle)** [40%, 50%, se]
    16. **Block Content (Particle)** [52%, 5%, se]
    17. **Promo Content (Particle)** [62%, 5%, se]
    18. **Promo Content (Particle)** [70%, 7%, se]
    19. **Promo Content (Particle)** [70%, 45%, se]
    20. **Promo Content (Particle)** [82%, 5%, se]
    21. **Contact (Particle)** [89%, 5%, se]
    22. **Promo Content (Particle)** [89%, 50%, se]
    23. **Contact (Particle)** [93%, 50%, se]
    24. **Contact (Particle)** [93%, 68%, se]
    25. **Logo (Particle)** [99%, 5%, se]
    26. **To Top (Particle)** [99%, 40%, se]
    27. **Social (Particle)** [99%, 70%, se]

We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Navigation](demo_navigation.md)
2. [Header](demo_header.md)
3. [SlideLeft, SlideCenter, and SlideRight](demo_slideshow.md)
4. [Showcase](demo_showcase.md)
5. [Utility](demo_utility.md)
6. [Feature](demo_feature.md)
7. [Mainbar](demo_mainbar.md)
8. [Expanded](demo_expanded.md)
9. [Plugin](demo_plugin.md)
10. [Bottom](demo_bottom.md)
11. [Footer / Footside](demo_footer.md)
12. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Ambrosia:

* [Gantry Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/wordpress/plugins/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/wordpress/plugins/rokbox)
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket](http://www.rockettheme.com/wordpress/plugins/roksprocket)
* [RokBooster](http://www.rockettheme.com/wordpress/plugins/rokbooster)

Many of these plugins are included with the Salient RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Salient demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Salient demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a **Home outline** which is commonly referred to in WordPress as a **Style Override**. This can be done by navigating to **Components > Gantry 5 Themes** and finding the theme you wish to create a new outline based in. Once you have done this, you can select the blue **Configure** button and then navigate to **Outlines**. This page gives you a quick overview of any configurations for this theme.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an override, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.png)

Salient has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Salient Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Admin. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Salient Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, we used the **Front Page** page, which is a blank page we created.