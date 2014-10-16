---
title: Nuance: Recreating the Demo
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Introduction
-----

![][Nuance]

Recreating features of the demo site used to show off some of the more interesting aspects of Nuance can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Nuance theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Nuance:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Nuance RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Nuance demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Nuance theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Nuance Theme** and selecting the **+** icon located just above the **Style** settings tab.

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Top - Gantry Social Buttons** [5%, 81%, se]
    2. **Header - Gantry Logo** [7%, 14%, se]
    3. **Header - Gantry Menu**  [7%, 41%, se]
    4. **Header - Text** [7%, 70%, se]
    5. **Showcase - RokSprocket (Features)**  [11%, 14%, se]
    6. **Feature - RokSprocket (Headlines)**  [21%, 14%, se]
    7. **Feature - Text**  [21%, 70%, se]
    8. **Main Top - RokSprocket (Grids)**  [25%, 14%, se]
    9. **Main Bottom - Text**  [45%, 14%, se]
    10. **Expanded Bottom - Text**  [50%, 14%, se]
    11. **Extension - Text** [59%, 14%, se]
    12. **Extension - Text** [59%, 32%, se]
    13. **Bottom - Text** [68%, 14%, se]
    14. **Bottom - Text** [68%, 38%, se]
    15. **Bottom - Text** [68%, 64%, se]
    16. **Footer - Text** [82%, 14%, se]
    17. **Footer - Text** [82%, 38%, se]
    18. **Footer - Text** [82%, 64%, se]
    19. **Expanded Footer - Custom Menu** [90%, 30%, se]
    20. **Copyright - Gantry Branding** [92%, 14%, ne]
    21. **Copyright - Gantry Copyright** [92%, 43%, ne]
    22. **Copyright - Gantry To Top** [92%, 83%, ne]

Like any Gantry theme, Nuance utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Top][top]
* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Main Top][maintop]
* [Main Bottom][mainbottom]
* [Expanded Bottom][expandedbottom]
* [Extension][extension]
* [Bottom][bottom]
* [Footer][footer]
* [Expanded Footer][expandedfooter]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[Nuance]: assets/nuance.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[top]: demo_top.md
[showcase]: demo_showcase.md
[feature]: demo_feature.md
[maintop]: demo_maintop.md
[bottom]: demo_bottom.md
[expandedbottom]: demo_expandedbottom.md
[expandedfooter]: demo_expandedfooter.md
[expandedtop]: demo_expandedtop.md
[mainbottom]: demo_mainbottom.md
[extension]: demo_extension.md
[utility]: demo_utility.md
[copyright]: demo_copyright.md
[bottom]: demo_bottom.md
[post]: demo_posts.md
[footer]: demo_footer.md
[demooverride]: demo_override.md
[sidepanelimage]: assets/demo_4.jpg
[theme]: assets/nuance2.jpeg
[scroll]: assets/scrollwidget.jpg
