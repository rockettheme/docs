---
title: RokBox
tags: [rokbox, index, documentation, installation, install, intro]

---

Introduction
-----

RokBox2 is a fully responsive modal plugin for Grav and the successor of the very popular, but quite dated, RokBox1. Rewritten from the ground up it can display many different media formats such as images, videos, music, embedded widgets, Ajax content and Grav widgets and takes advantage of the new technologies such as HTML5 and CSS3.

![][featured]

>> NOTE: If you are upgrading from RokBox1 and you are using the old RokBox syntax, such as `[rokbox]` or `<a rel="rokbox" ..`, you can enable the Backward Compatibility from both the **System** and **Content** plugin.
>>
>> Be aware that the Backward compatibility can dramatically slow down the loading of your site. It is highly suggested to convert the old syntax into the new one.

Requirements
------------

RokBox2 has the following requirements in order to operate:

* Grav 3.x - ensure you are using the latest version
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.


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

Installing RokBox takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokBox. The package you will download contains everything you need to get RokBox up and running and it is compatible with Grav 3.2 or higher. It does not need to be uncompressed.

Once you have downloaded the package, go into the Grav Administrator and:

![][install]

From Grav 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokbox.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

Once installation is complete, you will receive a message indicating that the plugin was installed successfully. To activate RokBox right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages can be updated by uploading the new plugin and/or theme files via FTP, replacing the ones that currently exist on the server. Alternatively, you can remove the existing plugin directory you would like to update via FTP and upload the new package through the backend Installation tool. Deleting a plugin and replacing it using only the Plugin Manager can cause plugin settings to be lost. In either case, we recommend deactivating the plugin or theme prior to replacing its files.


[featured]: assets/rokbox2-layout.png
[download]: http://www.rockettheme.com/
[install]: assets/install.jpeg
