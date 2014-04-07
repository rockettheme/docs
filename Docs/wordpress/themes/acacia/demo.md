---
title: Acacia: Recreating the Demo
description: Your Guide to Recreating Elements of the Acacia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/acacia:Acacia

---

Introduction
-----

![][acacia]

Recreating features of the demo site used to show off some of the more interesting aspects of Acacia can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Acacia theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Acacia:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Acacia RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Acacia demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Acacia theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Acacia Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Header - Gantry Logo** [5%, 15%, se]
    2. **Header - Gantry Menu** [5%, 40%, se]
    3. **Header - RokAjaxSearch** [5%, 75%, se]
    4. **Showcase - RokSprocket** [10%, 15%, se]
    5. **Feature - Text** [24%, 15%, se]
    6. **Main Top - Text** [42%, 15%, se]
    7. **Main Bottom - Text** [58%, 38%, se]
    8. **Extension - RokSprocket** [62%, 15%, se]
    9. **Extension - RokSprocket** [62%, 63%, se]
    10. **Bottom - Text** [75%, 38%, se]
    11. **Footer - Text** [79%, 15%, se]
    12. **Footer - Gantry Login Form** [79%, 85%, sw]
    13. **Copyright - Gantry Copyright** [91%, 15%, se]
    14. **Copyright - Gantry To Top** [91%, 85%, sw]

Like any Gantry theme, Acacia utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Main Top][maintop]
* [Main Bottom][mainbottom]
* [Extension][extension]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[acacia]: assets/acacia.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[showcase]: demo_showcase.md
[mainbottom]: demo_mainbottom.md
[feature]: demo_feature.md
[extension]: demo_extension.md
[posts]: demo_posts.md
[maintop]: demo_maintop.md
[extension]: demo_extension.md
[bottom]: demo_bottom.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[top]: demo_top.md
[demooverride]: demo_override.md
[theme]: assets/acacia2.jpeg
[scroll]: assets/scrollwidget.jpg