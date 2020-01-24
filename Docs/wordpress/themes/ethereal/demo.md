---
title: Ethereal: Recreating the Demo
description: Your Guide to Recreating Elements of the Ethereal Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ethereal:Ethereal

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Ethereal can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Ethereal Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

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
    11. **Plugin - Custom HTML (Particle)** [67%, 19%, se]
    12. **Plugin - Icon Headline (Particle) / RokSprocket (Strips)** [70%, 19%, se]
    13. **Bottom - Custom HTML (Particle)** [79%, 45%, se]
    14. **Bottom - Image Overlay (Particle)** [81%, 19%, se]
    15. **Bottom - Blog Content (Particle)** [81%, 40%, se]
    16. **Copyright - Logo (Particle)** [88%, 19%, se]
    17. **Copyright - Custom HTML (Particle)** [88%, 40%, se]
    18. **Copyright - Copyright (Particle)** [92%, 19%, se]
    19. **Copyright - Horizontal Menu (Particle)** [92%, 40%, se]
    20. **Copyright - To Top (Particle)** [92%, 80%, se]

We have detailed how to recreate the individual widgets and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Top](demo_top.md)
2. [Header](demo_header.md)
3. [Slideshow](demo_slideshow.md)
4. [Feature](demo_feature.md)
5. [Main](demo_main.md)
6. [Plugin](demo_plugin.md)
7. [Bottom](demo_bottom.md)
8. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

### Theme Particles

+ [Blog Content](particle_blogcontent.md)
+ [Contact](particle_contact.md)
+ [Content List](particle_contentlist.md)
+ [Ethereal Block](particle_block.md)
+ [WordPress Content](particle_wordpress.md)
+ [Icon Headline](particle_iconheadline.md)
+ [Image Block](particle_imageblock.md)
+ [Image Grid](particle_image.md)
+ [Image Overlay](particle_imageoverlay.md)
+ [Info List](particle_info.md)
+ [Newsletter](particle_newsletter.md)
+ [Number Headline](particle_numberheadline.md)
+ [Promo Image](particle_promoimage.md)
+ [Simple Counter](particle_simplecounter.md)
+ [Slideshow](particle_slideshow.md)
+ [Swiper](particle_swiper.md)

### Core Particles 

+ [Logo](http://docs.gantry.org/gantry5/particles/logo)
+ [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
+ [To Top](http://docs.gantry.org/gantry5/particles/to-top)
+ [Social](http://docs.gantry.org/gantry5/particles/social)
+ [Positions](http://docs.gantry.org/gantry5/particles/position)
+ [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
+ [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
+ [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
+ [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
+ [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins we recommend using with Ethereal:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Ethereal RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Ethereal demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Ethereal demo.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting outline. This can be done by navigating to **Admin -> Ethereal Theme -> Outlines** and selecting the **+** icon.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an outline, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Ethereal - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.jpeg)

Ethereal has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Ethereal Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Admin. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Ethereal Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, we used the **Front Page** page, which is a blank page we created.
