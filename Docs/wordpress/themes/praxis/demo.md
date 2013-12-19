---
title: Praxis: Recreating the Demo
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Introduction
-----

![][Praxis]

Recreating features of the demo site used to show off some of the more interesting aspects of Praxis can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Praxis theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Praxis:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Praxis RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Praxis demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the blog. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Praxis theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Praxis Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you will want to select both **Home Page** and **Front Page**.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Navigation - Gantry Menu** [5%, 14%, se]
    2. **Navigation - Gantry Social Buttons** [5%, 62%, se]
    3. **Navigation - RokAjaxSearch** [5%, 86%, sw]
    4. **Header - Gantry Logo** [8%, 14%, se]
    5. **Header - RokSprocket** [8%, 28%, se]
    6. **Showcase - RokSprocket** [12%, 86%, sw]
    7. **Feature - Text** [32%, 14%, se]
    8. **Utility - Text** [51%, 24%, se]
    9. **Main Top - RokSprocket** [58%, 24%, se]
    10. **Bottom - Text** [74%, 24%, se]
    11. **Footer - Text** [78%, 24%, se]
    12. **Footer - Gantry Login Form** [78%, 58%, se]
    13. **Side Widget - Custom Menu** [14%, 14%, se]
    14. **Copyright - Gantry Social Buttons** [91%, 14%, se]
    15. **Copyright - Text** [91%, 70%, se]

Like any Gantry theme, Praxis utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Navigation][navigation]
* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Utility][utility]
* [Main Top][maintop]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]
* [Side Widget][sidewidget]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2624-rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2625-rokbox
[roksprocket]: http://www.rockettheme.com/wordpress-downloads/plugins/free/3228-roksprocket
[Praxis]: assets/Praxis.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[showcase]: demo_showcase.md
[maintop]: demo_maintop.md
[feature]: demo_feature.md
[navigation]: demo_navigation.md
[bottom]: demo_bottom.md
[utility]: demo_utility.md
[extension]: demo_extension.md
[bottom]: demo_mainbottom.md
[footer]: demo_footer.md
[sidewidget]: demo_side.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md
[theme]: assets/Praxis2.jpeg