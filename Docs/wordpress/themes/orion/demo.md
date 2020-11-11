---
title: Orion: Recreating the Demo
description: Your Guide to Recreating Elements of the Orion Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/orion:Orion

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Orion can be done fairly easily. All you need is the right particles and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Orion Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/orion2.jpg)

1. **Navigation** Logo / Image (Particle)
2. **Navigation** Menu (Particle)
3. **Navigation** Social (Particle)
4. **Slideshow** Promo (Particle)
5. **Slideshow** Slider (Particle)
6. **Header** Logos (Particle)
7. **Header** Info List (Particle)
8. **Above** Showcase (Particle)
9. **Feature** Icon Promo (Particle)
10. **Feature** Testimonials (Particle)
11. **Showcase** Pricing Table (Particle)
12. **Utility** Comparison Table (Particle)
13. **Expanded** Video (Particle)
14. **Expanded** Simple Content (Particle)
15. **Expanded** Button (Particle)
16. **Extension** User Stories (Particle)
17. **Bottom** Grid Statistic (Particle)
18. **Footer** Simple Content (Particle)
19. **Footer** Simple Menu (Particle)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Orion, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Themes > Orion - Home > Layout. Any additional particles that are found in the Subpages of our Orion RocketLauncher can be located via your WordPress Administrator > Extensions > Modules. WordPress allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

Theme Particles

- [Promo](particle_promo.md)
+ [Slider](particle_slider.md)
+ [Logos](particle_logos.md)
+ [Info List](particle_info.md)
+ [Showcase](particle_showcase.md)
+ [Icon Promo](particle_iconpromo.md)
+ [Testimonials](particle_testimonials.md)
+ [Pricing Table](particle_pricing.md)
+ [Comparison Table](particle_comparison.md)
+ [Video](particle_video.md)
+ [Simple Content](particle_simple.md)
+ [Button](particle_button.md)
+ [User Stories](particle_userstories.md)
+ [Grid Statistic](particle_grid.md)
+ [Simple Menu](particle_simplemenu.md)
+ [WordPress Posts](particle_wordpress.md)
+ [Newsletter](particle_newsletter.md)
+ [Block Content](particle_block.md)
+ [Heading](particle_heading.md)
+ [Image Grid](particle_image.md)
+ [Latest News](particle_latestnews.md)
+ [Quote](particle_quote.md)
+ [Search](particle_search.md)
+ [Social](particle_social.md)
+ [Simple Counter](particle_simplecounter.md)
+ [Swiper](particle_swiper.md)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Social](http://docs.gantry.org/gantry5/particles/social)
* [Module Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Orion:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Orion RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Orion demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Orion demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.png)

While the **Home - Particles** layout is automatically loaded after installing the Orion theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.png)


Orion has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Orion Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Orion Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
