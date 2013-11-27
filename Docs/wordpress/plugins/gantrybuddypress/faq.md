---
title: Gantry BuddyPress: FAQ
description: Your Guide to Using Gantry BuddyPress for WordPress
breadcrumb: /wordpress:WordPress/!plugins:Plugins/gantrybuddypress:GantryBuddyPress

---

#### What are the requirements of the plugin?

The recommended minimum requirements are :

    WordPress 3.2.1 or higher
    BuddyPress 1.6 or higher
    Gantry Framework plugin 1.28 or higher
    Gantry powered theme (updated for 1.28 compatibility fixes)

#### Where are the options of the plugin?

You can find the plugin options in the Admin Dashboard -> Plugins -> Gantry BuddyPress

#### Does it work with all Gantry powered themes or just any particular one ?

It works with all Gantry powered themes (there can be some styling changes required)! :) If you own a Gantry powered theme - your theme is BuddyPress capable.
Does it work with WordPress Multi Site installations ?

Yes it does! In order to have it working in the Multi Site environment a Gantry Framework plugin version 1.28 or higher is required.

#### Can I customize the CSS style or the HTML structure of the BuddyPress files ?

Yes you can!

In order to customize the CSS styling please follow these steps : * Disable loading of the default style in the Gantry BuddyPress plugin settings * Copy the CSS files from the plugin directory to your theme-directory/css/ * Edit the index.php file and add the CSS files to the head section

In order to change the structure of the BuddyPress files please follow these steps : * Duplicate the 'html' directory from the plugin directory * Rename the duplicated directory to 'buddypress' * Place it in your theme root directory - once plugin will detect these files in your theme directory, it will load them instead of the plugin ones.