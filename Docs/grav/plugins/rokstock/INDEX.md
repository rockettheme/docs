---
title: RokStock
description: Your Guide to Using RokStock for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/!rokstock:RokStock

---

Introduction
-----

![][rokstock]

RokStock, is an Ajax-powered stocks widget for your site. It has been finely tuned to give stocks character such as a coloured line graph, coloured indexes, draggable indexes, tooltips and much more.

Your users can easily add, remove, and reorder the stock symbols in their portfolio, this is stored locally for them in a cookie. The widget fits seamlessly into the theme and is perfect for any news site.

Requirements
------------

RokStock has the following requirements in order to operate:

* Grav 3.x - Ensure you have the latest version.
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

>> Also, if you experience the Fatal error: `Call to undefined function curl_init()`, you will need to have CURL enabled on your server. You can ask your hosting provider to activate this.

Key Features
------------

* **Multiple Stocks**: Display multiple stocks and compare them with the graphs and data.
* **Interactivity**: The RokStock widget is dynamic. The users can make changes such as adding, removing, and reordering stocks displayed.
* **Cookies**: RokStock stores the user's status in a cookie so the tickers will retain user settings after the page is refreshed.
* **Multiple Readings**: You can showcase the data many different ways. The widget is customizable to meet your needs.

RokStock uses the Google Finance API to show its data. There are a wide range of options to choose from and the parameter switches determine the functions of RokStock, such as the types of stocks which are showcased, and controls over the tooltips.

How to install
--------------
Installing RokStock takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokStock. The package you will download contains everything you need to get RokStock up and running and it is compatible with Grav 3.2 or higher. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Grav Administrator and:

From Grav 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokstock.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

Once installation is complete, you will receive a message indicating that the plugin was installed successfully. To activate RokStock right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages can be updated by uploading the new plugin and/or theme files via FTP, replacing the ones that currently exist on the server. Alternatively, you can remove the existing plugin directory you would like to update via FTP and upload the new package through the backend Installation tool. Deleting a plugin and replacing it using only the Plugin Manager can cause plugin settings to be lost. In either case, we recommend deactivating the plugin or theme prior to replacing its files.

[featured]: assets/roksprocket-layout.png
[download]: http://www.rockettheme.com/grav-downloads/plugins/club/2620-rokstock
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokstock]: assets/rokstock.png
[settings]: assets/wp_rokstock_settings.png