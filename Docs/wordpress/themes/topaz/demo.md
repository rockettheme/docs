---
title: Topaz: Recreating the Demo
description: Your Guide to Recreating Elements of the Topaz Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/topaz:Topaz

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Topaz can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Topaz Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/topaz2.png)

:   1. **Navigation Left** Social (Particle) [2%, 5%, se]
    2. **Navigation Main** Logo (Particle) [2%, 18%, se]
    3. **Navigation Main** Menu (Particle) [2%, 45%, se]
    4. **Navigation Right** Search (Widget) [2%, 76%, se]
    5. **Header Main** WordPress Articles (Particle) [6%, 15%, se]
    6. **Header Main** Owl Carousel (Particle) [6%, 60% se]
    8. **Showcase Main** Grid Statistic (Particle) [23%, 15%, se]
    8. **Showcase Main** Custom HTML (Particle) [33%, 15%, se]
    9. **Showcase Main** WordPress Articles (Particle) [23%, 38%, se]
    10. **Slideshow Main** Owl Carousel (Particle) [42%, 15%, se]
    11. **Feature Main** BookBlock (Particle) [55%, 15%, se]
    12. **Bottom Main** Owl Carousel (Particle) [73%, 15%, se]
    13. **Bottom Main** Owl Carousel (Particle) [86%, 38%, se]
    14. **Footer Main** Simple Menu (Particle) [92%, 15%, se]
    15. **Footer Main** Social (Particle) [92%, 73%, se]
    16. **Copyright Main** Logo (Particle) [96%, 15%, se]
    17. **Copyright Main** Custom HTML (Particle) [96%, 27%, se]
    18. **Copyright Main** Copyright (Particle) [99%, 27%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Topaz, as well as links to documentation to help you get started:

* Theme Particles
    * [Owl Carousel](particle_owl.md)
    * [BookBlock](particle_book.md)
    * [WordPress Articles](particle_wordpress.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Grid Statistic](particle_grid.md)
    * [Simple Content](particle_simple.md)
    * [Image Grid](particle_image.md)
* Core Particles 
    * [Logo](http://docs.gantry.org/gantry5/particles/logo)
    * [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    * [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    * [Socail](http://docs.gantry.org/gantry5/particles/social)
    * [Widget Positions](http://docs.gantry.org/gantry5/particles/position)
    * [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    * [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    * [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    * [Widget Instance](http://docs.gantry.org/gantry5/particles/widget-instance)
    * [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    * [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Socail](http://docs.gantry.org/gantry5/particles/social)
* [Widget Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Widget Instance](http://docs.gantry.org/gantry5/particles/widget-instance)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Interstellar:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokBox](http://www.rockettheme.com/wordpress/plugins/rokbox)

Many of these plugins are included with the Interstellar RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Interstellar demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Interstellar demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpg)

In order to make it really easy to replicate the home page, we included a layout preset for the home page with the theme. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout. If you downloaded the theme and not a RocketLauncher, this is the best option for you if you want a copy of the front page with minimal effort.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.png)

Interstellar has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Interstellar > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Interstellar** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.