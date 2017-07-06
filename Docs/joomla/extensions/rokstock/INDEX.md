---
title: RokStock
description: Your Guide to Using RokStock for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokstock:RokStock

---

Introduction
-----

![][rokstock]

RokStock, is an Ajax-powered stocks module for your site. It has been finely tuned to give stocks character such as a coloured line graph, coloured indexes, draggable indexes, tooltips and much more.

Your users can easily add, remove, and reorder the stock symbols in their portfolio, this is stored locally for them in a cookie. The module fits seamlessly into the template and is perfect for any news site.

Requirements
------------

RokStock has the following requirements in order to operate:

* Joomla 3.x - ensure you are using the latest version.
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

>> Also, if you experience the Fatal error: `Call to undefined function curl_init()`, you will need to have CURL enabled on your server. You can ask your hosting provider to activate this.

Key Features
------------

* **Multiple Stocks**: Display multiple stocks and compare them with the graphs and data.
* **Interactivity**: The RokStock module is dynamic. The users can make changes such as adding, removing, and reordering stocks displayed.
* **Cookies**: RokStock stores the user's status in a cookie so the tickers will retain user settings after the page is refreshed.
* **Multiple Readings**: You can showcase the data many different ways. The module is customizable to meet your needs.

RokStock uses the Google Finance API to show its data. There are a wide range of options to choose from and the parameter switches determine the functions of RokStock, such as the types of stocks which are showcased, and controls over the tooltips.

How to install
--------------

Installing RokStock takes just a matter of few minutes.

The first thing you’ll need to do is [download][download] the latest version of RokStock. The package you will download contains everything to get RokStock up and running and it is compatible with both Joomla 2.5 and Joomla 3.x. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 2.5 and 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokstock.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

Once installation is complete, a message highlighted in green should indicate its successful completion.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

[featured]: assets/roksprocket-layout.jpeg
[download]: http://www.rockettheme.com/extensions-downloads/club/1000-rokstock
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokstock]: assets/rokstock.jpeg
[details]: assets/RokStock_details.jpeg
