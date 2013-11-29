---
title: HomepageGrid
description: Your Guide to the HomepageGrid Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!homepagegrid:HomepageGrid

---

Introduction
-----

![][demo]

The **HomepageGrid** module adds the ability to set up your stores homepage with a few clicks. It adds an optional welcome message (depending on the template being used), and an optional product grid, showing a selection of products, all defined from the configuration section. Using the configuration section in the admin, it is possible to define how many products to show, whether to show as a list or a grid by default, and to decide how the products are filtered. You can choose from the following:

* Select Specific Products From List Below
* Show All Products
* Featured Products
* Best Selling Products
* Recently Added Products
* Most Viewed Products
* Highest Rated Products

>> NOTE: If you wish to use dynamically updating lists (﻿**Best-Selling**, **Recently Added**, **Most Viewed**, and **Highest Rated﻿**)﻿ you will need to disable the cache for **Blocks HTML output** by going to **System -> Cache Management** in the admin. If not, the lists won't be updated and the cached version will be displayed.

If you choose to **Select Specific Products From List Below**, you can use the multi-select list to choose which products to show simply by clicking the products in the list whilst holding CTRL (or CMD if using a Mac). You can also choose to randomize the products or show them in the catalog order, whether to truncate titles and descriptions, and the size of the images to be used (the display size can also be affected by the CSS).

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Homepage Grid** Enables or disables the homepage grid. Instructions for how to enable the block from your CMS homepage are listed below the option. [32%, 39%, se]

1. **Enable Homepage Grid**: Enables or disables the homepage grid. Instructions for how to enable the block from your CMS homepage are listed below the option.

![][extension2]

:	1. **Welcome Message** This field allows you to create a welcome message (if the template supports it) which appears to new visitors to the page. [14%, 38%, se]
	2. **Product Grid Title** This field is where you set the title that appears over the Product Grid in the block. [46%, 38%, se]
	3. **Product Grid Text** This field enables you to enter text which appears under the title within the block. [51%, 38%, se]
	4. **Number of Products Shown** This field allows you to enter a numerical value for the number of products you wish to have appear within the grid in the block. [79%, 38%, se]

1. **Welcome Message**: This field allows you to create a welcome message (if the template supports it) which appears to new visitors to the page.

2. **Product Grid Title**: This field is where you set the title that appears over the Product Grid in the block.

3. **Product Grid Text**: This field enables you to enter text which appears under the title within the block.

4. **Number of Products Shown**: This field allows you to enter a numerical value for the number of products you wish to have appear within the grid in the block.

![][extension3]

:	1. **Default Products Layout** Allows you to choose between a grid and list layout type for products. [9%, 37%, se]
	2. **Filter Products By** Enables you to set the default filtering behavior for the module. [15%, 37%, se]
	3. **Select Homepage List** Select your **Homepage** products from this list. You can hold ctrl and click to select multiple products (cmd and click on Mac). [21%, 37%, se]
	4. **Randomize Products** When enabled, products are presented in a random order in the module. [55%, 37%, se]
	5. **Truncate Product Titles/Descriptions** Enables truncating for long product names and/or descriptions. [65%, 37%, se]
	6. **Max Titles Length** The maximum length (in characters) of a product title that will appear. [74%, 37%, se]
	7. **Max Description Length** The maximum length (in characters) of a product description that will appear. [82%, 37%, se]

1. **Default Products Layout**: Allows you to choose between a grid and list layout type for products.

2. **Filter Products By**: Enables you to set the default filtering behavior for the module. 

3. **Select Homepage List**: Select your **Homepage** products from this list. You can hold ctrl and click to select multiple products (cmd and click on Mac). 

4. **Randomize Products**: When enabled, products are presented in a random order in the module. 

5. **Truncate Product Titles/Descriptions**: Enables truncating for long product names and/or descriptions. 

6. **Max Titles Length**: The maximum length (in characters) of a product title that will appear. 

7. **Max Description Length**: The maximum length (in characters) of a product description that will appear. 

![][extension4]

:	1. **Image Height** Sets the height (in pixels) of a product image. [20%, 38%, se]
	2. **Image Width** Sets the width (in pixels) of a product image. [43%, 38%, se]
	3. **Disable Ribbons** Disables the corner announcement ribbon. [64%, 38%, se]

1. **Image Height**: Sets the height (in pixels) of a product image.

2. **Image Width**: Sets the width (in pixels) of a product image.

3. **Disable Ribbons**: Disables the corner announcement ribbon.

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you have downloaded and unzipped the extension package, you'll notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

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
[demo]: assets/demo_homepagegrid.jpg