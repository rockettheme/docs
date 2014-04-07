---
title: Spectral: Recreating the Demo
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Introduction
-----

![][spectral]

Recreating features of the demo site used to show off some of the more interesting aspects of Spectral can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Spectral theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Spectral:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Spectral RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Spectral demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Spectral theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Spectral Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Header - Gantry Logo** [6%, 13%, se]
    2. **Header - Gantry Menu** [6%, 47%, se]
    3. **Showcase - RokSprocket** [10%, 12%, se]
    4. **Utility - RokSprocket** [24%, 12%, se]
    5. **Utility - RokAjaxSearch** [24%, 50%, se]
    6. **Feature - RokSprocket** [28%, 12%, se]
    7. **Feature - Text** [28%, 50%, se]
    8. **Main Top - RokSprocket** [46%, 12%, se]
    9. **Sidebar - RokSprocket** [66%, 63%, se]
    10. **Footer - Text** [80%, 12%, se]
    11. **Footer - Text** [80%, 60%, se]
    12. **Copyright - Gantry Copyright** [91%, 12%, se]
    13. **Copyright - Text** [91%, 41%, se]
    14. **Copyright - Gantry To Top** [91%, 87%, sw]
    15. **Featured Article** [66%, 12%, se]
    16. **Social - Gantry Social Buttons** [12%, 88%, se]

Like any Gantry theme, Spectral utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Utility][utility]
* [Main Top][maintop]
* [Sidebar][sidebar]
* [Footer][footer]
* [Copyright][copyright]
* [Social][social]

The featured posts on the front page of the demo are outlined in the [Featured posts][posts] area of this documentation.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[spectral]: assets/spectral.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[showcase]: demo_showcase.md
[sidebar]: demo_sidebar.md
[feature]: demo_feature.md
[extension]: demo_extension.md
[posts]: demo_featuredpost.md
[maintop]: demo_maintop.md
[extension]: demo_extension.md
[bottom]: demo_bottom.md
[footer]: demo_footer.md
[social]: demo_social.md
[utility]: demo_utility.md
[copyright]: demo_copyright.md
[top]: demo_top.md
[demooverride]: demo_override.md
[theme]: assets/spectral2.jpeg
[scroll]: assets/scrollwidget.jpg