---
title: FeaturedProducts
description: Your Guide to the FeaturedProducts Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!featuredproducts:FeaturedProducts

---

Introduction
-----

The **FeaturedProducts** module makes it easier for you to define your featured products. From the config section, you can use the dropdown to select 1 of 3 different ways that you can choose the products. For example, you can choose from a selected category, from an attribute, or from a multi-select list of all the products in the store.

#### Featured Category

If you decide to use the featured category option, you can simply create a new category from Catalog->Manage Categories in the admin, calling it for example 'Featured', and then add any products to the category you wish to include.

Next, you can select the category from the dropdown 'Select Featured Category' list in the settings box. This displays all of the categories that have been created. You can of course use any of the already established categories.

#### Featured Attribute

If you decide to use the featured attribute option, simply do the following. When the module is installed, it automatically adds a 'featured' attribute, which can be added to any product via an extra section on the Product Information page in Catalog->Manage Products.

Simply mark the product as featured, and the attribute will be added. By default the ‘featured’ attribute is already selected in the dropdown menu, but you are free to use any attribute you desire.

#### Featured List

If you decide to use the featured list option, you can use the multi-select list to choose which products should be 'featured' simply by clicking the desired products in the list, whilst holding CTRL (or CMD if using a Mac). Once the featured products have been selected, they will be shown anywhere you have specified ‘Featured Products’ to be used (for instance in the ProductScroller or ContentSlider modules). 

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Get Featured Products** Selects where to grab the featured products from. You can choose between **Featured Cateory**, **Featured Attribute**, or **Featured List** below. [40%, 39%, se]

1. **Get Featured Products**: Selects where to grab the featured products from. You can choose between **Featured Cateory**, **Featured Attribute**, or **Featured List** below.

![][extension2]

:	1. **Featured Category** Selects the category of products that will be listed as **Featured**. [See above][category] for more information. [15%, 39%, se]
	2. **Select Featured Attribute** Allows you to add items to the featured products list by attribute. [25%, 39%, se]
	3. **Select Featured List** This is a full product list you can pick and choose from to assign products to be featured. [35%, 39%, se]
	4. **Filter by Store Root** This option is useful when you have a multi-store setup. It makes it possible to filter out products not available in the current store's root category. It prevents bleed over from other stores. [73%, 39%, se]

1. **Featured Category**: Selects the category of products that will be listed as **Featured**. [See above][category] for more information.

2. **Select Featured Attribute**: Allows you to add items to the featured products list by attribute.

3. **Select Featured List**: This is a full product list you can pick and choose from to assign products to be featured.

4. **Filter by Store Root**: This option is useful when you have a multi-store setup. It makes it possible to filter out products not available in the current store's root category. It prevents bleed over from other stores.


How to Install
-----

You can download a zip package from the RokMage Extensions using the **Download** button above..

Once you have downloaded and unzipped the extension package, you will notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

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
[demo]: assets/demo_featuredproducts.jpeg
[category]: index.md#featured-category
[attribute]: index.md#featured-attribute
[list]: index.md#featured-list