---
title: ImageBorders
description: Your Guide to the ImageBorders Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!imageborders:ImageBorders

---

Introduction
-----

![][demo]

The ImageBorders module uses jQuery and CSS to style the product images, giving the ability to add any border or frame you desire.

It adds an extra span tag after every product image, which is pulled over the image using CSS. A background image is also added, which combined with the overlay, can transform the standard images into nicely framed ones, as seen to the left (image borders on the left, no border on the right).

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Image Borders** Enables or disables the image borders span tag after product images in the store view. [50%, 39%, se]

1. **Enable Image Borders**: Enables or disables the image borders span tag after product images in the store view.

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you have downloaded and unzipped the extension package, you will notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you are developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

![][installation]

:	1. This can also be the name of your template package. [22%, 55%, sw]
	2. This can also be the name of your template package. [77%, 50%, sw]

Magento uses a hierarchy system. Adding the files in the **base** folder will work with any theme package. You can also elect to add the layout, template, and skin files to your theme package folder (instead of base) in order to have the extension apply only to that theme. Anything placed in the theme package folder will override what exists in the **base** folder. Anything in the **base** folder is accepted as default.

>> If you download a RocketTheme Magento template, the extension files will all be included in the theme package folder, not the base folder.

[installation]: assets/installation.jpg
[download]: http://www.rockettheme.com/magento-downloads/1807-extension
[extension1]: assets/extension_1.jpg
[demo]: assets/demo_imageborders.jpg