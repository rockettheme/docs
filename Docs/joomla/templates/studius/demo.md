---
title: Studius: Recreating the Demo
description: Your Guide to Recreating Elements of the Studius Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/studius:Studius

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Studius can be done fairly easily. All you need is the right particles and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Studius Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/studius2.jpg)

3. **Navigation** Logo (Particle)
4. **Navigation** Menu (Particle)
5. **Navigation** Social (Particle)
6. **Slideshow** Slider (Particle)
7. **Header** Info List (Particle)
8. **Above** Image (Particle)
9. **Above** Grid Statistic (Particle)
10. **Feature** Latest News (Particle)
11. **Showcase** User Stories (Particle)
12. **Showcase** Image (Particle)
12. **Utility** Comments Slider (Particle)
13. **Expanded** News (Particle)
14. **Extension** Info List (Particle)
15. **Extension** Joomla Articles (Particle)
16. **Extension** Logos (Particle)
17. **Bottom** Video (Particle)
18. **Footer** Newsletter (Particle)
19. **Footer** Simple Content (Particle)
20. **Footer** Simple Menu (Particle)
21. **Footer** Copyright (Particle)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Studius, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Templates > Studius - Home > Layout. Any additional particles that are found in the Subpages of our Studius RocketLauncher can be located via your Joomla Administrator > Extensions > Modules. Joomla allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

Template Particles

- [Promo](particle_promo.md)
+ [Slider](particle_slider.md)
+ [Logos](particle_logos.md)
+ [Info List](particle_info.md)
+ [Feature Slider](particle_featureslider.md)
+ [Simple Contact](particle_simplecontact.md)
+ [Simple CTA](particle_simplecta.md)
+ [Icon Promo](particle_iconpromo.md)
+ [Comments Slider](particle_commentsslider.md)
+ [Pricing Table](particle_pricing.md)
+ [Comparison Table](particle_comparison.md)
+ [Video](particle_video.md)
+ [Simple Content](particle_simple.md)
+ [Team](particle_team.md)
+ [Team Highlight](particle_teamhighlight.md)
+ [Button](particle_button.md)
+ [Grid Statistic](particle_grid.md)
+ [Simple Menu](particle_simplemenu.md)
+ [Joomla Articles](particle_joomla.md)
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

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Studius:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these extensions are included with the Studius RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Studius demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Studius demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.png)

If you did not choose to 'Install Sample Data' upon installing the Studius theme, we have included a convenient layout preset that enables you to load the home page as seen in our demo. This preset is called **Home - Particles** and it includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access this preset by selecting **Load** in the **Layout Manager**. Make sure to uncheck the "Keep the current Particles while changing Preset" checkbox to start fresh with any of our presets.



Menu Editor
-----

![](assets/menu_1.png)

Studius has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Studius > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.png)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Studius** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
