---
title: RokGallery
description: Your Guide to Using RokGallery for WordPress
breadcrumb: /wordpress:WordPress/!plugins:Plugins/!rokgallery:RokGallery

---

Introduction
-----
![][featured]

RokGallery is a revolutionary ground-up gallery extension developed to be highly flexible, versatile, and user friendly. The system itself is built on a custom tag-based architecture with the ability to have multiple tag-based galleries.

RokGallery uses design and concepts that have been traditionally reserved for platform-native applications and are for the first time making their way into a web environment.

https://www.youtube.com/watch?v=zUTwqSrFEoM

Requirements
------------
RokGallery has the following requirements in order to operate:

* WordPress 5.x - Ensure that you are using the latest version.
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.
* PHP support for the SQLite PDO driver
* PHP support for the MySQL PDO driver
* MySQL with InnoDB support
* PHP support for PDO
* PHP support for GD2
* PHP 5.2.17 and above
* RokCommon 3.1+ Plugin (You can download it [here][download])

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

>> Also, if you experience the Fatal error: `Call to undefined function curl_init()`, you will need to have CURL enabled on your server. You can ask your hosting provider to activate this.

Key Features
------------
#### Administration Features
* HTML5/Flash multi-file uploader with upload status indicators
* Multiple image ‘slices’ per image with individual zoom/crop sizes
* Custom tag-based architecture
* Interactive multi-selection via selection drag, or “shift” clicking multiple images
* Advanced compound filtering for selecting specific images
* Multiple Gallery support associated by tag
* Ajax-powered for speed optimization
* CSS3 animation effects for that desktop application feel
* Sophisticated slice editor for creating custom views of a particular image file

#### Frontend Features
* Gallery view component with various view options: 3x3, 4x4, Details etc.
* Override-able architecture to allow for custom layouts including custom HTML, CSS, JS, etc.
* Front-end selectable sort options
* Ability to “love” an image
* Image view counter
* Details view for a particular image with full image information
* Modules available include: Grid view and new Slideshow widget with unique transition effects.

How to install
--------------
Installing RokGallery takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokGallery. The package you will download contains everything you need to get RokGallery up and running and it is compatible with WordPress 3.2 or higher. It does not need to be uncompressed. 

Once you have downloaded the package, go into the WordPress Administrator and:

From WordPress 5.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokgallery.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

![][install2]

Once installation is complete, you will receive a message (shown above) indicating that the plugin was installed successfully. To activate RokGallery right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages can be updated by uploading the new plugin and/or theme files via FTP, replacing the ones that currently exist on the server. Alternatively, you can remove the existing plugin directory you would like to update via FTP and upload the new package through the backend Installation tool. Deleting a plugin and replacing it using only the Plugin Manager can cause plugin settings to be lost. In either case, we recommend deactivating the plugin or theme prior to replacing its files.

RokBox
-----
We recommend downloading and installing [RokBox][rokbox] in addition to RokGallery. RokBox is a useful companion extension to RokGallery which enables you to make media files available to visitors in an elegant frame without having to leave the page to do so. By linking a RokGallery widget to RokBox, you will be able to present images in a way that goes beyond what RokGallery alone can offer.

In addition, RokBox gives you more media options for other areas of your site apart from RokGallery.

[featured]: assets/wp_rokgallery.jpeg
[download]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[rokbox]: ../rokbox/
[admin1]: assets/wp_rokgallery_admin_1.jpeg
[admin2]: assets/wp_rokgallery_admin_2.jpeg
[admin3]: assets/wp_rokgallery_admin_3.jpeg
[admin4]: assets/wp_rokgallery_admin_4.jpeg
[install]: assets/wp_rokgallery_install.jpeg
[install2]: assets/wp_rokgallery_install_1.jpeg
[page1]: assets/wp_rokgallery_page_1.jpeg
[page2]: assets/wp_rokgallery_page_2.jpeg
[page3]: assets/wp_rokgallery_page_3.jpeg
[page4]: assets/wp_rokgallery_page_4.jpeg
[settings]: assets/wp_rokgallery_settings.jpeg
[widget1]: assets/wp_rokgallery_widget_1.jpeg
[widget2]: assets/wp_rokgallery_widget_2.jpeg
[widget3]: assets/wp_rokgallery_widget_3.jpeg
[widget4]: assets/wp-rokgallery_widget_4.jpeg
