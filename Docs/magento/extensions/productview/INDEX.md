---
title: ProductView
description: Your Guide to the ProductView Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!productview:ProductView

---

Introduction
-----

![][demo]

The **ProductView** module overrides the default product view, adding some configurable extras. It does away with the default Magento zoom, which is based on **Scriptaculous**, and replaces it with a **jQuery** version.

The original zoom isn't very user friendly. You need to drag a zoom bar below the image, move up to the image, and click and hold to drag it around and pan. The new jQuery version needs just one click to be activated. Then, simply moving the mouse will pan the image. A second click returns to the full image view.

The thumbnails have also been improved upon. You can now simply click a thumbnail to have that image show as the main picture, with the images fading between one another.

You also have the option of having the thumbnail images show in an overlaid thumb gallery, which slides up into view or down and out of view when clicked. You can also choose between a two or three column layout (as long as your current template supports both layout types). 

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Product View**  [34%, 39%, se]
	2. **Use 2 Column Layout**  [50%, 39%, ne]

![][extension2]

:	1. **Enable Tabbed Product Info**  [13%, 39%, se]
	2. **"Quick Info" Attribute**  [19%, 39%, se]
	3. **"Quick Info" Content**  [28%, 39%, se]
	4. **Tab Attribute**  [56%, 39%, se]
	5. **Tab Content**  [63%, 39%, se]

![][extension3]

:	1. **Show Product Reviews**  [23%, 38%, se]
	2. **Equalize Tab Heights**  [39%, 38%, se]
	3. **Upsell Columns**  [57%, 38%, se]

![][extension4]

:	1. **Enable RokMage Media View**  [12%, 38%, se]
	2. **Resize Product Image Background**  [18%, 38%, se]
	3. **Image Background Location**  [32%, 38%, se]
	4. **Small Image Width**  [40%, 38%, se]
	5. **Small Image Height**  [51%, 38%, se]
	6. **Large Image Width**  [59%, 38%, se]
	7. **Large Image Height**  [67%, 38%, se]
	8. **Thumbnail Width**  [75%, 38%, se]
	9. **Thumbnail Height**  [83%, 38%, se]

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you've downloaded and unzipped the extension package, you'll notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you are developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

![][installation]

:	1. This can also be the name of your template package. [22%, 55%, sw]
	2. This can also be the name of your template package. [77%, 50%, sw]

Magento uses a hierarchy system. Adding the files in the **base** folder will work with any theme package. You can also elect to add the layout, template, and skin files to your theme package folder (instead of base) in order to have the extension apply only to that theme. Anything placed in the theme package folder will override what exists in the **base** folder. Anything in the **base** folder is accepted as default.

>> If you download a RocketTheme Magento template, the extension files will all be included in the theme package folder, not the base folder.

[installation]: assets/installation.jpg
[download]: http://www.rockettheme.com/magento-downloads/1807-extension
[extension1]: assets/extension_1.jpeg
[extension2]: assets/extension_2.jpeg
[extension3]: assets/extension_3.jpeg
[extension4]: assets/extension_4.jpeg
[demo]: assets/demo_productview.jpeg