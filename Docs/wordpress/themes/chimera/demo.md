---
title: Chimera: Recreating the Demo
description: Your Guide to Recreating Elements of the Chimera Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Chimera can be done fairly easily. All you need is the right particles and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Chimera Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/chimera2.png)

:   1. **Navigation** Logo (Particle) [1%, 7%, se]
    2. **Navigation** Menu (Particle) [1%, 62%, se]
    3. **Slideshow** Slideshow (Particle) [6%, 50%, se]
    4. **Feature** Custom HTML (Particle) [20%, 50%, se]   
    5. **Utility** Icon List (Particle) [25%, 7%, se]
    6. **Utility** Custom HTML (Particle) [25%, 65%, se]
    7. **Expandedtop** Content Tabs (Particle) [37%, 6%, se]
    8. **Expandedtop** Progress Bar (Particle) [37%, 64%, se]
    9. **Maintop** Custom HTML (Particle) [46%, 50%, se]
    10. **Mainbottom** Strips Slider (Particle) [51%, 50%, se]
    11. **FullWidth** Slider (Particle) [64%, 50%, se]
    12. **Extension** Pricing Table  (Particle) [74%, 9%, se]
    13. **Extension** Custom (Particle) [74%, 61%, se]
    14. **Bottom** Custom HTML (Particle) [87%, 6%, se]
    15. **Footer** Custom HTML (Particle) [92%, 6%, se]
    16. **Footer** Custom HTML (Particle) [92%, 28%, se]
    17. **Footer** Custom HTML (Particle) [92%, 51%, se]
    18. **Footer** Custom HTML (Particle) [92%, 72%, se]    
    19. **Copyright** Branding (Particle) [99%, 6%, se]
    20. **Copyright** To Top (Particle) [99%, 46%, se]
    21. **Copyright** Social (Particle) [99%, 77%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
----- 

* Theme Particles / Atoms
    * [Animation on Scroll](atom_aos.md)
    * [Block Content](particle_block.md)
    * [Contact](particle_contact.md)
    * [Content List](particle_contentlist.md)
    * [Content Tabs](particle_contenttabs.md)
    * [WordPress Posts](particle_wordpress.md)
    * [Fixed Header](atom_fixedheader.md)
    * [Icon List](particle_iconlist.md)
    * [Image Grid](particle_image.md)
    * [Info List](particle_info.md)
    * [Lists](particle_lists.md)
    * [Mosaic](particle_mosaic.md)
    * [Newsletter](particle_newsletter.md)
    * [Pricing Table](particle_pricing.md)
    * [Progress Bar](particle_progressbar.md)
    * [Promo Image](particle_promoimage.md)
    * [Simple Counter](particle_simplecounter.md)
    * [Slider](particle_slider.md)
    * [Slideshow](particle_slideshow.md)
    * [Strips Slider](particle_stripsslider.md)
    * [Tab Image](particle_tabimage.md)
    * [Video](particle_video.md)
    * [Swiper](particle_swiper.md)
* Core Particles 
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Chimera:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Chimera RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Chimera demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Chimera demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

While the **Home - Particles** layout is automatically loaded after installing the Chimera theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)


Chimera has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Chimera Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Chimera Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.