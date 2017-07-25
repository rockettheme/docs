---
title: Xenon: Recreating the Demo
description: Your Guide to Recreating Elements of the Xenon Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/xenon:Xenon

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Xenon can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Xenon Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/xenon2.jpeg)

:   1. **Top** Logo (Particle) [1%, 5%, se]
    2. **Top** Overlay Toggle (Particle) [1%, 62%, se]
    3. **Top** Social (Particle) [1%, 85%, se]
    4. **Navigation** Menu (Particle) [3%, 7%, se]
    5. **Navigation** Popup Module (Particle) [3%, 85% se]
    6. **Header** FlexSlider (Particle) [7%, 25%, se]
    7. **Above** News Ticker (Particle) [13%, 7%, se]
    8. **Showcase** Popup Grid (Particle) [15%, 7%, se]
    9. **Utility** FlexSlider (Particle) [46%, 7%, se]
    10. **Feature** Image Grid (Particle) [54%, 7%, se]
    11. **Expanded** News Slider (Particle) [69%, 7%, se]
    12. **Extension** Chartist (Particle) [80%, 7%, se]
    13. **Extension** Chartist (Particle) [80%, 40%, se]
    14. **Extension** Chartist (Particle) [80%, 68%, se]
    15. **Bottom** Testimonial (Particle) [88%, 7%, se]
    16. **Bottom** Promo Content (Particle) [93%, 7%, se]
    17. **Footer** Info List (Particle) [95%, 7%, se]
    18. **Footer** Info List (Particle) [95%, 25%, se]
    19. **Footer** Custom HTML (Particle) [95%, 50%, se]
    20. **Footer** Newsletter (Particle) [95%, 75%, se]
    21. **Copyright** Branding (Particle) [99%, 7%, se]
    22. **Copyright** Copyright (Particle) [99%, 35%, se]
    23. **Copyright** To Top (Particle) [99%, 85%, se]

Particles
-----

Here is a list of particles that are available in Xenon, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Gantry5 > Home > Layout in the RocketLauncher package. Any additional particles that are found in the Subpages of our Xenon RocketLauncher can be found via its respective Outline.

* Theme Particles
    - [Block Content](particle_block.md)
    - [Chartist](particle_chartist.md)
    - [Contact](particle_contact.md)
    - [Content List](particle_contentlist.md)
    - [FlexSlider](particle_flexslider.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grav Content](particle_grav.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [News Ticker](particle_newsticker.md)
    - [Newsletter](particle_newsletter.md)
    - [News Slider](particle_newsslider.md)
    - [Overlay Toggle](particle_overlay.md)
    - [Popup Grid](particle_popupgrid.md)
    - [Promo Content](particle_promocontent.md)
    - [Pricing Table](particle_pricing.md)
    - [Promo Image](particle_promoimage.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Testimonial](particle_testimonial.md)
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

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

![Overlay](overlay.jpeg)

There is also an **Overlay** position which appears when the **Overlay Toggle** particle is activated on the front end.

Recreating the Front Page
-----

The front page of the Xenon demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Xenon demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Xenon has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
