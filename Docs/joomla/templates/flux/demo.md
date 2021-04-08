---
title: Flux: Recreating the Demo
description: Your Guide to Recreating Elements of the Flux Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/flux:Flux

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Flux can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Flux Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/flux2.png)

:   1. **Navigation** Logo (Particle) [0%, 2%, se]
	2. **Navigation** Search (Particle) [0%, 12%, se]
	3. **Navigation** Menu (Particle) [0%, 56%, se]
    4. **Slideshow** Slider (Particle) [3%, 50%, se]
    5. **Header** Simple Content (Particle) [15%, 12%, se]
    6. **Header** Simple Content (Particle) [15%, 51%, se]    	
    7. **Header** Video (Particle) [19%, 50%, se]
    8. **Header** Custom (Particle) [29%, 50%, se]
    9. **Above** Simple Content (Particle) [33%, 50%, se]
    10. **Above** Charts (Particle) [36%, 50%, se]
    11. **Feature** Simple Content (Particle) [44%, 12%, se]
    12. **Feature** Cards (Particle) [44%, 57%, se]
    13. **Showcase** Logo (Particle) [56%, 12%, se]
    14. **Showcase** Info List (Particle) [56%, 47%, se]    
    15. **Showcase** Newsletter (Particle) [66%, 12%, se]
    16. **Expanded** Testimonials (Particle) [69%, 12%, se]  
    17. **Utility** Simple Content (Particle) [77%, 12%, se]      
    18. **Utility** Calendar (Particle) [77%, 51%, se]
    19. **Bottom** Carousel (Particle) [86%, 50%, se]
    20. **Footer** Bottom Menu (Particle) [94%, 16%, se]
    21. **Footer** Social (Particle) [94%, 66%, se]
    22. **Footer** Branding (Particle) [98%, 38%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Flux, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Templates > Flux - Home > Layout. Any additional particles that are found in the Subpages of our Flux RocketLauncher can be located via your Joomla Administrator > Extensions > Modules. Joomla allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

* Template Particles
    - [Accordion](particle_accordion.md)
    - [Block Content](particle_block.md)
    - [Calendar](particle_calendar.md)
    - [Cards](particle_cards.md)
    - [Carousel](particle_carousel.md)
    - [Content Tabs](particle_tabs.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grid Statistic](particle_grid.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [Joomla Articles](particle_joomla.md)
    - [Pricing Table](particle_pricing.md)
    - [Simple Charts](particle_simplecharts.md)
    - [Simple Content](particle_simple.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Slider](particle_slider.md)
    - [Testimonials](particle_testimonials.md)
    - [Video](particle_video.md)
    - [Swiper](particle_swiper.md)

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

Here is a list of RocketTheme extensions used to create the demo version of Flux:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Flux RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Flux demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Flux demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

If you did not choose to 'Install Sample Data' upon installing the Flux theme, we have included a convenient layout preset that enables you to load the home page as seen in our demo. This preset is called **Home - Particles** and it includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access this preset by selecting **Load** in the **Layout Manager**.



Menu Editor
-----

![](assets/menu_1.jpeg)

Flux has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Flux > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Flux** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
