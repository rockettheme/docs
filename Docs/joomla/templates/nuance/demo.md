---
title: Nuance: Recreating the Demo
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Nuance can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Nuance Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----

Like any Gantry template, Nuance allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][template2]

:   1. **Top A - Breadcrumbs**  [5%, 16%, se]
    2. **Header C - Custom HTML**  [7%, 84%, sw]
    3. **Showcase A - RokSprocket Features Scroller**  [10%, 16%, se]
    4. **Feature A - RokSprocket (Headlines)**  [21%, 16%, se]
    5. **Feature B - Custom HTML**  [21%, 68%, se]
    6. **MainTop A - RokSprocket (Grids)**  [25%, 16%, se]
    7. **MainBottom A - Custom HTML**  [45%, 16%, se]
    8. **ExpandedBottom A - Custom HTML**  [50%, 16%, se]
    9. **Extension A - Custom HTML**  [58%, 16%, se]
    10. **Extension B - Custom HTML**  [58%, 35%, se]
    11. **Bottom A - Custom HTML**  [68%, 16%, se]
    12. **Bottom B - Custom HTML** [68%, 40%, se]
    13. **Bottom C - Custom HTML** [68%, 63%, se]
    14. **Footer A - Custom HTML** [82%, 17%, se]
    15. **Footer B - Custom HTML** [82%, 40%, se]
    16. **Footer C - Custom HTML** [82%, 63%, se]
    17. **ExpandedFooter A - Menu** [90%, 33%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Top A - Breadcrumbs][module1]
2. [Header C - Custom HTML][module2]
3. [Showcase A - RokSprocket Features Scroller][module3]
4. [Feature A - RokSprocket (Headlines)][module4]
5. [Feature B - Custom HTML][module5]
6. [MainTop A - RokSprocket (Grids)][module6]
7. [MainBottom-A - Custom HTML][module7]
8. [ExpandedBottom A - Custom HTML][module8]
9. [Extension A - Custom HTML][module9]
10. [Extension B - Custom HTML][module10]
11. [Bottom A - Custom HTML][module11]
12. [Bottom B - Custom HTML][module12]
13. [Bottom C - Custom HTML][module13]
14. [Footer A - Custom HTML][module14]
15. [Footer B - Custom HTML][module15]
16. [Footer C - Custom HTML][module16]
17. [ExpandedFooter A - Menu][module17]


Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Nuance:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Nuance RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Nuance demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Nuance demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Nuance - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you will want to select **Home** in the Menu Assignments tab..

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You will need to change the **Page Class** setting under the Home menu item to ` aug14-home`.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[template2]: assets/nuance2.jpeg
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
[module16]: demo_module_16.md
[module17]: demo_module_17.md
[module18]: demo_module_18.md
[module19]: demo_module_19.md
[module20]: demo_module_20.md
[module21]: demo_module_21.md
[module22]: demo_module_22.md
[module23]: demo_module_23.md
[mainmenu]: assets/menu_1.jpeg
[article]: assets/article.jpg
[demo11]: assets/demo_10.jpeg
[mobile]: assets/mobilemenu.jpeg
[mobile2]: mobilemenu.md
[sidepanelmodule]: demo_module_10.md
[sidepanel]: assets/sidepanel.jpeg
