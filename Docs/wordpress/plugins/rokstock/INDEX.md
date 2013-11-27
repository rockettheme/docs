---
title: RokStock
description: Your Guide to Using RokStock for Joomla
breadcrumb: /wordpress:WordPress/plugins:Plugins/!rokstock:RokStock

---

Introduction
-----

![][rokstock]

RokStock, is an Ajax-powered stocks widget for your site. It has been finely tuned to give stocks character such as a coloured line graph, coloured indexes, draggable indexes, tooltips and much more.

Your users can easily add, remove, and reorder the stock symbols in their portfolio, this is stored locally for them in a cookie. The widget fits seamlessly into the theme and is perfect for any news site.

Requirements
------------

RokStock has the following requirements in order to operate:

* WordPress 3.x - Ensure you have the latest version.
* Compatible Browser: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 7 and before are not supported

>> Also, if you experience the Fatal error: `Call to undefined function curl_init()`, you'll need to have CURL enabled on your server. You can ask your hosting provider to activate this.

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

The first thing you'll need to do is [download][download] the latest version of RokStock. The package you will download contains everything you need to get RokStock up and running and it is compatible with WordPress 3.2 or higher. It does not need to be uncompressed. 

Once you've downloaded the package, go into the WordPress Administrator and:

From WordPress 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokweather.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

Once installation is complete, you'll receive a message (shown above) indicating that the plugin was installed successfully. To activate RokStock right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

[featured]: assets/roksprocket-layout.png
[download]: http://www.rockettheme.com/wordpress-downloads/plugins/club/2620-rokstock
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokstock]: assets/rokstock.png
[settings]: assets/wp_rokstock_settings.png