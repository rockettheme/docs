---
title: RokQuickCart
description: Your Guide to Using RokQuickCart for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokquickcart:RokQuickCart

---

Introduction
--------------

![][extension]

RokQuickCart is a simple shopping cart for Joomla. It takes a simple, yet elegant, shopping cart script and integrates directly into Joomla. It allows you to showcase products, inclusive of images, descriptions and additional options, and purchase these items, with support for shipping and tax calculation.

This extension enables you to rapidly set up and deploy a powerful e-commerce system for your Joomla site that accepts payments from **Amazon**, **PayPal**, **Google Checkout**, or a custom SendForm option.

>> NOTE: Google Checkout has been retired by Google and may not be available. Support is maintained to be in-line with [SimpleCart][simplecart]'s current list of supported platforms.

Requirements
------------

* Joomla 3.x - ensure you are using the latest version.
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> Note: A version of RokQuickCart for Joomla 1.5 is available but unsupported.

Key Features
-----

* **Payment Systems**: use PayPal, Amazon, Google Checkout, or a custom SendForm checkout
* **Currencies**: use up to 16 different currencies for your store
* **Tax Rate**: automatic cost calculation based on a tax rate
* **Shipping**: configure shipping costs for auto-calculation
* **RokBox**: product images use RokBox to display larger previews
* **Style**: built-in styling for rapid deployment
* **Based on SimpleCart**: based on the powerful SimpleCart platform to make it easy and simple to use

How to install
--------------

Installing RokQuickCart takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokQuickCart. The package you will download contains all the files you need to get RokQuickCart up and running. It is compatible with Joomla 3.x, and does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokquickcart.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

>> RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

How to Publish to the Frontend
-----

Publishing RokQuickCart to the frontend of your site is an easy process. You do this by creating a menu item using the **RokQuickCart** item type. That menu item becomes your RokQuickCart page.

To do this, navigate to **Administrator -> Menus -> Menu Manager** and select the menu you would like to add a link to your RokQuickCart from. You can then select the green **New** button to initiate the creation of a new menu item. The **Menu Item Type** should be **RokQuickCart**.

You can find more information about menu management in Joomla [in our guide][guide].

[download]: http://www.rockettheme.com/extensions-downloads/free/1112-rokquickcart
[install]: ../../platform/extensions.md#how-to-install-an-extension
[extension]: assets/rokquickcart.jpg
[guide]: ../../basic/menu_manager.md
[simplecart]: http://simplecartjs.org/