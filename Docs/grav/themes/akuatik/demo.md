---
title: Akuatik: Recreating the Demo
description: Your Guide to Recreating Elements of the Akuatik Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/akuatik:Akuatik

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Akuatik can be done fairly easily. All you need are the right particles and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Akuatik Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Particles
-----

Here is a list of particles that are available in Akuatik, as well as links to documentation to help you get started:

Theme Particles

* [Slideshow](particle_slideshow.md)
* [Info List](particle_info.md)
* [Testimonials](particle_testimonials.md)
* [Category List](particle_categorylist.md)
* [Topic List](particle_topiclist.md)
* [Pricing Table](particle_pricing.md)
* [Team](particle_team.md)
* [Latest News](particle_latestnews.md)
* [Block Content](particle_block.md)
* [Button](particle_button.md)
* [Social](particle_social.md)
* [Featured Video](particle_featuredvideo.md)
* [Simple Counter](particle_simplecounter.md)
* [Newsletter](particle_newsletter.md)
* [Simple Menu](particle_simplemenu.md)
* [Image Grid](particle_image.md)
* [Social](particle_social.md)
* [Grav Pages](particle_grav.md)
* [Grid Statistic](particle_grid.md)
* [Heading](particle_heading.md)
* [Particles](particle_particles.md)
* [Promo](particle_promo.md)
* [Video](particle_video.md)

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

Here is a list of RocketTheme plugins used to create the demo version of Akuatik:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Akuatik RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Akuatik demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Akuatik demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.png)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.png)

Akuatik has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to the Gantry 5 admin and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.