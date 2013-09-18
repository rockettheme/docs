---
title: Chapelco: Recreating the Demo
description: Your Guide to Recreating Elements of the Chapelco Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/chapelco:Chapelco

---

Introduction
=====
Recreating features of the demo site used to show off some of the more interesting aspects of Chapelco can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we'll break down some of these elements and give you the information you need to know to recreate them on your own site using the Chapelco theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We've added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
=====
Here is a list of RocketTheme plugins used to create the demo version of Chapelco:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokGallery][gallery]

All of these plugins are included with the Chapelco RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
=====
The front page of the Chapelco demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the blog. It's because of this that several widget and layout overrides were done. In this section, we'll break down the settings you'll need to recreate elements present in the front page of the Chapelco theme.

Theme Settings
-----
The first thing you'll need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Chapelco Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments
The next step you'll need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you'll want to select both **Home Page** and **Front Page**.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it doesn't require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----
![][chapelco]

:   1. **Header - Gantry Logo** [6%, 13%, se]
    2. **Header - Gantry Menu** [6%, 31%, se]
    3. **Header - RokAjaxSearch** [6%, 85%, sw]
    4. **Showcase - RokSprocket** [10%, 13%, se]
    5. **Utility - Text** [24%, 13%, se]
    6. **Utility - RokSprocket** [30%, 13%, se]
    7. **MainTop - Text** [48%, 13%, se]
    8. **Sidebar - RokSprocket** [60%, 85%, sw]
    9. **Bottom - Text** [77%, 13%, se]
    10. **Footer - Text** [82%, 13%, se]
    11. **Footer - Text** [82%, 38%, se]
    12. **Footer - Text** [82%, 63%, se]
    13. **Copyright - Text** [91%, 13%, se]
    14. **Copyright - Custom Menu** [91%, 32%, se]
    15. **Copyright - Gantry To Top** [91%, 81%, se]

Like any of our Gantry template demos, Chapelco utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you'll find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You'll see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Showcase][showcase]
* [Utility][utility]
* [MainTop][maintop]
* [Sidebar][sidebar]
* [Bottom][bottom]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2624-rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2625-rokbox
[roksprocket]: http://www.rockettheme.com/wordpress-downloads/plugins/free/3228-roksprocket
[chapelco]: assets/chapelco.jpeg
[roksprocket]: ../../plugins/roksprocket/
[gallery]: http://www.rockettheme.com/wordpress-downloads/plugins/club/2837-rokgallery
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[showcase]: demo_showcase.md
[feature]: demo_feature.md
[sidebar]: demo_sidebar.md
[footer]: demo_footer.md
[header]: demo_header.md
[utility]: demo_utility.md
[maintop]: demo_maintop.md
[bottom]: demo_bottom.md
[top]: demo_top.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md