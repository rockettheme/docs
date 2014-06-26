---
title: Ximenia: Recreating the Demo
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ximenia:Ximenia

---

Introduction
-----

![][ximenia]

Recreating features of the demo site used to show off some of the more interesting aspects of Ximenia can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Ximenia theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Ximenia:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokGallery][rokgallery]
* [RokSocialButtons][social]
* [RokSprocket][roksprocket]

All of these plugins are included with the Ximenia RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Ximenia demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Ximenia theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Ximenia Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you will want to select both **Home Page** and **Front Page**. These settings can be found by navigating to **Assignments > Template Page Types** in the theme settings.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][ximenia2]

:   1. **Navigation - Gantry Logo** [6%, 13%, se]
    2. **Navigation - Gantry Menu** [6%, 85%, sw]
    3. **Showcase - RokSprocket** [9%, 13%, se]
    4. **Main Top - RokSprocket** [20%, 13%, se]
    5. **Main Top - Text: Interview Creative Director** [29%, 13%, se]
    6. **Main Top - Gantry Social Buttons** [20%, 85%, sw]
    7. **Main Top - Text: Top Features** [26%, 85%, sw]
    8. **Main Top - RokAjaxSearch** [38%, 85%, sw]
    9. **Sidebar - Text: More Features** [44%, 85%, sw]
    10. **Sidebar - RokSprocket: Ximenia Guide** [55%, 85%, sw]
    11. **Sidebar - Text: Advertisement** [65%, 85%, sw]
    12. **Content Top - Text: Fusion with MegaMenu** [41%, 13%, se]
    13. **Content Top - Text: RokGallery Styling** [48%, 13%, se]
    14. **Content Top - Text: RokSprocket Layouts** [41%, 45%, se]
    15. **Content Top - Text: Core Gantry Framework** [48%, 45%, se]
    16. **Content Bottom - RokGallery** [73%, 13%, se]
    17. **Bottom - Text** [81%, 55%, sw]
    18. **Footer - Text: Top Plugins** [83%, 13%, se]
    19. **Footer - Text: Demo Information** [83%, 38%, se]
    20. **Footer - Text: Contact Details** [83%, 83%, sw]
    21. **Copyright - Gantry Copyright** [92%, 13%, se]
    22. **Copyright - Gantry To Top** [92%, 50%, sw]
    23. **Copyright - Gantry Branding** [92%, 85%, sw]

Like any Gantry theme, Ximenia utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Navigation][navigation]
* [Showcase][showcase]
* [Main Top][maintop]
* [Sidebar][sidebar]
* [Content Top][contenttop]
* [Content Bottom][contentbottom]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[ximenia]: assets/ximenia.jpeg
[ximenia2]: assets/ximenia2.jpeg
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[rokgallery]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[navigation]: demo_navigation.md
[contenttop]: demo_contenttop.md
[showcase]: demo_showcase.md
[maintop]: demo_maintop.md
[feature]: demo_feature.md
[sidebar]: demo_sidebar.md
[contenttop]: demo_contenttop.md
[contentbottom]: demo_contentbottom.md
[bottom]: demo_bottom.md
[extension]: demo_extension.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md
[social]: http://www.rockettheme.com/wordpress/plugins/rokutilities