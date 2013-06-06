---
title: RokGallery
description: Your Guide to Using RokGallery for WordPress
breadcrumb: /wordpress:WordPress/plugins:Plugins/!rokgallery:RokGallery

---

Introduction
-----
![][featured]

RokGallery is a revolutionary ground-up gallery extension developed to be highly flexible, versatile, and user friendly. The system itself is built on a custom tag-based architecture with the ability to have multiple tag-based galleries.

RokGallery uses design and concepts that have been traditionally reserved for platform-native applications and are for the first time making their way into a web environment.

<iframe width="640" height="360" src="http://www.youtube.com/embed/zUTwqSrFEoM" frameborder="0" allowfullscreen></iframe>

Requirements
------------
RokGallery has the following requirements in order to operate:

* WordPress 3.x - Ensure that you are using the latest version.
* Compatible Browser: Firefox, Chrome, Safari, IE8+, Opera.
* PHP support for the SQLite PDO driver
* PHP support for the MySQL PDO driver
* MySQL with InnoDB support
* PHP support for PDO
* PHP support for GD2
* PHP 5.2.17 and above
* RokCommon 3.1+ Plugin (You can download it [here][rokgallery_download])

>> NOTE: Internet Explorer 7 and before are not supported

>> Also, if you experience the Fatal error: `Call to undefined function curl_init()`, you'll need to have CURL enabled on your server. You can ask your hosting provider to activate this.

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
* Modules available include: Grid view and new Slideshow module with unique transition effects.

How to install
--------------
Installing RokGallery is just a matter of few minutes. Firstly [download][rokgallery_download] the latest version of RokGallery. The package you will download is a bundle containing all the required plugins to get RokBooster up and running. It's compatible with both WordPress 2.5.x and WordPress 3.x.

Once downloaded the package, go into the WordPress Administrator and:

From WordPress 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokgallery.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

![][rokgallery_install_1]

Once installation is complete, you'll receive a message (shown above) indicating that the plugin was installed successfully. To activate RokGallery right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

RokBox
-----
We recommend downloading and installing [RokBox][rokbox] in addition to RokGallery. RokBox is a useful companion extension to RokGallery which enables you to make media files available to visitors in an elegant frame without having to leave the page to do so. By linking a RokGallery module to RokBox, you'll be able to present images in a way that goes beyond what RokGallery alone can offer.

In addition, RokBox gives you more media options for other areas of your site apart from RokGallery.

[featured]: assets/wp_rokgallery.png
[rokgallery_download]: http://www.rockettheme.com/wordpress-downloads/plugins/club/2837-rokgallery
[rokbox]: ../rokbox/
[admin1]: assets/wp_rokgallery_admin_1.png
[admin2]: assets/wp_rokgallery_admin_2.png
[admin3]: assets/wp_rokgallery_admin_3.png
[admin4]: assets/wp_rokgallery_admin_4.png
[install]: assets/wp_rokgallery_install.png
[install2]: assets/wp_rokgallery_install_1.png
[page1]: assets/wp_rokgallery_page_1.png
[page2]: assets/wp_rokgallery_page_2.png
[page3]: assets/wp_rokgallery_page_3.png
[page4]: assets/wp_rokgallery_page_4.png
[settings]: assets/wp_rokgallery_settings.png
[widget1]: assets/wp_rokgallery_widget_1.png
[widget2]: assets/wp_rokgallery_widget_2.png
[widget3]: assets/wp_rokgallery_widget_3.png
[widget4]: assets/wp-rokgallery_widget_4.png