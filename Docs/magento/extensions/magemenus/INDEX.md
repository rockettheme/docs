---
title: MageMenus
description: Your Guide to the MageMenus Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!magemenus:MageMenus

---

Introduction
-----

![][demo]

The MageMenus module replaces the default Magento dropdown with a configurable jQuery based menu. It also gives you the option of having two side menus, one on the left and one on the right, which can also display links of your choice.

>> NOTE:  This extension overrides some core Magento files - if you have multiple store views, and do not wish to use the extension on a particular view, it should be disabled in the config for that store view, by going to **System -> Configuration -> RT RokMage Modules -> MageMenus** and setting **Enable Top Menu** to **No**. 

Top Menu
-----

From the admin configuration, you can set which items will appear in the top menu, and in which order. You have the choice of whether or not to display a 'Home' link, whether or not to include the catalog categories, which CMS pages to include, if any (up to a maximum of 6), and whether or not to include a 'Contact' link. 

You can also specify "child" pages, to be shown in the dropdown sub-menus. These are added as a comma separated list of URL keys (with no spaces or trailing comma) below the main menu item you wish to be the parent. All menu animation settings can be tweaked in the config too.

The options available are as follows:

* **mm_slidedownspeed**: 250 ⇒ Sets the slide down speed of the 2nd level dropdown.
* **mm_fadeoutspeed**: 150 ⇒ Sets the fade out speed of the 2nd level dropdown.
* **mm_css_pre**: {left: 100, opacity: 0 } ⇒ Sets the position of 3rd level dropdown before it is visible.
* **mm_animatein**: {left: 165, opacity: 1} ⇒ Defines the animation for the 3rd level dropdown coming into view.
* **mm_animateout**: {opacity: 0, left: 180} ⇒ Defines the animation for the 3rd level dropdown going out of view.
* **mm_animate_speed**: 200 ⇒ Sets the overal animation speed.
* **mm_pause**: 200 ⇒ Sets the pause before the dropdown menu retreats on mouseout.

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
	6. **Default Products Layout** Sets whether you'll have a grid or list layout type for products. [77%, 39%, se]

1. **Enable Category View**: Sets whether you wish to enable or disable the Category View extension.

2. **Use 2 Column Layout**: Allows you to choose between the default column layout or a two column layout.

3. **Truncate Product Titles/Descriptions**: Toggles truncating for long product names and/or descriptions.

4. **Max Titles Length**: If truncating is turned on, it'll set a maximum title length for each product.

5. **Max Descriptions Length**: If truncating is turned on, it'll set a maximum description length for each product.

6. **Default Products Layout**: Sets whether you'll have a grid or list layout type for products.

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

![][extension4]

![][extension5]

![][extension6]

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you've downloaded and unzipped the extension package, you'll notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you're developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

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
[extension5]: assets/extension_5.jpeg
[extension6]: assets/extension_6.jpeg
[demo]: assets/demo_magemenus.jpeg