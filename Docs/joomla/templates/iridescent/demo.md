---
title: Iridescent: Recreating the Demo
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Iridescent can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Iridescent Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----

Like any Gantry template, Iridescent allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][template2]

:   1. **Slideshow - RokSprocket (Features)**  [8%, 16%, se]
    2. **Top A - Custom HTML**  [29%, 16%, se]
    3. **Tob B - Custom HTML**  [29%, 40%, se]
    4. **Top C - Custom HTML**  [29%, 63%, se]
    5. **Showcase A - RokSprocket (Features)**  [40%, 16%, se]
    6. **Feature A - RokSprocket (Strips)**  [61%, 16%, se]
    7. **Utility A - Custom HTML**  [68%, 16%, se]
    8. **Utility B - Custom HTML**  [68%, 51%, se]
    9. **Bottom A - Custom HTML**  [83%, 16%, se]
    10. **Bottom B - Custom HTML**  [83%, 40%, se]
    11. **Bottom C - Custom HTML**  [83%, 62%, se]
    12. **Footer A - Menu** [90%, 35%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Slideshow - RokSprocket (Features)](demo_module_1.md)
2. [Top A - Custom HTML](demo_module_2.md)
3. [Tob B - Custom HTML](demo_module_3.md)
4. [Top C - Custom HTML](demo_module_4.md)
5. [Showcase A - RokSprocket (Features)](demo_module_5.md)
6. [Feature A - RokSprocket (Strips)](demo_module_6.md)
7. [Utility A - Custom HTML](demo_module_7.md)
8. [Utility B - Custom HTML](demo_module_8.md)
9. [Bottom A - Custom HTML](demo_module_9.md)
10. [Bottom B - Custom HTML](demo_module_10.md)
11. [Bottom C - Custom HTML](demo_module_11.md)
12. [Footer A - Menu](demo_module_12.md)

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Iridescent:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Iridescent RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Iridescent demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Iridescent demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Iridescent - Home** as it would be used only for the front page of your site.

Animation
-----

The animated elements that trigger as you scroll down the page are handled via classes applied to modules. These classes are either included in the **Module Class Suffix** or in-line in the content.

You can find a visual example as well as the class names of classes that are supported by Iridescent [on the Animate.css project site][animation].

The element that triggers this animation during scrolling is explained in greater detail in the [WOW.js Documentation][animation2].

Menu Settings
-----

![Main Menu](assets/menu_1.jpeg)

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to ` rt-iridescent-style`. 

>> NOTE: There is a space before the page class.

RokSprocket and RocketLauncher Settings
------

Some aspects of the RokSprocket demo content in the Slideshow position are hard-coded in the **demo.less** file. This includes images for the following modules:

* [Slideshow - RokSprocket (Features)](demo_module_1.md)

If you wish to use custom images for these modules, you can do so by either switching the **Demo Style** setting in the **Template Settings** to **Custom** or remove the **fp-presets-images** suffix from the **Module Class Suffix** field in the module's **Advanced** settings. 

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

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[template2]: assets/iridescent2.jpeg
[demooverride]: demo_override.md
[template]: assets/iridescent.jpeg
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[article]: assets/article.jpg
[demo11]: assets/demo_10.jpeg
[mobile]: assets/mobilemenu.jpeg
[mobile2]: mobilemenu.md
[sidepanelmodule]: demo_module_10.md
[sidepanel]: assets/sidepanel.jpeg
[animation]: http://daneden.github.io/animate.css/
[animation2]: http://mynameismatthieu.com/WOW/docs.html
