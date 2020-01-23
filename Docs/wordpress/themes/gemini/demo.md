---
title: Gemini: Recreating the Demo
description: Your Guide to Recreating Elements of the Gemini Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/gemini:Gemini

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Versla can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Versla Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particles as they appear on the front page of our demo. These can all be found and edited via Versla Theme > Home > Layout.

![](assets/gemini2.jpeg)

:   1. **Navigation** Logo (Particle) [1%, 13%, se]
    2. **Navigation** Menu (Particle) [1%, 47%, se]
    3. **Navigation** Overlay Toggle (Particle) [1%, 83%, se]
    4. **Slideshow** Custom HTML (Particle) [14%, 13%, se]
    5. **Slideshow** Block Content (Particle) [14%, 60%, se]
    6. **Header** Simple Content (Particle) [25%, 15% se]
    7. **Header** Header Tabs (Particle) [31%, 15%, se]
    8. **Header** Accordion Slider (Particle) [31%, 55%, se]
    9. **Utility** Simple Content (Particle) [45%, 35%, se]
    10. **Utility** Newsletter (Particle) [53%, 35%, se]
    11. **Feature** Simple Content (Particle) [60%, 35%, se]
    12. **Feature** Content Tabs (Particle) [65%, 13%, se]
    13. **Expanded** Simple Content (Particle) [80%, 20%, se]
    14. **Expanded** Accordion (Particle) [84%, 13%, se]
    15. **Expanded** Accordion (Particle) [84%, 50%, se]
    16. **Expanded** Custom HTML (Particle) [87%, 40%, se]
    17. **Footer** Logo (Particle) [92%, 10%, se]
    18. **Footer** Custom HTML (Particle) [92%, 40%, se]
    19. **Footer** Custom HTML (Particle) [92%, 65%, se]
    20. **Footer** Custom HTML (Particle) [94%, 10%, se]
    21. **Footer** Custom HTML (Particle) [94%, 40%, se]
    22. **Footer** Custom HTML (Particle) [94%, 65%, se]
    23. **Copyright** Branding (Particle) [98%, 10%, se]
    24. **Copyright** Simple Menu (Particle) [98%, 40%, se]
    25. **Copyright** ToTop (Particle) [98%, 85%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

![](assets/gemini3.jpeg)

The **Overlay Sidebar** and **Overlay Main** sections are also available. They are accessible from the menu icon in the upper-right corner of the demo site, giving you a beautiful place to put additional information and links for your visitors.

Particles
-----

Here is a list of particles that are available in Gemini, as well as links to documentation to help you get started:

* Theme Particles
    - [Accordion](particle_accordion.md)
    - [Accordion Menu](particle_accordionmenu.md)
    - [Accordion Slider](particle_accordionslider.md)
    - [Block Content](particle_block.md)
    - [Content Tabs](particle_tabs.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grid Statistic](particle_grid.md)
    - [Header Tabs](particle_headertabs.md)
    - [Image Grid](particle_image.md)
    - [Newsletter](particle_newsletter.md)
    - [Overlay Toggle](particle_overlay.md)
    - [Pricing Table](particle_pricing.md)
    - [Simple Content](particle_simple.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Simple Menu](particle_simplemenu.md)
    - [Video](particle_video.md)
* Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Module Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Gemini:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Gemini RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Gemini demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Gemini demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

While the **Home - Particles** layout is automatically loaded after installing the Gemini theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Gemini has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gemini Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gemini Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.