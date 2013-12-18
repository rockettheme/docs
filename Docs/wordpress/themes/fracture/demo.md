---
title: Fracture: Recreating the Demo
description: Your Guide to Recreating Elements of the Fracture Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/fracture:Fracture

---

Introduction
-----

![][Fracture]

Recreating features of the demo site used to show off some of the more interesting aspects of Fracture can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Fracture theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Fracture:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokGallery][rokgallery]
* [RokSprocket][roksprocket]

All of these plugins are included with the Fracture RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Fracture demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the blog. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Fracture theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Fracture Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Advanced
We do not display any pages or posts on the front page of our demo, except through RokSprocket widgets. Because of this, we will need to cancel out the main content area while preserving our sidebar positions. To do this, you will want to select the **Display Content** field and turn this off.

#### Assignments
The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **theme Page Types** list, you will want to select both **Home Page** and **Front Page**.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][theme]

:   1. **Navigation - Gantry Logo** [6%, 13%, se]
	2. **Navigation - Gantry Menu** [6%, 53%, se]
	3. **Slideshow - RokSprocket**  [12%, 11%, se]
    4. **Feature - Text**  [31%, 11%, se]
    5. **Utility - Text**  [40%, 11%, se]
    6. **Utility - RokSprocket**  [45%, 11%, se]
    7. **Footer - Text**  [76%, 11%, se]
  	8. **Footer - Text**  [76%, 38%, se]
    9. **Footer - Text**  [76%, 65%, se]
    10. **Copyright - Gantry Copyright** [91%, 11%, se]
    11. **Copyright - Gantry Social Buttons** [91%, 32%, se]
    12. **Copyright - Gantry To Top** [91%, 66%, se]

Like any Gantry theme, Fracture utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Navigation][navigation]
* [Slideshow][slideshow]
* [Feature][feature]
* [Sidebar][sidebar]
* [Utility][utility]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2624-rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress-downloads/plugins/free/2625-rokbox
[roksprocket]: http://www.rockettheme.com/wordpress-downloads/plugins/free/3228-roksprocket
[fracture]: assets/wp_fracture.jpg
[roksprocket]: http://www.rockettheme.com/extensions-joomla/roksprocket
[rokgallery]: http://www.rockettheme.com/extensions-joomla/rokgallery
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[navigation]: demo_navigation.md
[slideshow]: demo_showcase.md
[feature]: demo_feature.md
[sidebar]: demo_slideshow.md
[utility]: demo_utility.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md
[theme]: assets/fracture2.jpg