---
title: RokWeather
description: Your Guide to Using RokWeather for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/!rokweather:RokWeather

---

Introduction
-----

![][rokweather]

RokWeather is an Ajax-powered weather widget which utilizes the Yahoo or Wunderground APIs to display weather data and related information from regions all across the globe.

Included are options to display temperature, climate, wind speed as well as frontend based location user interaction, default location settings and cookie enabling options.

Requirements
------------

RokWeather has the following requirements in order to operate:

* Grav 3.x - Ensure you are using the latest version
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

Key Features
------------

* **Graphical Representation**: the widget is packaged with images to showcase all types of weather from rain to sunshine.
* **Location Chooser**: Click the current area and type your desired location and the widget will show the appropriate weather, with both frontend and backend configuration options.
* **Temperature Units**: RokWeather supports both the Fahrenheit and Celsius temperate scales.
* **Forecast**: Up to 4 days worth of weather forecast (Maximum of 2 for Yahoo).
* **Multiple Readings**: Optional parameters to show humidity, wind speed and weather descriptions.
* **Cookie Control**: Options to configure whether a user's location is stored via a cookie or refreshed each time.

>> The Google API has been replaced by Yahoo and Wunderground.  Also, if you experience the Fatal error: Call to undefined function `curl_init()` error then you need to have CURL enabled on your server. You can ask your hosting provider to activate this.

How to install
--------------

Installing RokWeather takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokWeather. The package you will download contains everything you need to get RokWeather up and running and it is compatible with Grav 3.2 or higher. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Grav Administrator and:

From Grav 3.x:

* Select from the top menu: `wp-admin -> Plugins -> Add New -> Upload`
* Click on the **Choose File** button
* Select the `wp_rokweather.zip` that you just downloaded from your local drive.
* Click the **Install Now** button.

Once installation is complete, you will receive a message (shown above) indicating that the plugin was installed successfully. To activate RokWeather right away, select **Activate Plugin** from this confirmation page.

>> NOTE: RocketTheme packages can be updated by uploading the new plugin and/or theme files via FTP, replacing the ones that currently exist on the server. Alternatively, you can remove the existing plugin directory you would like to update via FTP and upload the new package through the backend Installation tool. Deleting a plugin and replacing it using only the Plugin Manager can cause plugin settings to be lost. In either case, we recommend deactivating the plugin or theme prior to replacing its files.

[featured]: assets/roksprocket-layout.png
[download]: http://www.rockettheme.com/extensions-downloads/club/1003-rokweather
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokweather]: assets/rokweather.png
[details]: assets/rokweather_details.png