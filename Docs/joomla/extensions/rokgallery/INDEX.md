---
title: RokGallery
description: Your Guide to Using RokGallery for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokgallery:RokGallery

---

Introduction
-----
![][rokgallery]

RokGallery is a revolutionary ground-up gallery extension developed to be highly flexible, versatile, and user friendly. The system itself is built on a custom tag-based architecture with the ability to have multiple tag-based galleries.

RokGallery uses design and concepts that have been traditionally reserved for platform-native applications and are for the first time making their way into a web environment.

https://www.youtube.com/watch?v=zUTwqSrFEoM

Requirements
------------

RokGallery has the following requirements in order to operate:

* Joomla 3.x - ensure you are using the latest version.
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.
* PHP support for the SQLite PDO driver
* PHP support for the MySQL PDO driver
* MySQL with InnoDB support
* PHP support for PDO
* PHP support for GD2
* PHP 5.2.17 and above

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
* Modules available include: Grid view and Slideshow view with unique transition effects.

How to install
--------------

Installing RokGallery takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokGallery. The package you will download is a bundle containing all of the required plugins to get RokGallery up and running and it is compatible with Joomla 3.x. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokgallery.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

![][rokgallery_install_1]

Once installation is complete, a message highlighted in green should indicate its successful completion.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

RokBox
-----

We recommend downloading and installing [RokBox][rokbox] in addition to RokGallery. RokBox is a useful companion extension to RokGallery which enables you to make media files available to visitors in an elegant frame without having to leave the page to do so. By linking a RokGallery module to RokBox, you will be able to present images in a way that goes beyond what RokGallery alone can offer.

In addition, RokBox gives you more media options for other areas of your site apart from RokGallery.

[featured]: assets/roksprocket-layout.jpeg
[download]: http://www.rockettheme.com/extensions-downloads/club/2216-rokgallery
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokgallery]: assets/rokgallery.jpeg
[rokgallery_install_1]: assets/rokgallery_install_1.jpeg
[details]: assets/RokStock_details.jpeg
[rokbox]: ../rokbox/
