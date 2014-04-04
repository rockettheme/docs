---
title: RokNavMenu Exporter for Joomla 2.5 / 3.x
description: This document will guide you through the process of installing RokNavMenu Exporter for Joomla and phpBB.
breadcrumb: /phpbb:phpBB/!modules:Modules/
tags: [Joomla, RokNavMenu, Export, Menu, extension, module, plugin, tutorial]

---

Introduction
-----

RokNavMenu Exporter allows you to bring your existing styled Joomla menu over to phpBB for a more seamless experience. It is a great way to keep your visitors engaged with your site in its entirety, and allow them to transition from your Joomla site to your phpBB forums, without losing the main menu.

RokNavMenu Exporter is primarily a Joomla extension, though it does require a little work to be done on both platforms. Below, we have outlined the requirements and steps you can take to make your phpBB and Joomla sites seamlessly transition between one-another.

Requirements
-----

The requirements for RokNavMenu are as follows:

* Joomla 2.5 / 3.x (A Joomla 1.5 version is available, but no longer supported.)
* phpBB 
* RokBB 3 / 5
* RocketTheme Style

>> NOTE: RokNavMenu Exporter does not function when Joomla is offline. The site being referenced has to be active in order to generate the menu files. RokNavMenu Exporter also does not support **Splitmenu**, or third-party Joomla menus. It requires RokNavMenu installed and active on Joomla to properly function.

How to Install
-----

Installation of RokNavMenu Exporter involves making preparations on both Joomla and phpBB. At the base level, RokNavMenu Exporter is a Joomla extension, but you will need to make sure both Joomla and phpBB are set up properly in order for the exported menu to appear as intended.

Before installing, you should already have RokNavMenu set up on your existing Joomla site. Otherwise, there would not be much for RokNavMenu Exporter to actually export. 

>> NOTE: The instructions detailed below apply to Joomla 2.5 / 3.x. RokNavMenu Exporter for Joomla 1.5 remains available, but is no longer officially supported.

### Step 1: Install RokNavMenu Exporter on Joomla

You can download RokNavMenu Exporter for Joomla 2.5 / 3.x from the [RokNavMenu Downloads Page for Joomla][download] on our official website.

To install the RokNavMenu Exporter, you will need to first log in to your Joomla site's Administrator and navigate to the **Extension Manager** by going to **Administrator -> Extensions -> Extension Manager** and selecting the **Install** tab. From here, you can choose the RokNavMenu Exporter zip file from your local directory and select **Upload and Install**. Once this is done, RokNavMenu Exporter should be installed to Joomla.

### Step 2: Activate the Plugin

![][nav6]

Once it is installed, you will need to activate it by navigating to **Admin -> Extensions -> Plugin Manager** and finding the plugin named **System - RokNavMenu Export**. You can activate it by clicking on the status icon, or selecting its checkbox and clicking **Enable** from the toolbar at the top of the page. Once activated, the status icon should be a green checkmark.

Joomla Setup
-----

Setting up RokNavMenu Exporter is fairly easy. There are a number of options in its configuration menu which need to be set in order for your menu to properly appear on your phpBB site. The following is a breakdown of settings you should set in the **Basic Options** tab after clicking on **System - RokNavMenu Export** in the **Plugin Manager**.

![][nav4]

:	1. **Select Active Menu Item** [42%, 8%, se]
	2. **Headers Filename** Name of the file for head scripts. [51%, 8%, se]
	3. **Guest Menu Filename** Name of the menu file for non-registered users of your forum. [61%, 8%, se]
	4. **Registered Menu Filename** Name of the menu file for registered users of your forum. [69%, 8%, se]
	5. **URL Type** Relative or absolute URL type. (full URL vs. a relative path from the current page) [79%, 8%, se]

1. **Select Active Menu Item** This is the active menu item you wish to set as active. (Example: Home)

2. **Headers Filename** Name of the file for head scripts.

3. **Guest Menu Filename** Name of the menu file for non-registered users of your forum.

4. **Registered Menu Filename** Name of the menu file for registered users of your forum.

5. **URL Type** Relative or absolute URL type. (full URL vs. a relative path from the current page)

With these settings in place, select **Save** and you should be done with the necessary work on the Joomla side. From here, you can head over to phpBB's Administration console to complete the necessary steps.

phpBB Setup
-----

Before you can use the generated menu, there are some settings that need to be adjusted for phpBB to enable support for RokNavMenu Exporter.

First, you will want to make sure you have the latest version of RokBB 3/5 (depending on the RocketTheme Style you have deployed), as well as the phpBB style you want to use. Once these are in place and activated, you will need to navigate to **ACP -> Styles -> Rockettheme Styles -> Global Configuration**, select **RokBB 3/5 Global Configuration**, and configure it as follows: 

![][nav3]

:	1. **Show Joomla Menu** This should be set to **Yes** in order to turn on the feature to show the Joomla menu at the top of the phpBB page instead of the built-in phpBB menu. [37%, 67%, se]
	2. **Joomla Menu Path** This is the relative path to the directory containing your Joomla installation. This path should end in a `/`. (Example: ../joomla/) [45%, 67%, se]
	3. **Guest Menu Filename** This is the name of the menu file used for non-registered users of the forum. Copy this value from your plugin settings in Joomla. These file names must remain the same. [53%, 67%, se]
	4. **Registered Menu Filename** This is the name of the menu file used for registered members of your forum. This name must be the same as the one entered on the Joomla side. [61%, 67%, se]
	5. **Headers Filename** This is the name of the file used for head scripts. [69%, 67%, se]

1. **Show Joomla Menu** This should be set to **Yes** in order to turn on the feature to show the Joomla menu at the top of the phpBB page instead of the built-in phpBB menu.

2. **Joomla Menu Path** This is the relative path to the directory containing your Joomla installation. This path should end in a `/`. If, for example, your phpBB installation is located in a subdirectory within your Joomla install (/joomla root/phpBB/), you would put `../` in the field. The **../** points up one level to the Joomla root directory. If your phpBB installation is located in a different directory branch (on the same level as the Joomla root), then you will want to put `../joomla root/`.

3. **Guest Menu Filename** This is the name of the menu file used for non-registered users of the forum. Copy this value from your plugin settings in Joomla. These file names must remain the same.

4. **Registered Menu Filename** This is the name of the menu file used for registered members of your forum. This name must be the same as the one entered on the Joomla side.

5. **Headers Filename** This is the name of the file used for head scripts.

![][folders]

:	1. **Relative Path** ../ [37%, 32%, sw]
	2. **Relative Path** ../joomla/ [47%, 28%, nw]

Once this is set, press **Submit** and enjoy using your Joomla menu on your phpBB board. If changes made here are not immediately visable, a manual cache purge is advised. You can do this by deleting cached files from the **Cache** folder in the phpBB installation via FTP.

[download]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[nav]: assets/roknavmenu_1.jpeg
[nav2]: assets/roknavmenu_2.jpeg
[nav3]: assets/roknavmenu_3.jpeg
[nav4]: assets/roknavmenu_4.jpeg
[nav5]: assets/roknavmenu_5.jpeg
[nav6]: assets/roknavmenu_6.jpeg
[nav7]: assets/roknavmenu_7.jpeg
[nav8]: assets/roknavmenu_8.jpeg
[folders]: assets/folders.jpg