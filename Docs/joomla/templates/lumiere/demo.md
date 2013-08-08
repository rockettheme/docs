---
title: Lumiere: Recreating the Demo
description: Your Guide to Recreating Elements of the Lumiere Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

Introduction
=====
![][lumiere2]
Recreating features of the demo site used to show off some of the more interesting aspects of Lumiere can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we'll break down some of these elements and give you the information you need to know to recreate them on your own site using the Lumiere Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We've added most of these elements into the Template's core files in order to make them easily accessible without having to edit any code.

Module Settings
-----
Like any Gantry template, Lumiere allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you'll find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][Lumiere]

:   1. **FP Showcase - RokSprocket Features**  [10%, 10%, se]
    2. **Search Our Site Title**  [27%, 10%, se]
    3. **Search Our Site Inputbox**  [27%, 25%, se]
    4. **Top News of the Week Title**  [33%, 30%, se]
    5. **FP MainTop - RokSprocket Mosaic**  [38%, 10%, se]
    6. **FP SideBar Menu**  [62%, 10%, se]
    7. **FP SideBar - RokSprocket Lists**  [62%, 90%, sw]
    8. **Popular Templates**  [82%, 10%, se]
    9. **Copyright Menu**  [91%, 38%, se]
    10. **Follow Us**  [91%, 76%, se]
    11. **Popular Features**  [58%, 28%, sw]
    12. **Gantry Extras** [58%, 65%, se]

We've detailed how to recreate the individual modules pictured above in the links below.

1. [FP Showcase - RokSprocket Features][module1]
2. [Search Our Site Title][module2]
3. [Search Our Site Inputbox][module3]
4. [Top News of the Week Title][module4]
5. [FP MainTop - RokSprocket Mosaic][module5]
6. [FP SideBar Menu][module6]
7. [FP SideBar - RokSprocket Lists][module7]
8. [Popular Templates][module8]
9. [Copyright Menu][module9]
10. [Follow Us][module10]
11. [Popular Features][module11]
12. [Gantry extras][module12]

Recommended Extensions
=====
Here is a list of RocketTheme extensions used to create the demo version of Lumiere:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

All of these plugins are included with the Lumiere RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
=====
The front page of the Lumiere demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the blog. It's because of this that several module and layout overrides were done. In this section, we'll break down the settings you'll need to recreate elements present in the front page of the Lumiere template.

Template Settings
-----
The first thing you'll need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you've checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you've assigned to the override. In this case, you'll be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Lumiere - Home** as it would be used only for the front page of your site.

#### Assignments
The next step you'll need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you'll want to select both **Home**.

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----
![][mainmenu]
In your site's main menu, you'll want to make a couple key changes in order for your home page to appear as it does in our demo.

First, you'll need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to ` feb13-home`.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/extensions-joomla/rokajaxsearch
[rokbox]: http://www.rockettheme.com/extensions-joomla/rokbox
[roksprocket]: http://www.rockettheme.com/extensions-joomla/roksprocket
[lumiere]: assets/lumiere.jpeg
[lumiere2]: assets/lumiere2.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/extensions-joomla/roknavmenu
[rokbooster]: http://www.rockettheme.com/extensions-joomla/rokbooster
[rokcandy]: http://www.rockettheme.com/extensions-joomla/rokcandy
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
[mainmenu]: assets/menu_1.jpg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg