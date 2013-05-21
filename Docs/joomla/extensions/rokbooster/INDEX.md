---
title: RokBooster
description: Your Guide to Using RokBooster for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/!rokbooster:RokBooster

---

Introduction
-----
![][RokBooster]

Increase the speed of your site by enabling the RokBooster plugin. This advanced extension will compress and combine your CSS and JavaScript into as few files as possible each. RokBooster can also convert page and background images to data URLs for increased performance.

RokBooster can dramatically reduce the number of HTTP calls a browser has to make, and sending those compressed files GZipped means your pages will load faster with less load on your server.

Requirements
------------
RokBooster has the following requirements in order to operate:

* Joomla 2.5 or 3.x - ensure you are using the latest version.

>> NOTE: Internet Explorer 7 and before are not supported

>> ALSO: Gzip must be installed on your server and enabled in PHP in order to function.

Key Features
------------

* Combine and compress CSS and JavaScript into as few files as possible
* GZip compression used to send CSS and JavaScript files
* Compress Inline CSS and JavaScript
* Compress Inline and Background Images
* Customizable cache timeout
* Background rendering, so initial file processing won't slow your users down
* Full page scan allows for non-header JavaScript and CSS to be included
* Ability to ignore specific CSS and JavaScript files
* Configurable permissions settings
* Exempted individual CSS/JS files

>> NOTE: If your site's CSS goes blank when you activate RokBooster, there is a permission problem on your server. Please change the Cache File Permissions settings in Advanced.

How to install
--------------
Installing RokBooster is just a matter of few minutes. Firstly [download][rokbooster-download] the latest version of RokBooster. The package you will download is a bundle containing all the required plugins to get RokBooster up and running and it is compatible with both Joomla 2.5.x and Joomla 3.0.x. It does not need to be uncompressed. There is also a version of RokBooster for Joomla 1.5 available.

Once downloaded the package, go into the Joomla Administrator and:

From Joomla 2.5:

* Select from the top menu: `Extend -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `RokBooster.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

From Joomla 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `RokBooster.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

Once installation is complete, a message highlighted in green should indicate its successful completion.

### Accessing the Plugin Page
You can access the RokBooster configuration page by navigating to **Extensions → Plugin Manager**. In the list, you will find **System - RokBooster**. Click the name in order to enter RokBooster's Plugin Manager. The plugin needs to be set to **Enabled** to operate.

[featured]: assets/roksprocket-layout.png
[rokbooster-download]: http://www.rockettheme.com/extensions-downloads/club/2937-rokbooster
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokbooster]: assets/rokbooster.png
[details]: assets/RokStock_details.png