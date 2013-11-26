---
title: Oculus: Recreating the Demo
description: Your Guide to Recreating Elements of the Oculus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/oculus:Oculus

---

Introduction
-----

![][oculus]

Recreating features of the demo site used to show off some of the more interesting aspects of Oculus can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we'll break down some of these elements and give you the information you need to know to recreate them on your own site using the Oculus theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We've added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Oculus:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]

All of these plugins are included with the Oculus RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Oculus demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the blog. It is because of this that several widget and layout overrides were done. In this section, we'll break down the settings you'll need to recreate elements present in the front page of the Oculus theme.

### Theme Settings

The first thing you'll need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Oculus Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you'll need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you'll want to select both **Home Page** and **Front Page**.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it doesn't require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

### Widget Settings

![][theme]

:   1. **Header - Gantry Social Buttons** [7%, 12%, se]
    2. **Header - Gantry Logo** [7%, 45%, se]
    3. **Header - Gantry Login Form** [7%, 87%, sw]
    4. **Navigation - Gantry Menu** [10%, 52%, sw]
    5. **Navigation - RokAjaxSearch** [10%, 70%, se]
    6. **Showcase - RokSprocket** [13%, 12%, se]
    7. **Showcase - Text** [29%, 12%, se]
    8. **Showcase - RokSprocket** [13%, 87%, sw]
    9. **Sidebar - RokSprocket** [34%, 45%, se]
    10. **Sidebar - RokSprocket** [56%, 45%, se]
    11. **Sidebar - RokSprocket** [34%, 87%, sw]
    12. **Sidebar - Text** [51%, 87%, sw]
    13. **Sidebar - Text** [66%, 87%, sw]
    14. **Footer - Text** [80%, 12%, se]
    15. **Footer - Custom Menu** [80%, 32%, se]
    16. **Footer - Text** [80%, 51%, se]
    17. **Footer - Text** [80%, 71%, se]
    18. **Copyright - Gantry Copyright** [90%, 12%, se]
    19. **Copyright - Gantry To Top** [90%, 87%, sw]

Like any Gantry template, Oculus utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you'll find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You'll see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Navigation][navigation]
* [Showcase][showcase]
* [Sidebar][sidebar]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2624-rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2625-rokbox
[roksprocket]: http://www.rockettheme.com/wordpress-downloads/plugins/free/3228-roksprocket
[oculus]: assets/oculus.jpeg
[roksprocket]: ../../plugins/roksprocket/
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[header]: demo_header.md
[showcase]: demo_showcase.md
[navigation]: demo_navigation.md
[footer]: demo_footer.md
[sidebar]: demo_sidebar.md
[copyright]: demo_copyright.md
[theme]: assets/oculus2.jpeg