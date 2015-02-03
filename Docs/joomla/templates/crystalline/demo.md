---
title: Crystalline: Recreating the Demo
description: Your Guide to Recreating Elements of the Crystalline Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/crystalline:Crystalline

---

Introduction
-----

![][Crystalline2]

Recreating features of the demo site used to show off some of the more interesting aspects of Crystalline can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Crystalline Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

>> NOTE: Modules originally built on extensions and/or Joomla features which are no longer officially supported may not be listed in this guide. For example, modules built on RokTabs and RokStories are no longer supported. Much of their functionality can be found in RokSprocket, which was not available at the time this demo was created.

![][Crystalline]

:   1. **Custom HTML - Color Chooser**  [24%, 17%, se]
    2. **Custom HTML - Built with the Gantry Framework** [24%, 52%, se]
    3. **Custom HTML - Latest Upload** [35%, 17%, se]
    4. **Custom HTML - Advanced Menu Options** [35%, 46%, se]
    5. **RokNavMenu - Main Menu**  [35%, 69%, se]
    6. **Custom HTML - About Us** [47%, 69%, se]
    7. **Custom HTML - Cross Browser Compatible** [59%, 69%, se]
    8. **Who's Online** [65%, 69%, se]
    9. **Custom HTML -  Site Information** [81%, 17%, se]
    10. **MainBody** [47%, 17%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Custom HTML - Color Chooser][module1]
2. [Custom HTML - Built with the Gantry Framework][module2]
3. [Custom HTML - Latest Upload][module3]
4. [Custom HTML - Advanced Menu Options][module4]
5. [RokNavMenu - Main Menu][module5]
6. [Custom HTML - About Us][module6]
7. [Custom HTML - Cross Browser Compatible][module7]
8. [Who's Online][module8]
9. [Custom HTML - Site Information][module9]
10. [MainBody][module10]

Recommended Extensions
-----

Here is a list of RocketTheme extensions we recommend using with Crystalline:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Crystalline RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You can find these settings by navigating to **Admin > Menus > Main Menu > Home**. Once there, you will want to select the **Page Display** tab.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `mar10-home`.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[rokgallery]: http://www.rockettheme.com/joomla/extensions/rokgallery
[Crystalline]: assets/crystalline2.jpeg
[Crystalline2]: assets/crystalline.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg
[mainmenu]: assets/menu_1.jpeg
