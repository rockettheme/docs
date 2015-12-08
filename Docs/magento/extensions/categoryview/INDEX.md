---
title: CategoryView
description: Your Guide to the CategoryView Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!categoryview:CategoryView

---

Introduction
-----

![][demo]

The CategoryView module overrides the default category product-list template. It adds a few extra options that help to cut down on page loads, and clean up the layout. The most important change is how it handles switching between a grid layout and a list layout. Unlike the default template, which requires a page refresh to change between the two views, CategoryView uses JavaScript to make the switch.

Instead of two separate pages being required, just to show some extra text, one page is loaded - with all of the product information available. When browsing via the grid mode, the product description is merely hidden, and then shown when the list mode is selected. All other changes are purely CSS. The chosen view is then stored in a cookie and applied to each new page viewed. From the admin configuration, you are able to define whether or not to truncate the titles and descriptions, and which view to use as default, grid, or list.

Product Filter
-----

![][extension4]

You can choose to use a jQuery accordion effect for the product filter in the sidebar.

You can specify a custom title for the filter block if you wish. If left blank, the default **Filter Products By** title will be displayed.

>> NOTE: In order to use this feature, you must set **Is Anchor** to **Yes** in the category display settings.

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Category View** Sets whether you wish to enable or disable the Category View extension. [18%, 39%, se]
	2. **Use 2 Column Layout** Allows you to choose between the default column layout or a two column layout. [24%, 39%, se]
	3. **Truncate Product Titles/Descriptions** Toggles truncating for long product names and/or descriptions. [39%, 39%, se]
	4. **Max Titles Length** If truncating is turned on, it'll set a maximum title length for each product. [53%, 39%, se]
	5. **Max Descriptions Length** If truncating is turned on, it'll set a maximum description length for each product. [65%, 39%, se]
	6. **Default Products Layout** Sets whether you will have a grid or list layout type for products. [77%, 39%, se]

1. **Enable Category View**: Sets whether you wish to enable or disable the Category View extension.

2. **Use 2 Column Layout**: Allows you to choose between the default column layout or a two column layout.

3. **Truncate Product Titles/Descriptions**: Toggles truncating for long product names and/or descriptions.

4. **Max Titles Length**: If truncating is turned on, it'll set a maximum title length for each product.

5. **Max Descriptions Length**: If truncating is turned on, it'll set a maximum description length for each product.

6. **Default Products Layout**: Sets whether you will have a grid or list layout type for products.

![][extension2]

:	1. **Use Accordion Effect** Enables or Disables the accordion effect in product lists. [28%, 39%, se]
	2. **Product Filter Title** Sets the title you wish to appear above product category lists. [41%, 39%, se]
	3. **Open First Accordion by Default** Allows you to set the first accordion to be open on page load. [60%, 39%, se]

1. **Use Accordion Effect**: Enables or Disables the accordion effect in product lists. 

2. **Product Filter Title**: Sets the title you wish to appear above product category lists.

3. **Open First Accordion by Default**: Allows you to set the first accordion to be open on page load.

![][extension3]

:	1. **Image Height** Sets the height (in pixels) of the category product images. [32%, 39%, se]
	2. **Image Width** Sets the width (in pixels) of the category product images. [53%, 39%, se]

1. **Image Height** Sets the height (in pixels) of the category product images.

2. **Image Width** Sets the width (in pixels) of the category product images.

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
[download]: http://www.rockettheme.com/magento/extensions//modal/downloads
[extension1]: assets/extension_1.jpeg
[extension2]: assets/extension_2.jpeg
[extension3]: assets/extension_3.jpeg
[extension4]: assets/demo_categoryview2.jpeg
[demo]: assets/demo_categoryview.jpeg