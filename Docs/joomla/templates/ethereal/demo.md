---
title: Ethereal: Recreating the Demo
description: Your Guide to Recreating Elements of the Ethereal Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ethereal:Ethereal

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Ethereal can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Ethereal Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

>> NOTE: In Ethereal, we have two versions of the front page. One is comprised of Gantry 5 particles, and the other utilizes the popular RokSprocket extension to offer an alternative to particles for users that are more familiar with RokSprocket. You will find documentation for both styles of the items on their section guides linked below the image.

![](assets/ethereal2.jpeg)

:   1. **Header - Logo** [5%, 19%, se]
    2. **Header - Menu** [5%, 37%, se]
    3. **Slideshow - Slideshow (Particle) / RokSprocket (Features)** [10%, 19%, se]
    4. **Feature - Custom (Particle)** [14%, 50%, se]
    5. **Feature - Swiper (Particle) / RokSprocket (Features)** [16%, 20%, se]
    6. **Feature - Blog Content (Particle)** [16%, 62%, se]
    7. **Main - Image Block (Particle)** [28%, 19%, se]
    8. **Main - Custom HTML (Particle)** [40%, 19%, se]
    9. **Main - Number Headline (Particle)** [44%, 19%, se]
    10. **Main - Ethereal Block (Particle)** [53%, 19%, se]
    11. **Extension - Custom HTML (Particle)** [67%, 19%, se]
    12. **Extension - Icon Headline (Particle) / RokSprocket (Strips)** [70%, 19%, se]
    13. **Bottom - Custom HTML (Particle)** [79%, 45%, se]
    14. **Bottom - Image Overlay (Particle)** [81%, 19%, se]
    15. **Bottom - Blog Content (Particle)** [81%, 40%, se]
    16. **Copyright - Logo (Particle)** [88%, 19%, se]
    17. **Copyright - Custom HTML (Particle)** [88%, 40%, se]
    18. **Copyright - Copyright (Particle)** [92%, 19%, se]
    19. **Copyright - Horizontal Menu (Particle)** [92%, 40%, se]
    20. **Copyright - To Top (Particle)** [92%, 80%, se]

We have detailed how to recreate the individual modules and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Top](demo_top.md)
2. [Header](demo_header.md)
3. [Slideshow](demo_slideshow.md)
4. [Feature](demo_feature.md)
5. [Main](demo_main.md)
6. [Extension](demo_extension.md)
7. [Bottom](demo_bottom.md)
8. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Ethereal:

* [Gantry Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/joomla/extensions/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket](http://www.rockettheme.com/joomla/extensions/roksprocket)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Ethereal RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Ethereal demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Ethereal demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a **Home outline** which is commonly referred to in Joomla as a **Style Override**. This can be done by navigating to **Components > Gantry 5 Themes** and finding the theme you wish to create a new outline based in. Once you have done this, you can select the blue **Configure** button and the navigate to **outlines**. This page gives you a quick overview of any configurations for this theme.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an override, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Ethereal - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.jpeg)

Ethereal has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Gantry 5 > Ethereal > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Gantry 5 > Ethereal** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.

>> NOTE: There are two versions of the home page in our demo. This is to allow our users to easily choose between starting with a home page built entirely with Gantry 5 particles, or with the popular RokSprocket modules many of them are used to. You will notice that the `Ethereal - RokSprocket` outline is assigned to the `RokSprocket` menu item in the Assignments panel.
