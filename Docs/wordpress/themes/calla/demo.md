---
title: Calla: Recreating the Demo
description: Your Guide to Recreating Elements of the Calla Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/calla:Calla

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Calla can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Calla Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/calla2.png)

:   1. **Slideshow** Vertical Menu (Particle) [1%, 3%, se]
    2. **Slideshow** Carousel (Particle) [1%, 24%, se]
    3. **Header** Heading (Particle) [20%, 3%, se]
    4. **Header** Slider (Particle) [24%, 3%, se]
    5. **Above** Promo (Particle) [32%, 3%, se]
    6. **Above** Logo/Image (Particle) [32%, 28%, se]
    7. **Above** Platform Content (Particle) [32%, 43%, se]
    8. **Feature** Slideshow (Particle) [45%, 5%, se]
    9. **Showcase** Case Studies (Particle) [59%, 11%, se]
    10. **Extension** Springboard (Particle) [76%, 11%, se]
    11. **Extension** Logo/Image (Particle) [76%, 76%, se]
    12. **Footer** Bottom Menu (Particle) [91%, 11%, se]
    13. **Footer** Newsletter (Particle) [91%, 49%, se]
    14. **Footer** Branding (Particle) [99%, 37%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Calla, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Calla Theme > Home > Layout.

Theme Particles

* [Block Content](particle_block.md)
+ [Carousel](particle_carousel.md)
+ [Case Studies](particle_case.md)
+ [Grid Statistic](particle_grid.md)
+ [Heading](particle_heading.md)
+ [Image Grid](particle_image.md)
+ [Info List](particle_info.md)
+ [WordPress Posts](particle_wordpress.md)
+ [Pricing Table](particle_pricing.md)
+ [Promo](particle_promo.md)
+ [Simple Content](particle_simple.md)
+ [Simple Counter](particle_simplecounter.md)
+ [Slider](particle_slider.md)
+ [Slideshow](particle_slideshow.md)
+ [Social](particle_social.md)
+ [Springboard](particle_springboard.md)
+ [Video](particle_video.md)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Social](http://docs.gantry.org/gantry5/particles/social)
* [Widget Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Widget Instance](http://docs.gantry.org/gantry5/particles/module-instance)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Calla:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Calla RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Calla demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Calla demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

While the **Home - Particles** layout is automatically loaded after installing the Calla theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)


Calla has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Calla Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Calla Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.