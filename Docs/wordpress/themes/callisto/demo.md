---
title: Callisto: Recreating the Demo
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Callisto can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Callisto theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

### Theme Particles

* [Contact](particle_contact.md)
* [Content List](particle_contentlist.md)
* [Content Tabs](particle_contenttabs.md)
* [Features Slider](particle_featuresslider.md)
* [WordPress Content](particle_wordpress.md)
* [Headlines](particle_headlines.md)
* [Icon Menu](particle_iconmenu.md)
* [Image Grid](particle_image.md)
* [Info List](particle_info.md)
* [Lists](particle_lists.md)
* [Newsletter](particle_newsletter.md)
* [Promo Image](particle_promoimage.md)

### Core Particles 

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
* [Front Page Layout](layout.md)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Callisto:

* [Gantry 5 Theme Framework](http://gantry.org/)

Several of these plugins may be included with the Callisto RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Callisto demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout outlines were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Callisto demo.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting outline. This can be done by navigating to **Admin -> Callisto Theme -> Outlines** and selecting the **+** icon.

You can then simply find the default outline and select the dark blue **Duplicate** button to create a new one based on the default outline used by your site. This will create an outline, or **Style**. This outline can have its own layout, style, and settings preferences.

It would be a good idea for organization to name this outline something like **Callisto - Home** as it would be used only for the front page of your site.

Menu Editor
-----

![](assets/menu_1.jpeg)

Callisto has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Callisto Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Admin. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Callisto Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, we used the **Front Page** page, which is a blank page we created.
