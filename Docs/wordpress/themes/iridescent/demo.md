---
title: Iridescent: Recreating the Demo
description: Your Guide to Recreating Elements of the Iridescent Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/iridescent:Iridescent

---

Introduction
-----

![Iridescent](assets/iridescent.jpeg)

Recreating features of the demo site used to show off some of the more interesting aspects of Iridescent can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Iridescent theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Iridescent:

* [Gantry Framework](http://gantry-framework.org/download)
* [RokAjaxSearch](http://www.rockettheme.com/wordpress/plugins/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/wordpress/plugins/rokbox)
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket](../../plugins/roksprocket/)

All of these plugins are included with the Iridescent RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Iridescent demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Iridescent theme.

For the front page, we used a **Page Suffix** to load the unique styling for it. You will need to create a **Front Page** override under **Theme Settings**. To get to this page, navigate to **Admin > Iridescent Settings**. Once you have done that, simply select the **Gizmos** panel (tab) and enter the following in the **Page Suffix** field: `rt-menu-home -rt-iridescent-style`. 

Once this is done, you will need to assign the **Front Page** override to the page. You can find more details about this [assignment here](demo_override.md#assignments).

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Iridescent Theme** and selecting the **+** icon located just above the **Style** settings tab.

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the page you wish to use as the home page. Under the **Template Page Types** list, you will want to select your desired page.

Doing this will assign the override to this page. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion](demo_override.md) of this tutorial.

Widget Settings
-----

![Theme](assets/iridescent2.jpeg)

:   1. **Header - Gantry Logo** [5%, 15%, se]
    2. **Header - Gantry Menu** [5%, 60%, se]
    3. **Slideshow - RokSprocket (Features)**  [8%, 16%, se]
    4. **Top - Text**  [29%, 16%, se]
    5. **Top - Text**  [29%, 40%, se]
    6. **Top - Text**  [29%, 63%, se]
    7. **Showcase - RokSprocket (Features)**  [40%, 16%, se]
    8. **Feature - RokSprocket (Strips)**  [61%, 16%, se]
    9. **Utility - Text** [68%, 16%, se]
    10. **Utility - Text** [68%, 51%, se]
    11. **Bottom - Text** [83%, 16%, se]
    12. **Bottom - Text** [83%, 40%, se]
    13. **Bottom - Text** [83%, 62%, se]
    14. **Footer - Custom Menu** [90%, 35%, se]
    15. **Copyright - Gantry Branding** [92%, 18%, ne]
    16. **Copyright - Gantry Copyright** [92%, 48%, ne]
    17. **Copyright - Gantry To Top** [92%, 80%, ne]

Like any Gantry theme, Iridescent utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header](demo_header.md)
* [Slideshow](demo_slideshow.md)
* [Top](demo_top.md)
* [Showcase](demo_showcase.md)
* [Feature](demo_feature.md)
* [Utility](demo_utility.md)
* [Bottom](demo_bottom.md)
* [Footer](demo_footer.md)
* [Copyright](demo_copyright.md)

RokSprocket and RocketLauncher Settings
------

Some aspects of the RokSprocket demo content in the Slideshow position are hard-coded in the **demo.less** file. This includes images for the following modules:

* [Slideshow - RokSprocket (Features)](demo_module_1.md)

If you wish to use custom images for these modules, you can do so by either switching the **Demo Style** setting in the **Template Settings** to **Custom** or remove the **fp-preset-images** suffix from the **Module Class Suffix** field in the module's **Advanced** settings. 

To switch the **Demo Style** setting, you will need to navigate to **Administration -> Template Manager -> Iridescent Template** and selecting the **Style** tab. By default, this setting will be set to the preset selected. By switching this option to **Custom** it will ignore the preset settings for the RokSprocket module found in **Demo.less**.

For reference, and in the event that you wish to modify this code to meet your individual needs, here is the section of the demo.less file that sets this behavior.

~~~ .css
// Demo Preset Images
.demostyleImage(@index) when (@index > 0) {
    (~".demostyle-type-preset@{index}") {
        .fp-preset-images {
            &.fp-slideshow .sprocket-features-index-1 .sprocket-features-img-container.sprocket-fullslideshow-image, {
                background-image: url(../../../images/rocketlauncher/home/fp-slideshow/img-01-preset-@{index}.jpg) !important;
                background-position: center;
                background-repeat: no-repeat;
            }
        }
    }
    .demostyleImage(@index - 1);
}
.demostyleImage(6);

// FP Slideshow
.fp-slideshow .layout-fullslideshow {
    .sprocket-features-title {
        font-family: @alt-font-family;
        font-size: 1.75em;
        text-transform: uppercase;
        position: relative;
        // Small Mobile Modes
        @media (max-width: 480px) {
            body.layout-mode-responsive & {
                font-size: 1.25em;
            }
        }
    }
    .sprocket-features-desc {
        font-size: 1.25em;
        color: darken(@header-textcolor, 5%);
        width: 60%;
        margin: 25px auto;
        .readon {
            margin-top: 25px;
        }
        // Tablet Mode
        @media only screen and (min-width: 768px) and (max-width: 959px) {
            body.layout-mode-responsive & {
                width: 80%;
            }
        }
    }
}
~~~
