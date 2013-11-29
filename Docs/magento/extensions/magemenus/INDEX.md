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

Side Menus
-----

If you choose to use the side menus, you have the option of defining your own menu titles, whether or not to include the catalog categories, and which CMS pages, if any, to include (to a maximum of 6). You can also include a 'Contact' link if desired, and can add "child" items in the same manner as for the top menu. These sub-menu items are shown in an accordion fashion. 

Breadcrumbs
-----

Although Magento does not support hierarchal CMS pages, the jQuery script that powers the menus will inject a pages "menu" parent into the site breadcrumbs. Both the top and side menus have this functionality - however, if an item appears in both menus, the top menus parent will take precedence. 

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Top Menu** Enables or disables the top menu module. [33%, 39%, se]
	2. **Enable Left Side Menu** Enables or disables the left side menu module. [43%, 39%, se]
	3. **Enable Right Side Menu** Enables or disables the right side menu module. [53%, 39%, se]
	4. **Enable Top Menu lavalamp effect** Enables or disables the lavalamp effect for the top menu module. [63%, 39%, se]

1. **Enable Top Menu**: Enables or disables the top menu module.

2. **Enable Left Side Menu**: Enables or disables the left side menu module.

3. **Enable Right Side Menu**: Enables or disables the right side menu module.

4. **Enable Top Menu lavalamp effect**: Enables or disables the lavalamp effect for the top menu module.

![][extension2]

:	1. **Double column dropdown** Enables the double column dropdowns (default and single). [19%, 38%, se]
	2. **Apply Right Offset Fix** Applies dropdown-position fix to second-level items appearing beyond the template's width. [30%, 38%, se]
	3. **Include 'Home' link** Includes a link to the home page in the top menu. [43%, 38%, se]
	4. **Include Catalog Categories** Includes Catalog categories in the menu. [53%, 38%, se]
	5. **Slot #1 CMS page link** Allows you to disable or select a CMS page to show in this slot. [63%, 38%, se]
	6. **Slot #1 sub-menu items** Allows you to add CMS page URL keys in a comma separated list (no spaces). [72%, 38%, se]

1. **Double column dropdown**: Enables the double column dropdowns (default and single).

2. **Apply Right Offset Fix**: Applies dropdown-position fix to second-level items appearing beyond the template's width.

3. **Include 'Home' link**: Includes a link to the home page in the top menu.

4. **Include Catalog Categories**: Includes Catalog categories in the menu.

5. **Slot #1 CMS page link**: Allows you to disable or select a CMS page to show in this slot.

6. **Slot #1 sub-menu items**: Allows you to add CMS page URL keys in a comma separated list (no spaces).

![][extension3]

:	1. **Animation settings** This field allows you to add jQuery variables for dropdown menu animations. [25%, 39%, se]

1. **Animation settings**: This field allows you to add jQuery variables for dropdown menu animations.

![][extension4]

:	1. **Mega Dropdown Width** Sets the width (in pixels) of the mega dropdown. [17%, 38%, se]
	2. **Visible Sub-categories Depth** Level of subcategories to show. [29%, 38%, se]
	3. **Number of Inner Columns** Maximum number of inner columns to show in mega dropdown. [38%, 38%, se]
	4. **Inner Column Width** Sets the width (in pixels) of the inner columns. [49%, 38%, se]
	5. **Enable Static Blocks** Enables or Disables the presence of static blocks in the menu. [61%, 38%, se]

1. **Mega Dropdown Width**: Sets the width (in pixels) of the mega dropdown.

2. **Visible Sub-categories Depth**: Level of subcategories to show.

3. **Number of Inner Columns**: Maximum number of inner columns to show in mega dropdown.

4. **Inner Column Width**: Sets the width (in pixels) of the inner columns.

5. **Enable Static Blocks**: Enables or Disables the presence of static blocks in the menu.

![][extension5]

:	1. **Menu Title** Adds a title to the menu block. Leave blank if you do not want a title to be present. [16%, 39%, se]
	2. **Include Catalog Categories** Includes catalog categories in the menu. [24%, 39%, se]
	3. **Visible Categories Depth** Sets the level of categories to show. [32%, 39%, se]
	4. **Collapse 1st level parents** Disables links, collapses subcategories, and enables the accordion effect (tree only). [41%, 39%, se]
	5. **Default to open accordion state** Sets the default accordion state to open (tree only). [52%, 39%, se]
	6. **Show Item Count** Shows the number of items in each category. [60%, 39%, se]
	7. **Slot #1 CMS page link** Allows you to disable or select a CMS page to show in this slot. [69%, 39%, se]
	8. **Slot #1 sub-menu items** Allows you to add CMS page URL keys in a comma separated list (no spaces). [77%, 39%, se]

1. **Menu Title**: Adds a title to the menu block. Leave blank if you do not want a title to be present.

2. **Include Catalog Categories**: Includes catalog categories in the menu.

3. **Visible Categories Depth**: Sets the level of categories to show.

4. **Collapse 1st level parents**: Disables links, collapses subcategories, and enables the accordion effect (tree only).

5. **Default to open accordion state**: Sets the default accordion state to open (tree only).

6. **Show Item Count**: Shows the number of items in each category.

7. **Slot #1 CMS page link**: Allows you to disable or select a CMS page to show in this slot.

8. **Slot #1 sub-menu items**: Allows you to add CMS page URL keys in a comma separated list (no spaces).

![][extension6]

:	1. **Menu Title** Adds a title to the menu block. Leave blank if you do not want a title to be present. [16%, 39%, se]
	2. **Include Catalog Categories** Includes catalog categories in the menu. [25%, 39%, se]
	3. **Visible Categories Depth** Sets the level of categories to show. [33%, 39%, se]
	4. **Collapse 1st level parents** Disables links, collapses subcategories, and enables the accordion effect (tree only). [41%, 39%, se]
	5. **Default to open accordion state** Sets the default accordion state to open (tree only). [52%, 39%, se]
	6. **Show Item Count** Shows the number of items in each category. [60%, 39%, se]
	7. **Slot #1 CMS page link** Allows you to disable or select a CMS page to show in this slot. [69%, 39%, se]
	8. **Slot #1 sub-menu items** Allows you to add CMS page URL keys in a comma separated list (no spaces). [77%, 39%, se]

1. **Menu Title**: Adds a title to the menu block. Leave blank if you do not want a title to be present.

2. **Include Catalog Categories**: Includes catalog categories in the menu.

3. **Visible Categories Depth**: Sets the level of categories to show.

4. **Collapse 1st level parents**: Disables links, collapses subcategories, and enables the accordion effect (tree only).

5. **Default to open accordion state**: Sets the default accordion state to open (tree only).

6. **Show Item Count**: Shows the number of items in each category.

7. **Slot #1 CMS page link**: Allows you to disable or select a CMS page to show in this slot.

8. **Slot #1 sub-menu items**: Allows you to add CMS page URL keys in a comma separated list (no spaces).

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
[extension5]: assets/extension_5.jpeg
[extension6]: assets/extension_6.jpeg
[demo]: assets/demo_magemenus.jpeg