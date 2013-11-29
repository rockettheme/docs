---
title: ProductScroller
description: Your Guide to the ProductScroller Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!productscroller:ProductScroller

---

Introduction
-----

![][demo]

The ProductScroller module adds a scrollable product list to the home and category pages. The product scroller can be fully configured from the admin section. You can define how you want the **Next** and **Prev** buttons to function – either as **Next Page** buttons, or **Next Product** buttons. Next Page will scroll to the next full page of products, 4 products at a time (or more depending on how many products are shown per page – this is also definable, although you will also need to edit the CSS if you decide to change this value). Next Product will scroll one product at a time.

You can choose whether or not to truncate the product titles. This is useful if you have long product names that won't otherwise fit the product scroller design. You can also choose to enable the **Circular** plugin where you can have the scroller be on an infinite circlular loop, continually scrolling through the products, or else disable it and have it only scroll until the end of the product list and then stop, disabling the 'Next' button. You can also set the speed of the scrolling animation, and the number of products per scroller page.

>> NOTE: If you wish to use dynamically updating lists (﻿Best-Selling, Recently Added, Most Viewed, & Highest Rated﻿)﻿ you will need to disable the cache for **Blocks HTML output** by going to **System -> Cache Management** in the admin. If not, the lists won't be updated and the cached version will be displayed. 

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Homepage Scroller** Enables or disables the homepage scroller in the store view. [12%, 38%, se]
	2. **Enable Category Scroller** Enables or disables the category scroller in the store view. [16%, 38%, se]
	3. **Prev/Next Function** Sets the type of scrolling available. **PRODUCT** scrolls to the next product. **PAGE** scrolls to the next page of products. [20%, 38%, se]
	4. **Enable Scroll Button Fade Animation** This allows you to enable or disable the fade animation that takes place when the prev/next function occurs. [27%, 38%, se]
	5. **Truncate Product Titles** Truncates product titles that are too long for the current design. Useful when some products have long titles that would interfere with the aesthetics of the scroller. [33%, 38%, se]
	6. **Max Titles Length** Sets the maximum length (in characters) for product titles in the scroller. [43%, 38%, se]
	7. **Image Size** Sets the image size (in pixels) for product images. [51%, 38%, se]
	8. **Speed** This is the speed of the scroller (in seconds) of product/page transitions. [59%, 38%, se]
	9. **Circular** Allows you to choose whether or not the scroller will loop around indefinitely. [65%, 38%, se]
	10. **Enable Autoscroll** Enables or disables autoscroll which will rotate between products and/or pages without user input. [72%, 38%, se]
	11. **Autoscroll Interval** The interval (in seconds) between product/page scrolling when autoscroll is active. [78%, 38%, se]
	12. **Products Per Page** This sets how many products will appear at one time in the scroller. CSS will need to be adjusted, also. [84%, 38%, se]

1. **Enable Homepage Scroller** Enables or disables the homepage scroller in the store view.

2. **Enable Category Scroller** Enables or disables the category scroller in the store view.

3. **Prev/Next Function** Sets the type of scrolling available. **PRODUCT** scrolls to the next product. **PAGE** scrolls to the next page of products.

4. **Enable Scroll Button Fade Animation** This allows you to enable or disable the fade animation that takes place when the prev/next function occurs.

5. **Truncate Product Titles** Truncates product titles that are too long for the current design. Useful when some products have long titles that would interfere with the aesthetics of the scroller.

6. **Max Titles Length** Sets the maximum length (in characters) for product titles in the scroller.

7. **Image Size** Sets the image size (in pixels) for product images.

8. **Speed** This is the speed of the scroller (in seconds) of product/page transitions.

9. **Circular** Allows you to choose whether or not the scroller will loop around indefinitely.

10. **Enable Autoscroll** Enables or disables autoscroll which will rotate between products and/or pages without user input.

11. **Autoscroll Interval** The interval (in seconds) between product/page scrolling when autoscroll is active.

12. **Products Per Page** This sets how many products will appear at one time in the scroller. CSS will need to be adjusted, also.

![][extension2]

:	1. **Use Tooltip for Details** Displays product details on an *on hover* tooltip. [20%, 39%, se]
	2. **Use Tooltip Animations** If enabled, tooltips will animate in and out of view. [33%, 39%, se]
	3. **Set Tooltip Offset** Sets the offset position of the tooltip. [47%, 39%, se]
	4. **Disable Ribbons** Disables the corner announcement ribbon. [67%, 39%, se]

1. **Use Tooltip for Details**: Displays product details on an *on hover* tooltip.

2. **Use Tooltip Animations**: If enabled, tooltips will animate in and out of view.

3. **Set Tooltip Offset**: Sets the offset position of the tooltip.

4. **Disable Ribbons**: Disables the corner announcement ribbon.

![][extension3]

:	1. **Number of Products** Determines the number of products show in the scroller. Leave blank to show all products. [27%, 39%, se]
	2. **Filter Products By** Allows you to determine the default filtering rules for products in the scroller. [46%, 39%, se]
	3. **Randomize Products** Displays products randomly within the scroller. [60%, 39%, se]

1. **Number of Products**: Determines the number of products show in the scroller. Leave blank to show all products.

2. **Filter Products By**: Allows you to determine the default filtering rules for products in the scroller.

3. **Randomize Products**: Displays products randomly within the scroller.

![][extension4]

:	1. **Number of Products** Determines the number of products show in the scroller. Leave blank to show all products. [28%, 39%, se]
	2. **Filter Products By** Allows you to determine the default filtering rules for products in the scroller. [48%, 39%, se]
	3. **Randomize Products** Displays products randomly within the scroller. [60%, 39%, se]

1. **Number of Products**: Determines the number of products show in the scroller. Leave blank to show all products.

2. **Filter Products By**: Allows you to determine the default filtering rules for products in the scroller.

3. **Randomize Products**: Displays products randomly within the scroller.

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
[demo]: assets/demo_productscroller.jpeg
[demo2]: assets/demo_productscroller_2.jpeg