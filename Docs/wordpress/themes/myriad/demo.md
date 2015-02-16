---
title: Myriad: Recreating the Demo
description: Your Guide to Recreating Elements of the Myriad Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Introduction
-----

![Myriad](assets/myriad.jpeg)

Recreating features of the demo site used to show off some of the more interesting aspects of Myriad can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Myriad theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Myriad:

* [Gantry Framework](http://gantry-framework.org/download)
* [RokAjaxSearch](http://www.rockettheme.com/wordpress/plugins/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/wordpress/plugins/rokbox)
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket](../../plugins/roksprocket/)

All of these plugins are included with the Myriad RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Myriad demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Myriad theme.

For the front page, we used a **Page Suffix** to load the unique styling for it. You will need to create a **Front Page** override under **Theme Settings**. To get to this page, navigate to **Admin > Myriad Settings**. Once you have done that, simply select the **Gizmos** panel (tab) and enter the following in the **Page Suffix** field: `rt-menu-home -rt-myriad-style`. 

Once this is done, you will need to assign the **Front Page** override to the page. You can find more details about this [assignment here](demo_override.md#assignments).

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Myriad Theme** and selecting the **+** icon located just above the **Style** settings tab.

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion](demo_override.md) of this tutorial.

Widget Settings
-----

![Theme](assets/myriad2.jpeg)

:   1. **Header - Gantry Menu** [5%, 30%, se]
    2. **Slideshow - RokSprocket (Features)** [10%, 35%, se]
    3. **FullStrip - RokSprocket (Strips)**  [23%, 15%, se]
    4. **First Full Width - RokSprocket (Features)**  [30%, 40%, se]
    5. **Feature - Text**  [44%, 15%, se]
    6. **Feature - Text**  [44%, 50%, se]
    7. **Utility - Text**  [56%, 40%, se]
    8. **SecondFullWidth - RokSprocket (Strips)**  [58%, 15%, se]
    9. **Main Top - Text** [69%, 40%, se]
    10. **Sidebar - RokSprocket (Lists)** [71%, 60%, se]
    11. **Extension - Text** [80%, 40%, se]
    12. **Bottom - Text** [86%, 17%, se]
    13. **Bottom - Text** [86%, 40%, se]
    14. **Bottom - Text** [86%, 63%, se]
    15. **Footer - Custom Menu** [91%, 35%, se]
    16. **Copyright - Gantry Branding** [92%, 18%, ne]
    17. **Copyright - Gantry Copyright** [92%, 48%, ne]
    18. **Copyright - Gantry To Top** [92%, 80%, ne]
    19. **MainBody** [71%, 18%, se]

Like any Gantry theme, Myriad utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header](demo_header.md)
* [Slideshow](demo_slideshow.md)
* [FullStrip](demo_fullstrip.md)
* [First Full Width](demo_firstfullwidth.md)
* [Feature](demo_feature.md)
* [Utility](demo_utility.md)
* [Second Full Width](demo_secondfullwidth.md)
* [Main Top](demo_maintop.md)
* [Sidebar](demo_sidebar.md)
* [Extension](demo_extension.md)
* [Bottom](demo_bottom.md)
* [Footer](demo_footer.md)
* [Copyright](demo_copyright.md)
* [MainBody](demo_mainbody)
