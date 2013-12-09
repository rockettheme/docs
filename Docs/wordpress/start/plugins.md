---
title: WordPress: Plugins Guide
description: Your Introductory Guide to Installing and Using Plugins in WordPress.
breadcrumb: /wordpress:WordPress/!start:Start/!plugins_guide:Plugins Guide

---

Introduction
-----

In WordPress, a plugin (referred to as a plug-in in the backend) is used to extend the functionality of the platform beyond its core feature set. There are thousands of WordPress plugins available, for free and via purchase, that enable site managers to do virtually anything with WordPress from managing a podcast to improving the way WordPress handles caching.

RocketTheme has several plugins available that enhance the way WordPress handles content. RokSprocket, for example, makes it easier to display information in a way that is both aesthetically pleasing and simple to use. This type of plugin is made possible by WordPress' robust [Plugin API][api].

How to Install a Plugin
-----

WordPress makes it easy to install new plugins. 

If the plugin you would like to install is listed on [WordPress.org's Plugin Directory][directory], you can search for and find the plugin using the built-in plugins search located on the backend of WordPress located in **Admin -> Plugins -> Add New -> Search**.

RocketTheme carries commercial themes and plugins, so most of our products are not listed in this directory. We have outlined the installation process for RocketTheme plugins below.

![][plugin]

1. Download the RocketTheme plugin ZIP file from [our website][download].

2. Navigate to **Admin -> Plugins -> Add New** (pictured above).

3. Select **Upload**.

4. Click **Choose File** and select the ZIP file.

5. Click **Install Now**.

6. In the confirmation screen, select **Activate Plugin** to activate it.

![][plugin2]

How to Manage Plugins
-----

![][plugin3]

The main Plugin Manager can be found by navigating to **Admin -> Plugins -> Installed Plugins**. Here, you will find a list of all of the currently installed plugins. This list allows you to quickly access settings, activate, deactivate, delete, and edit plugins as needed. We have outlined some of these features below as they relate to RocketTheme plugins.

#### Activate and Deactivate

Activating a plugin turns on its functionality and allows it to affect the way WordPress works. For most plugins, activation is required in order for their settings menu to appear on the backend.

Deactivating an extension essentially turns it off. When a plugin is deactivated, its settings and functionality remains intact, but are not available.

When troubleshooting site issues, deactivating related plugins is a common first step to finding the root cause of a problem.

#### Delete

This option completely removes the plugin from the backend of the site. When deleted, a plugin's settings may be lost, and will need to be reset when reinstalled.

Because uninstalling plugins can result in the removal of plugin-specific settings, we do not recommend uninstalling unless you are sure that you want to completely remove it from the site.

#### Edit

This option takes you to the source files for the plugin and should only be used by advanced users. Any changes made here can directly affect the functionality of the plugin.

#### Update

Many WordPress plugins allow for easy updating through this menu. If an update is available, you will see a message stating such, along with an **Update** link. Clicking this link initiates the update process.

This feature is not available for all plugins. For example, commercial plugins that are not listed on the official WordPress Plugin Directory may not be automatically updated. 

[api]: http://codex.wordpress.org/Plugin_API
[directory]: http://wordpress.org/plugins/
[download]: http://www.rockettheme.com/wordpress-downloads/2565-plugins
[plugin]: assets/plugin_1.jpeg
[plugin2]: assets/plugin_2.jpeg
[plugin3]: assets/plugin_3.jpeg