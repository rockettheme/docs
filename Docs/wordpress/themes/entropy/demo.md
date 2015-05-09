---
title: Entropy: Recreating the Demo
description: Your Guide to Recreating Elements of the Entropy Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/entropy:Entropy

---

Introduction
-----

![][entropy2]

Recreating features of the demo site used to show off some of the more interesting aspects of Entropy can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Entropy theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Entropy:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokGallery][rokgallery]
* [RokSprocket][roksprocket]

All of these plugins are included with the Entropy RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Entropy demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Entropy theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Entropy Theme** and selecting the **+** icon located just above the **Style** settings tab.

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you will want to select both **Home Page** and **Front Page**. These settings can be found by navigating to **Assignments > Template Page Types** in the theme settings.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][Entropy]

:   1. **Top - Gantry Logo** [5%, 25%, se]
    2. **Top - Gantry Menu** [5%, 42%, se]
    3. **Header - Text** [8%, 52%, se]
    4. **Showcase - RokFeatureTable** [15%, 25%, se]
    5. **Feature - Text** [32%, 25%, se]
    6. **Main Top - Text** [35%, 25%, se]
    7. **Main Top - Text** [35%, 52%, se]
    8. **Main Top - Text** [39%, 25%, se]
    9. **Main Top - Text** [39%, 52%, se]
    10. **Main Top - Text** [44%, 25%, se]
    11. **Main Top - Text** [44%, 52%, se]
    12. **Sidebar - Gantry Links** [56%, 55%, se]
    13. **Bottom - Text** [65%, 25%, se]
    14. **Footer - Text** [82%, 25%, se]
    15. **Footer - Text** [82%, 43%, se]
    16. **Footer - Text** [82%, 61%, se]
    17. **Footer - Text** [86%, 25%, se]
    18. **Footer - Text** [86%, 43%, se]
    19. **Footer - Text** [86%, 61%, se]
    20. **Copyright - Gantry Branding** [91%, 45%, se]
    21. **Copyright - Text** [92%, 30%, se]
    22. **MainBody** [50%, 25%, se]

>> Any widgets not specifically pointed out above are likely left out due to the fact that they were created using legacy plugins and/or features of WordPress that are no longer supported.

Like any Gantry theme, Entropy utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

>> NOTE: The big title and subtitles that appear at the top of each panel are set via the theme settings reachable by navigating to **Admin > Entropy Theme > Style**. Just find the associated panel settings and fill in your information there.

### Widget Sections

* [Top][top]
* [Header][header]
* [Showcase][showcase]
* [Feature][feature]
* [Main Top][maintop]
* [Sidebar][sidebar]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]
* [MainBody][mainbody]

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[Entropy]: assets/entropy2.jpg
[entropy2]: assets/entropy.jpeg
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[rokgallery]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[faq]: faq.md
[override]: http://docs.gantry.org/gantry4/configure
[navigation]: demo_navigation.md
[header]: demo_header.md
[feature]: demo_feature.md
[showcase]: demo_showcase.md
[top]: demo_top.md
[mainbody]: demo_posts.md
[bottom]: demo_bottom.md
[navigation]: demo_navigation.md
[maintop]: demo_maintop.md
[contenttop]: demo_contenttop.md
[post]: demo_post.md
[sidebar]: demo_sidebar.md
[mainbottom]: demo_mainbottom.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md
