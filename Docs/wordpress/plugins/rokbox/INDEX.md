---
title: RokBox
description: Your Guide to Using RokBox for WordPress
breadcrumb: /wordpress:WordPress/plugins:Plugins/!rokbox:RokBox

---

Introduction
============
RokBox2 is a fully responsive modal plugin for WordPress and the successor of the very popular but quite dated RokBox1. Rewritten from the ground up it can display many different media formats such as images, videos, music, embedded widgets, Ajax content and WordPress widgets and takes advantage of the new technologies such as HTML5 and CSS3.

![][featured]

RokBox2 is bundled with:

1. a Content plugin
2. a Button Editor plugin
3. a System plugin

The **Content Plugin** can auto-generate thumbnails of local images that can be used as content for the RokBox2 links. All thumbnails generated are responsive so that they can easily adapt to any device.

The **Button Editor Plugin** allows for easy creation of RokBox2 snippets with just a few clicks.

The **System Plugin** is responsible for loading the assets necessary for RokBox2 to work.

>> NOTE: If you are upgrading from RokBox1 and you are using the old RokBox syntax, such as `{rokbox}` or `<a rel="rokbox" ..`, you can enable the Backward Compatibility from both the **System** and **Content** plugin.
>>
>> Be aware that the Backward compatibility can dramatically slow down the loading of your site. It is highly suggested to convert the old syntax into the new one.

Requirements
------------
RokBox2 has the following requirements in order to operate:

* WordPress 3.2 or above - ensure you are using the latest version
* Compatible Browser: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 7 and before are not supported


Key Features
------------
* HTML5 and CSS3
* Fully Responsive
* Auto thumbnails generator
* Captions supporting HTML syntax
* Ajax Content listener
* Multiple media types supported:
    * Images: base64 encoded, jpg, gif, png, bmp, webp
    * HTML5 Video and Audio
    * TwitPic
    * Instagram
    * YouTube
    * Vimeo
    * Telly (ex TwitVid)
    * Metacafe
    * Dailymotion
    * Spotify
    * Google Maps
* Fit/Unfit Screen: If an image is too big it gets shrunk to fit the view-port but you can always click the Fit Screen icon to expand it and scroll.
* Albums to group related images
* Key Bindings for easy navigation: `⇠` (Previous), `⇢` (Next), `f` Fitscreen/Unfitscreen, `esc` Close


How to install
--------------
Installing RokBox2 takes just a matter of few minutes.

The first thing you'll need to do is [download][download] the latest version of RokBox2. The package you will download is a bundle containing all the required plugins to get RokBox2 up and running and it is compatible with WordPress 3.2 or higher. It does not need to be uncompressed. 

Once you've downloaded the package, go into the WordPress Administrator and:

From WordPress 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokbox.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

Once installation is complete, you'll receive a message (shown above) indicating that the plugin was installed successfully. To activate RokGallery right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.


[featured]: assets/rokbox2-layout.png
[download]: http://www.rockettheme.com/extensions-downloads/free/rokbox/3173-rokbox-plugin/download
