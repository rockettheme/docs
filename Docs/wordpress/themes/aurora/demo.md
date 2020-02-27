---
title: Aurora: Recreating the Demo
description: Your Guide to Recreating Elements of the Aurora Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/aurora:Aurora

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Aurora can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Aurora Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/aurora2.png)

:   1. **Navigation** Logo (Particle) [1%, 2%, se]
	2. **Navigation** Menu (Particle) [1%, 17%, se]
	3. **Navigation** Social (Particle) [1%, 92%, se]
    4. **Slideshow** Vertical Slider (Particle) [6%, 12%, se]
    5. **Header** Logo - SVG Pattern (Particle) [17%, 4%, se]
    6. **Header** Simple Content (Particle) [17%, 12%, se]
    7. **Header** Simple Content (Particle) [17%, 60%, se]
    8. **Above** Image Grid (Particle) [22%, 5%, se]
    9. **Above** Custom HTML (Particle) [33%, 11%, se]
    10. **Above** Custom HTML (Particle) [33%, 74%, se]
    11. **Feature** Custom HTML (Particle) [35%, 12%, se]
    12. **Feature** Testimonials (Particle) [35%, 47%, se]
    13. **Showcase** Logo - SVG Pattern (Particle) [40%, 4%, se]
    14. **Showcase** Case Studies (Particle) [44%, 6%, se]
    15. **Utility** Carousel (Particle) [60%, 16%, se]
    16. **Bottom** Logo - SVG Pattern (Particle) [72%, 4%, se]
    17. **Bottom** Panel Slider (Particle) [76%, 21%, se]
    18. **Bottom** Logo - SVG Pattern (Particle) [89%, 4%, se]
    19. **Footer Sidebar** Simple Content (Particle) [92%, 11%, se]
    20. **Footer Sidebar** Social (Particle) [94%, 11%, se]
    21. **Footer Main** Simple Menu (Particle) [92%, 38%, se]
    22. **Footer Aside** Simple Content (Particle) [92%, 67%, se]
    23. **Footer Aside** Newsletter (Particle) [95%, 67%, se]
    24. **Copyright** Branding (Particle) [98%, 37%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Aurora, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Aurora Theme > Home > Layout.

- Theme Particles
    - [Block Content](particle_block.md)
    - [Carousel](particle_carousel.md)
    - [Case Studies](particle_case.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grid Statistic](particle_grid.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [WordPress Posts](particle_wordpress.md)
    - [Newsletter](particle_newsletter.md)
    - [Panel Slider](particle_panel.md)
    - [Pricing Table](particle_pricing.md)
    - [Simple Content](particle_simple.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Testimonials](particle_testimonials.md)
    - [Vertical Slider](particle_vertical.md)
    - [Video](particle_video.md)
- Theme Atoms
    + [Fixed Header](atom_fixedheader.md)

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

Here is a list of RocketTheme plugins used to create the demo version of Aurora:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Aurora RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Aurora demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Aurora demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

While the **Home - Particles** layout is automatically loaded after installing the Aurora theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Aurora has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Aurora Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Aurora Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.