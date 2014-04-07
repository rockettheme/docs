---
title: Hadron: Recreating the Demo
description: Your Guide to Recreating Elements of the Hadron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hadron:Hadron

---

Introduction
-----

![][Hadron]

Recreating features of the demo site used to show off some of the more interesting aspects of Hadron can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Hadron theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Hadron:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Hadron RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Hadron demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Hadron theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Hadron Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Header - Gantry Logo** [6%, 44%, se]
    2. **Navigation - Gantry Menu** [9%, 12%, se]
    3. **Navigation - Gantry Social Buttons** [9%, 72%, se]
    4. **Navigation - RokAjaxSearch** [9%, 89%, sw]
    5. **Showcase - RokSprocket** [12%, 12%, se]
    6. **Utility - Text** [27%, 12%, se]
    7. **Feature - Text** [36%, 12%, se]
    8. **Feature - RokSprocket** [41%, 12%, se]
    9. **Main Top - RokSprocket** [53%, 12%, se]
    10. **Main Top - RokSprocket** [57%, 89%, sw]
    11. **Bottom - Text** [78%, 32%, se]
    12. **Bottom - Gantry To Top** [76%, 85%, se]
    13. **Footer - Text** [84%, 32%, se]
    14. **Copyright - Gantry Branding** [88%, 48%, se]
    15. **Copyright - Gantry Copyright** [91%, 43%, se]

Like any Gantry theme, Hadron utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Navigation][navigation]
* [Showcase][showcase]
* [Utility][utility]
* [Feature][feature]
* [Main Top][maintop]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]

The featured posts on the front page of the demo are outlined in the [Featured posts][posts] area of this documentation.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[Hadron]: assets/hadron.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[showcase]: demo_showcase.md
[bottom]: demo_bottom.md
[feature]: demo_feature.md
[extension]: demo_extension.md
[sidebar]: demo_sidebar.md
[posts]: demo_featuredpost.md
[maintop]: demo_maintop.md
[navigation]: demo_navigation.md
[extension]: demo_extension.md
[bottom]: demo_bottom.md
[footer]: demo_footer.md
[social]: demo_social.md
[utility]: demo_utility.md
[copyright]: demo_copyright.md
[top]: demo_top.md
[demooverride]: demo_override.md
[theme]: assets/hadron2.jpeg
[scroll]: assets/scrollwidget.jpg