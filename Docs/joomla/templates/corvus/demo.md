---
title: Corvus: Recreating the Demo
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Introduction
=====
![][corvus2]
Recreating features of the demo site used to show off some of the more interesting aspects of Corvus can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we'll break down some of these elements and give you the information you need to know to recreate them on your own site using the Corvus Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We've added most of these elements into the Template's core files in order to make them easily accessible without having to edit any code.

Module Settings
-----
Like any Gantry template, Corvus allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you'll find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][corvus]

:   1. **Social Icons**  [6%, 49%, se]
    2. **RokAjaxSearch**  [6%, 88%, sw]
    3. **FP RokSprocket Strips Showcase**  [12%, 13%, se]
    4. **The Big Story**  [28%, 12%, se]
    5. **FP RokSprocket - Lists**  [32%, 12%, se]
    6. **Demo Corvus**  [32%, 88%, sw]
    7. **Latest News**  [45%, 88%, sw]
    8. **RocketLauncher Package**  [61%, 12%, se]
    9. **Popular Features**  [61%, 38%, se]
    10. **Popular Templates**  [74%, 12%, se]
    11. **FP Footer A** [78%, 12%, se]
    12. **Inside Corvus** [78%, 38%, se]
    13. **Contact Us** [78%, 88%, sw]
    14. **FP Footer Social Button** [87%, 65%, se]

We've detailed how to recreate the individual modules and features pictured above in the links below.

1. [Social Icons][module1]
2. [RokAjaxSearch][module2]
3. [FP RokSprocket Strips Showcase][module3]
4. [The Big Story][module4]
5. [FP RokSprocket - Lists][module5]
6. [Demo Corvus][module6]
7. [Latest News][module7]
8. [RocketLauncher Package][module8]
9. [Popular Features][module9]
10. [Popular Templates][module10]
11. [FP Footer A][module11]
12. [Inside Corvus][module12]
13. [Contact Us][module13]
14. [FP Footer Social Button][module14]

![][scroll]

There is also one additional module that activates as you scroll down the page (pictured above). You can find details about this particular module [here][module15].

Recommended Extensions
=====
Here is a list of RocketTheme extensions used to create the demo version of Corvus:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

All of these extensions are included with the Corvus RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
=====
The front page of the Corvus demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It's because of this that several module and layout overrides were done. In this section, we'll break down the settings you'll need to recreate elements present in the front page of the Corvus template.

Template Settings
-----
The first thing you'll need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you've checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you've assigned to the override. In this case, you'll be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Corvus - Home** as it would be used only for the front page of your site.

#### Assignments
The next step you'll need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you'll want to select **Home** in the Menu Assignments tab..

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----
![][mainmenu]
In your site's main menu, you'll want to make a couple key changes in order for your home page to appear as it does in our demo.

First, you'll need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to ` sep13-home`.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/extensions-joomla/rokajaxsearch
[rokbox]: http://www.rockettheme.com/extensions-joomla/rokbox
[roksprocket]: http://www.rockettheme.com/extensions-joomla/roksprocket
[corvus]: assets/corvus.jpeg
[corvus2]: assets/corvus2.jpeg
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
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[mainmenu]: assets/menu_1.jpg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[scroll]: assets/demo_2.jpeg