---
title: RokNavMenu: Setup Guide
description: Your Guide to Using RokNavMenu for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roknavmenu:RokNavMenu
tags: [roknavmenu, setup, splitmenu, dropdown]

---

Introduction
-----

There is not a whole lot that needs to be done out of the box to set RokNavMenu up on a RocketTheme template. A lot of what RokNavMenu adds to Joomla is done on the backend by taking the standard Joomla menus and adding additional features and details you can customize to meet your specific needs.

In this tutorial, we will take a look at some of the options available to you through RokNavMenu, as well as some of the most important options you should be aware of when setting up a new site.

Gantry Menu Options
------

In order to make our templates easy to use, we baked RokNavMenu in and made many of the core controls accessible using the **Templates Manager**. The **Menu** tab gives you direct access to options that impact the main menu for your site. This includes: Where it appears on the page, the responsive menu type, and more.

![][menu3]

:	1. **Show** Enabling this option enables the main menu on the frontend. If this is turned off, the menu will not appear as assigned. [40%, 24%, se]
	2. **Type** This option allows you to select the menu type. Types such as **Dropdown** and **Splitmenu** change the way the menu works on the frontend. Some templates may include **Fusion** in lieu of **Dropdown**, and others may also offer **Spicemenu**. [40%, 31%, se]
	3. **Menu Numbering** Enabling or disabling menu numbering is done via this option. This option is not present in all templates.  [40%, 41%, se]
	4. **Select a Menu** The Joomla menu you select here will be the source for the main menu. [50%, 24%, se]
	5. **Position** This is where you select a module position to assign the main menu to. [58%, 32%, sw]
	6. **Responsive Menu** For smartphones and tablets, this option determines how the menu will appear. [66%, 24%, se]
	7. **Enable ID** You can enable or disable the default Joomla menu ID through this setting. [74%, 29%, sw]
	8. **Module Cache** This setting turns on or off default module caching for the menu. [82%, 24%, se]

1. **Show**: Enabling this option enables the main menu on the frontend. If this is turned off, the menu will not appear as assigned.

2. **Type**: This option allows you to select the menu type. Types such as **Dropdown** and **Splitmenu** change the way the menu works on the frontend. Some templates may include **Fusion** in lieu of **Dropdown**, and others may also offer **Spicemenu**.

3. **Menu Numbering**: Enabling or disabling menu numbering is done via this option. This option is not present in all templates.

4. **Select a Menu**: The Joomla menu you select here will be the source for the main menu.

5. **Position**: This is where you select a module position to assign the main menu to.

6. **Responsive Menu**: For smartphones and tablets, this option determines how the menu will appear.

7. **Enable ID**: You can enable or disable the default Joomla menu ID through this setting.

8. **Module Cache**: This setting turns on or off default module caching for the menu.


Menu Item Options
-----

Individual menu items can be edited from **Admin -> Menu -> Menu Name -> Menu Item**. In the **Advanced Settings** area of the editing page, you will find a set of options for each supported menu type. Typically, this includes Dropdown and Splitmenu. Here, you can refine how a menu item appears in a RokNavMenu menu.

>> NOTE: These options will only appear if the **RokExtender** extension (part of RokNavMenu) is **enabled**. Also, these settings will only appear when a Gantry template that supports these options has been set as the default template. When switching to another template, these options may have to be reconfigured for the new template.

### Dropdown Menu Options

![][dropdown]

The Dropdown Menu is an advanced CSS driven dropdown menu system. It offers advanced structural features such as multiple columns, inline icons and text, inline modules and positions, custom column widths, item distribution and menu offset. All of these are configurable for each menu item.

![][menu1]

:	1. **Subtext Line** You can post a second line here. [13%, 47%, se]
	2. **Menu Icon** You can opt to use an icon from Font Awesome to add a visual element to the menu item using this field. For example: `icon-bitcoin`. [19%, 47%, se]
	3. **Custom CSS Class** This field allows you to add a custom CSS class to the menu item. [25%, 47%, se]
	4. **Columns of Child Items** This setting gives you the ability to choose to have one or more columns for child items. [31%, 47%, se]
	5. **Item Distribution** You can choose to distribute child items **Evenly**, **In Order**, or **Manually**. As an example, seven items in three columns distributed **Evenly** is: 3,2,2. If these were done **In Order**, it would be 3,3,1. [38%, 47%, se]
	6. **Manual Item Distribution** This is the comma-separated count of rows in each column. Example: 3,2,2. [49%, 47%, se]
	7. **Drop-Down Width** This is the width of any dropdown column (in pixels). [55%, 47%, se]
	8. **Column Widths** For multiple columns, this is the width (in pixels) of each column. Example: 100,150,300. [61%, 47%, se]
	9. **Group Child Items** You can select whether or not to group children under the menu item rather than as a submenu. [68%, 47%, se]
	10. **Child Item Type** Allows you to select the type of child item. This can be **Menu Items**, **Modules**, or **Module Positions**. Modules and module positions allow you to embed modules within the menu itself. [80%, 47%, se]

1. **Subtext Line**: You can post a second line here.

2. **Menu Icon**: You can opt to use an icon from Font Awesome to add a visual element to the menu item using this field. For example: `icon-bitcoin` will add a [Bitcoin icon][bitcoin].

3. **Custom CSS Class**: This field allows you to add a custom CSS class to the menu item.

4. **Columns of Child Items**: This setting gives you the ability to choose to have one or more columns for child items.

5. **Item Distribution**: You can choose to distribute child items **Evenly**, **In Order**, or **Manually**. As an example, seven items in three columns distributed **Evenly** is: 3,3,2. If these were done **In Order**, it would be 3,3,1.

6. **Manual Item Distribution**: This is the comma-separated count of rows in each column. Example: 3,3,2.

7. **Drop-Down Width**: This is the width of any dropdown column (in pixels).

8. **Column Widths**: For multiple columns, this is the width (in pixels) of each column. Example: 100,150,300.

9. **Group Child Items**: You can select whether or not to group children under the menu item rather than as a submenu.

10. **Child Item Type**: Allows you to select the type of child item. This can be **Menu Items**, **Modules**, or **Module Positions**. Modules and module positions allow you to embed modules within the menu itself. This is especially useful if you would like to have a custom HTML module, or perhaps a login module embedded in the menu itself. There are a lot of different things you can do with this particular option.

### Splitmenu Options

![][split]

Splitmenu is a static menu system that displays 1st level items in the main horizontal menu and further children in the Sidebar.

![][menu2]

:	1. **Subtext Line** You can post a second line here. [32%, 47%, se]
	2. **Menu Icon** You can opt to use an icon from Font Awesome to add a visual element to the menu item using this field. [47%, 47%, se]
	3. **Custom CSS Class** This field allows you to add a custom CSS class to the menu item. [62%, 47%, se]

1. **Subtext Line**: You can post a second line here.

2. **Menu Icon**: You can opt to use an icon from Font Awesome to add a visual element to the menu item using this field.

3. **Custom CSS Class**: This field allows you to add a custom CSS class to the menu item.

RokNavMenu Module Options
------

We designed RokNavMenu to work with most templates, even ones that do not include the Gantry framework. While you might not be able to take advantage of the Templates Manager setup for the main menu in these instances, you can still use styled RokNavMenu modules to extend the features and functionality of the core Joomla menu.

To create a new RokNavMenu module, you need to navigate to **Administrator -> Extensions -> Module Manager -> New** and select **RokNavMenu** as the module type. Here, you can configure the menu module to meet your needs.

### Details 

![][module1]

:	1. **Title** Every module must have a title. This title should be easy to remember should you need to adjust the menu settings in the future. [17%, 43%, se]
	2. **Show Title** Allows you to show or hide the title assigned above. [25%, 43%, se]
	3. **Position** This is the position you wish to have the RokNavMenu module appear. [31%, 43%, se]
	4. **Status** The module can be **Published** (live), **Unpublished** (hidden), or **Trashed**. [42%, 43%, se]
	5. **Access** Allows you to determine who has access to the module. If this is your main menu, it should be **Public**. [49%, 43%, se]
	6. **Ordering** Selects the ordering option for the module. [56%, 43%, se]
	7. **Start Publishing** Allows you to set the module to be moved to a **Published** status at a specific date. [63%, 43%, se]
	8. **Finish Publishing** Allows you to set the module to be moved to an **Unpublished** status at a specific date. [70%, 43%, se]
	9. **Language** Assign a language to the module. [77%, 43%, se]
	10. **Note** An optional note that appears in the module list (todo tasks, etc.) This note only appears on the backend. [84%, 43%, se]

1. **Title**: Every module must have a title. This title should be easy to remember should you need to adjust the menu settings in the future.

2. **Show Title**: Allows you to show or hide the title assigned above.

3. **Position**: This is the position you wish to have the RokNavMenu module appear.

4. **Status**: The module can be **Published** (live), **Unpublished** (hidden), or **Trashed**.

5. **Access**: Allows you to determine who has access to the module. If this is your main menu, it should be **Public**.

6. **Ordering**: Selects the ordering option for the module.

7. **Start Publishing**: Allows you to set the module to be moved to a **Published**: status at a specific date.

8. **Finish Publishing**: Allows you to set the module to be moved to an **Unpublished**: status at a specific date.

9. **Language**: Assign a language to the module.

10. **Note**: An optional note that appears in the module list (todo tasks, etc.) This note only appears on the backend.


### Basic Options

![][module2]

:	1. **Select Menu** Selects a menu to assign to the module. (Example: Main Menu) [17%, 47%, se]
	2. **Limit Levels** Allows you to choose whether or not to limit the levels that appear in this menu. [33%, 47%, se]
	3. **Start Level** This is the level to start rendering the menu at. If you set the **Start** and **End** levels to the same level, and set the **Show Sub-Menu Items** option to **Yes**, only one level will appear in the menu. [41%, 47%, se]
	4. **End Level** This is the level to stop rendering the menu at. [48%, 47%, se]
	5. **Show Sub-Menu Items** Allows you to make sub-menu items available through an expanded menu. [56%, 47%, se]
	6. **Themes** This is the theme you wish to have the menu rendered in. For example: **Fusion**, **Dropdown**, or **Splitmenu**. [80%, 47%, se]

1. **Select Menu**: Selects a menu to assign to the module. (Example: Main Menu)

2. **Limit Levels**: Allows you to choose whether or not to limit the levels that appear in this menu.

3. **Start Level**: This is the level to start rendering the menu at. If you set the **Start** and **End** levels to the same level, and set the **Show Sub-Menu Items** option to **Yes**, only one level will appear in the menu.

4. **End Level**: This is the level to stop rendering the menu at.

5. **Show Sub-Menu Items**: Allows you to make sub-menu items available through an expanded menu.

6. **Themes**: This is the theme you wish to have the menu rendered in. For example: **Fusion**, **Dropdown**, or **Splitmenu**.


### Advanced Options

![][module3]

:	1. **Menu Tag ID** This is an optional ID attribute to assign to the root UL tag of the menu. [15%, 47%, se]
	2. **Menu Class Suffix** This is a suffix to be applied to the CSS class of the menu items. [21%, 47%, se]
	3. **Target Position** JavaScript values to position the popup window. Example: `top=50,left=50,width=200,height=300` [27%, 47%, se]
	4. **Module Class Suffix** A suffix to be applied to the CSS class of the module. This allows for individual module styling. [33%, 47%, se]
	5. **Caching** Select whether to cache the content of this module. [43%, 47%, se]
	6. **Cache Time** This is the time between module recachings. [49%, 47%, se]
	7. **Module Tag** The HTML tag for the module. [58%, 47%, se]
	8. **Bootstrap Size** This option specifies how many columns the module will use. [65%, 47%, se]
	9. **Header Tag** This is the HTML tag for the header/title. It affects how the title of the module appears, if the title is set to **Show**. [71%, 47%, se]
	10. **Header Class** The CSS class for the header/title. [78%, 47%, se]
	11. **Module Style** Use this option to override the template's style for its position. [84%, 47%, se]

1. **Menu Tag ID**: This is an optional ID attribute to assign to the root UL tag of the menu.

2. **Menu Class Suffix**: This is a suffix to be applied to the CSS class of the menu items.

3. **Target Position**: JavaScript values to position the popup window. Example: `top=50,left=50,width=200,height=300`

4. **Module Class Suffix**: A suffix to be applied to the CSS class of the module. This allows for individual module styling.

5. **Caching**: Select whether to cache the content of this module.

6. **Cache Time**: This is the time between module recachings.

7. **Module Tag**: The HTML tag for the module.

8. **Bootstrap Size**: This option specifies how many columns the module will use.

9. **Header Tag**: This is the HTML tag for the header/title. It affects how the title of the module appears, if the title is set to **Show**.

10. **Header Class**: The CSS class for the header/title.

11. **Module Style**: Use this option to override the template's style for its position.


[menu1]: assets/menu_1.jpeg
[menu2]: assets/menu_2.jpeg
[menu3]: assets/menu_3.jpeg
[module1]: assets/module_1.jpeg
[module2]: assets/module_2.jpeg
[module3]: assets/module_3.jpeg
[split]: assets/splitmenu.jpeg
[dropdown]: assets/dropdownmenu.jpeg
[bitcoin]: http://fontawesome.io/icon/btc/