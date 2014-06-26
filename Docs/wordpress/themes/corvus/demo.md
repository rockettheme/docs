---
title: Corvus: Recreating the Demo
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Introduction
-----

![][corvus]

Recreating features of the demo site used to show off some of the more interesting aspects of Corvus can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Corvus theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Corvus:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Corvus RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Corvus demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Corvus theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Corvus Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Top - Gantry Social Buttons** [5%, 48%, se]
    2. **Top - RokAjaxSearch** [5%, 64%, se]
    3. **Header - Gantry Logo** [6%, 12%, se]
    4. **Header - Gantry Menu** [8%, 54%, se]
    5. **Showcase - RokSprocket** [12%, 12%, se]
    6. **Feature - Text** [28%, 12%, se]
    7. **Sidebar - RokSprocket** [31%, 38%, se]
    8. **Sidebar - Text** [31%, 70%, se]
    9. **Sidebar - RokSprocket** [44%, 70%, se]
    10. **Main Bottom - Text** [60%, 12%, se]
    11. **Main Bottom - RokSprocket** [60%, 38%, se]
    12. **Extension - Text** [74%, 12%, se]
    13. **Footer - Text** [78%, 12%, se]
    14. **Footer - Text** [78%, 38%, se]
    15. **Footer - Text** [78%, 64%, se]
    16. **Footer - Text** [88%, 64%, se]
    17. **Copyright - Gantry To Top** [90%, 89%, sw]
    18. **Featured Posts** [31%, 12%, se]

Like any Gantry theme, Corvus utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

#### Scroll-Triggered Expanded Widget

![][scroll]

The above widget appears below the main showcase as you scroll down the page. This particular instance is a **Text** widget placed in the **Showcase** widget position under the main **RokSprocket** showcase. You will find instructions on this widget in the **Showcase** area of this documentation.

### Widget Sections

* [Top][top]
* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Sidebar][sidebar]
* [Main Bottom][mainbottom]
* [Extension][extension]
* [Footer][footer]
* [Copyright][copyright]

The featured posts on the front page of the demo are outlined in the [Featured posts][posts] area of this documentation.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[corvus]: assets/corvus.jpeg
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
[sidebar]: demo_sidebar.md
[extension]: demo_extension.md
[bottom]: demo_mainbottom.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[top]: demo_top.md
[demooverride]: demo_override.md
[theme]: assets/corvus2.jpeg
[scroll]: assets/scrollwidget.jpg