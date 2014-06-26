---
title: Halcyon: Recreating the Demo
description: Your Guide to Recreating Elements of the Halcyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/halcyon:Halcyon

---

Introduction
-----

![][theme]

Recreating features of the demo site used to show off some of the more interesting aspects of Halcyon can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Halcyon theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Halcyon:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokGallery][rokgallery]
* [RokSocialButtons][social]

All of these plugins are included with the Halcyon RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Halcyon demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Halcyon theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Halcyon Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments
The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you will want to select both **Home Page** and **Front Page**. These settings can be found by navigating to **Assignments > Template Page Types** in the theme settings. These settings can be found by navigating to **Assignments > Template Page Types** in the theme settings.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme2]

:   1. **Top - Text** [5%, 17%, se]
    2. **Top - Text** [5%, 83%, sw]
    3. **Header - Gantry Logo** [8%, 16%, se]
    4. **Header - RokAjaxSearch** [8%, 66%, nw]
    5. **Navigation - Gantry Menu** [11%, 39%, se]
    6. **Subnavigation - Gantry Menu** [13%, 83%, nw]
    7. **Showcase - RokStories** [15%, 18%, se]
    8. **Showcase - Text** [27%, 25%, se]
    9. **Feature - Text** [30%, 16%, se]
    10. **Feature - Text** [30%, 34%, se]
    11. **Feature - Text** [30%, 52%, se]
    12. **Feature - Text** [30%, 69%, se]
    13. **Sidebar - Text** [40%, 17%, se]
    14. **Main Bottom - Text** [64%, 16%, se]
    15. **Main Bottom - Text** [64%, 40%, se]
    16. **Main Bottom - Text** [64%, 63%, se]
    17. **Extension - Text** [71%, 16%, se]
    18. **Extension - Text** [71%, 45%, se]
    19. **Extension - Text** [71%, 63%, se]
    20. **Bottom - Text** [83%, 16%, se]
    21. **Bottom - Text** [83%, 62%, se]
    22. **Footer - Text** [90%, 17%, se]
    23. **Footer - Text** [90%, 35%, se]
    24. **Footer - Text** [90%, 52%, se]
    25. **Footer - Text** [90%, 70%, se]
    26. **Copyright - Gantry Copyright** [93%, 16%, se]
    27. **Copyright - Gantry To Top** [93%, 45%, se]
    28. **Copyright - Gantry Branding** [93%, 73%, se]

Like any Gantry theme, Halcyon utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Top][top]
* [Header][header]
* [Navigation][navigation]
* [Subnavigation][subnavigation]
* [Showcase][showcase]
* [Feature][feature]
* [Sidebar][sidebar]
* [Main Bottom][mainbottom]
* [Extension][extension]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[theme2]: assets/halcyon2.jpeg
[theme]: assets/halcyon.jpeg
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[rokgallery]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[top]: demo_top.md
[navigation]: demo_navigation.md
[showcase]: demo_showcase.md
[feature]: demo_feature.md
[extension]: demo_extension.md
[header]: demo_header.md
[footer]: demo_footer.md
[subnavigation]: demo_subnavigation.md
[mainbottom]: demo_mainbottom.md
[bottom]: demo_bottom.md
[copyright]: demo_copyright.md
[sidebar]: demo_sidebar.md
[featured]: demo_featured.md
[demooverride]: demo_override.md
[social]: http://www.rockettheme.com/wordpress/plugins/rokutilities