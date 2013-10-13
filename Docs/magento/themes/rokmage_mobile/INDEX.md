---
title: RokMage Mobile
description: Your Guide to Using the RokMage Mobile Theme for Magento
tags: [Theme, Template, RokMage, Requirements, Setup]
breadcrumb: /magento:Magento/!themes:Themes/!rokmage_mobile:RokMage Mobile

---

Introduction
-----

![][theme]

RokMage Mobile, the 9th Magento Club Theme release, is a universal mobile template, built on the jQuery Mobile Framework.

The theme has it's own configuration page, and can be styled to match your site in seconds using the jQuery Mobile Theme Roller. 

Features
-----

* Based on jQuery Mobile
* Theme Roller compatible
* Separate Config Settings
* Works on most smartphones
* Landscape/Portrait Support
* Touch ContentSlider
* Touch Image gallery

Themeable via the jQuery Mobile Theme Roller
-----

![][roller]

Using the Theme Roller couldn't be easier - simply drag the colours from the box onto the sections of the swatches and you're done. Then simply download the theme, copy the contents of the minified css, and paste them into the style input in the config, and you're good to go!

How to Install
-----

Installing the RokMage Mobile theme is quick and easy to do. There are numerous ways to do it, but we'll outline the most common method(s) in this tutorial. We'll start with the process you'll likely want to go through if you are installing RokMage Mobile on an existing Magento install.

>> NOTE: We recommend backing up all of your data (including your database) prior to installing any new theme, extension, and/or making any changes to settings.

### Step 1: Download the Theme

To install the theme, you only need one file:

* **RokMage Mobile Theme** (**rt_RokMage Mobile_m.zip**) This file is the theme package you will use to install your theme in Magento. All files are laid out in the correct directory structure, and are ready to be dropped into an existing Magento installation.

There are other files that you may wish to download that accompany the release, but are not required for the theme to work.

* **RokMage Mobile Source PNG(s)** (**rt_RokMage Mobile_m-sources.zip**) This contains all the Adobe Fireworks PNG source files for the template, and if applicable, the logo font.

All of these files can be found on the [Downloads page][download] associated with the RokMage Mobile theme.

### Step 2: Upload the Theme

* Extract **rt_RokMage Mobile_m.zip**
* Open your FTP client ([FileZilla][filezilla] is a popular choice)
* Upload the contents of the unzipped folder to your Magento root directory, being sure to Merge and not Overwrite the files!
* Log in to the Magento administrator dashboard (http://www.(your url).com/admin/ by default)
* Go to **System -> Configuration**
* Click the **Design** tab on the left
* Under the **Package** heading, add RokMage Mobile as the Current Package Name
* Under the **Themes** heading, add style (or which ever preset you prefer) as the Skin (Images / CSS), and save

### Step 3: Set up RokMage Extension Settings

The integrated RokMage extensions are all included in the download zip. However, the configuration settings for each extension also make up part of the theme, as they control image sizes, layout options, animation settings, and so on. So, these changes also need to be added. 

If you've set up a fresh Magento store (with or without sample data) and **have yet to start on any customization**, you can simply drop the extension settings SQL installer file (**mysql4-install-1.0.php**) into the **ExtensionSetup** module (**app/code/community/Rockettheme/ExtensionSetup/sql/extensionsetup_setup/**), replacing the dummy file that's currently there, and it will add the correct tables to your database, complete with the correct settings for each extension.

It will also automatically edit your CMS homepage to show the HomepageGrid extension, edit the other default CMS pages to use the correct RokMageLayout for the theme, and edit the footer menu CMS block to work within the FooterBlock extension. **Be sure to replace the installer file BEFORE you add the theme files to your Magento installation**, otherwise, the ExtensionSetup module will run with the dummy file in place.

You can download the extension settings installer file from the template [download page][download].

>> NOTE: If you have already made customizations to your Magento store (CMS pages, store views, CMS blocks etc) or you have already installed the RokMage extensions with another theme and do not wish to lose your current settings, do NOT use this installer file. It will override your current setup. If you are comfortable dealing with SQL statements, you can edit the installer file to suit your needs. If not, you should add the extension settings manually through **Admin Panel -> Configuration**.

How to Install the RocketLauncher
-----

If you wish to see the theme in a full store setting, you can download the RokMage Mobile RocketLauncher. This will install a complete version of Magento, along with all template files and extensions, plus the Magento sample data.

>> NOTE: Prior to starting installation, you need to to have a MySQL database created and active on your host. You'll be asked for information about this database during installation.

### Step 1: Unpack and Upload the RocketLauncher

* Download the RokMage Mobile RocketLauncher Package (**rt_RokMage Mobile_m-rocketlauncher.zip**) from the [RokMage Mobile template downloads section][download].
* Unzip the package on your computer to reveal the **rt_RokMage Mobile_m-rocketlauncher** folder.
* Upload this to your server using a FTP client.

>> NOTE: on some servers, you can upload the zip and extract the package directly onto your server using cPanel or SSH access. For more details on this, please contact your hosting provider.

### Step 2: Complete the Installation Process

* Direct your browser to the installation (**for example, www.(your site).com/rt_RokMage Mobile_m-rocketlauncher**) URL.
* Follow the installation instructions, including filling out your database information.
* Complete your installation.

[theme]: assets/rokmage_mobile.jpeg
[rokmagelayout]: assets/RokMageLayout.jpg
[roller]: assets/roller.jpg
[download]: http://www.rockettheme.com/magento-downloads/club/2700-rokmagemobile
[filezilla]: https://filezilla-project.org/download.php