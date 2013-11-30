---
title: How to Install a WordPress Theme
description: Your Guide to Installing a WordPress Theme from RocketTheme
breadcrumb: /wordpress:WordPress/start:Start/!themes:Theme Installation

---

How to Install a WordPress Theme from RocketTheme
-----

There are two primary methods used to install a theme by RocketTheme. You can download the theme files and associated plugins to install them on an existing site, or opt to go with RocketLauncher. 

What makes RocketLauncher an appealing solution is that it includes everything you need to hit the ground running with your site. It comes complete with WordPress, a quick and easy database setup method, associated plugins, and plenty of pre-written content to help you get started with your site.

Whichever way you decide to go, RocketTheme is dedicated to making sure its products are easily updated and capable of running on all of the most common server solutions.

### Installing the Theme

Gantry-powered themes require the Gantry framework in order to run on your site. This plugin is available via the same download page as the theme, and should be installed and activated prior to installing the theme. You can find more detailed instructions on installing the Gantry framework [here][gantry_install].

#### Downloading the Theme Files

Installing the theme by way of the theme files and associated plugins is the most common way to get it on your site if you have existing content and widgets you wish to preserve. You can download all the files listed below by visiting the theme's primary download page.

To install the theme powered by Gantry, you need two files:

* **Theme** (*rt_themename_wp.zip*) - This file is the standalone theme package you will use to install your theme into WordPress.
* **Gantry Plugin** (*gantry_wordpress_framework.zip*) - This file contains the Gantry Framework Plugin and it is required in order to have our themes working.

>> Please note that the Gantry plugin needs to be installed first and activated (does not apply to RocketLauncher).

#### Other Files

There are other files that you may wish to download that accompany the release, but are not required for the theme to work.

* **Source PNG(s)** (*rt_themename_wp-sources.zip*) - This contains all the Adobe Fireworks PNG source files for the theme, and if applicable, the logo font.
* **RocketLauncher** (*rt_themename_wp-rocketlauncher.zip*) - The RocketLauncher pack is a full WordPress install that contains all the demo content, including plugins and the theme.
* **Theme Plugins** (*rt_themename_wp-plugins.zip*) - This file contains all of the recommended plugins in order to run the theme as featured in the demo. This file typically includes the Gantry plugin, RokCommon, and any other required plugins in addition to the recommended additions.

#### Installing Using the WordPress Installer

* Log in into the WordPress administrative dashboard (*http://www.yoursite.com/wp-admin/*).
* In the left menu sidebar, go to **Appearance → Install Themes → Upload**.
* Select the **Choose File** button.
* Locate the **rt_themename_wp.zip** file on your computer.
* Click **Install Now**.
* The theme will now be installed.
* Click **Activate** under the desired theme.

#### Installing Using FTP

* Extract **rt_themename_wp.zip**.
* Load your FTP client, such as [FileZilla][filezilla].
* Upload the **rt_themename_wp** folder to the **/wp-content/themes** directory.
* Log in into the WordPress administrator dashboard (*http://www.yoursite.com/wp-admin/*).
* In the left menu sidebar, go to **Appearance → Themes**.
* Click **Activate** underneath the theme's named section.

### RocketLauncher

>> RocketLauncher includes a FULL WordPress install, in addition to the theme and demo contents. The WordPress installation process is necessary in creating the demo content, therefore RocketLauncher will only work properly as a new WordPress installation. It can not be used on an existing WordPress installation.

* Download the RocketLauncher package (rt_themename_wp_rocketlauncher.zip) from the theme's downloads section.
* Unzip the zip packaged onto your computer to reveal the rt_themename_wp_rocketlauncher folder.
* Upload this to your site using your FTP client.
* Direct your browser to the installation directory. For example: **www.yoursite.com/rt_themename_wp_rocketlauncher**. 
* Follow the standard WordPress installation, after which the theme and gantry framework will automatically be activated, along with the associated sample content.

More detailed instructions on setting up RocketLauncher can be found in our [RocketLauncher documentation][launcher].

[gantry]: http://www.gantry-framework.org/
[gantry_install]: gantry.md
[filezilla]: https://filezilla-project.org
[launcher]: rocketlauncher.md