---
title: Myriad: Recreating the Demo
description: Your Guide to Recreating Elements of the Myriad (Gantry 5 Edition) Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Myriad can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Myriad Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/myriad2.png)

:   1. **Navigation** Menu (Particle) [1%, 21%, se]
    2. **Slideshow** Features Slider (Particle) [7%, 50%, se]
    3. **Fullstrip** Strips Slider (Particle) [21%, 50%, se]
    4. **Firstfullwidth** Features Slider (Particle) [29%, 50%, se]
    5. **Feature-a** Custom HTML (Particle) [45%, 8%, se]
    6. **Feature-b** Custom HTML (Particle) [45%, 49%, se]
    7. **Utility** Custom HTML (Particle) [59%, 37%, se]
    8. **Secondfullwidth** Strips Slider (Particle) [61%, 50%, se]
    9. **Maintop** Custom HTML (Particle) [73%, 41%, se]
    10. **Mainbody** Custom HTML (Particle) [76%, 7%, se]
    11. **Sidebar** Lists (Particle) [76%, 64%, se]    
    12. **Extension** Custom HTML (Particle) [85%, 50%, se]
    13. **Bottom** Custom HTML (Particle) [93%, 7%, se]
    14. **Bottom** Custom HTML (Particle) [93%, 36%, se]
    15. **Bottom** Custom HTML (Particle) [93%, 65%, se]
    16. **Footer** Horizontal Menu (Particle) [98%, 28%, se]
    17. **Copyright** Branding (Particle) [99%, 5%, se]
    18. **Copyright** Copyright (Particle) [99%, 42%, se]
    19. **Copyright** ToTop (Particle) [99%, 91%, se]

Particles
-----

Here is a list of particles that are available in Myriad, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Myriad Theme > Home > Layout.

* Theme Particles
    - [Audio Player](particle_audio.md)
    - [Calendar](particle_calendar.md)
    - [Case Studies](particle_case.md)
    - [Contact](particle_contact.md)
    - [Content List](particle_contentlist.md)
    - [Features Slider](particle_featuresslider.md)       
    - [WordPress Posts](particle_wordpress.md)
    - [Headlines](particle_headlines.md)
    - [Image Grid](particle_image.md)
    - [Lists](particle_lists.md)
    - [Newsletter](particle_newsletter.md)
    - [Promo Image](particle_promoimage.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Strips Slider](particle_stripsslider.md)
    - [Tab Image](particle_tabimage.md)
    - [Testimonial](particle_testimonial.md)
    - [Video](particle_video.md) 
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

Here is a list of RocketTheme plugins used to create the demo version of Myriad:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Myriad RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Myriad demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Myriad demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

While the **Home - Particles** layout is automatically loaded after installing the Myriad theme, we have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)


Myriad has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Myriad Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Myriad Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.