---
title: Myriad: Recreating the Demo
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Myriad can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Myriad Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][template2]

:   1. **Slideshow - RokSprocket (Features)**  [8%, 16%, se]
    2. **FullStrip - RokSprocket (Strips)**  [23%, 16%, se]
    3. **FirstFullWidth - RokSprocket (Features)**  [32%, 16%, se]
    4. **Feature A - Custom HTML**  [45%, 16%, se]
    5. **Feature B - Custom HTML**  [45%, 50%, se]
    6. **Utility A - Custom HTML**  [57%, 40%, se]
    7. **SecondFullWidth - RokSprocket (Strips)**  [59%, 16%, se]
    8. **Main Top A - Custom HTML**  [69%, 40%, se]
    9. **MainBody**  [71%, 16%, se]
    10. **Sidebar A - RokSprocket (Lists)**  [71%, 60%, se]
    11. **Extension A - Custom HTML**  [80%, 40%, se]
    12. **Bottom A - Custom HTML** [86%, 16%, se]
    13. **Bottom B - Custom HTML** [86%, 40%, se]
    14. **Bottom C - Custom HTML** [86%, 60%, se]
    15. **Footer A - Menu** [91%, 35%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Slideshow - RokSprocket (Features)](demo_module_1.md)
2. [FullStrip - RokSprocket (Strips)](demo_module_2.md)
3. [FirstFullWidth - RokSprocket (Features)](demo_module_3.md)
4. [Feature A - Custom HTML](demo_module_4.md)
5. [Feature B - Custom HTML](demo_module_5.md)
6. [Utility A - Custom HTML](demo_module_6.md)
7. [SecondFullWidth - RokSprocket (Strips)](demo_module_7.md)
8. [Main Top A - Custom HTML](demo_module_8.md)
9. [MainBody](demo_module_9.md)
10. [Sidebar A - RokSprocket (Lists)](demo_module_10.md)
11. [Extension A - Custom HTML](demo_module_11.md)
12. [Bottom A - Custom HTML](demo_module_12.md)
13. [Bottom B - Custom HTML](demo_module_13.md)
14. [Bottom C - Custom HTML](demo_module_14.md)
15. [Footer A - Menu](demo_module_15.md)

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Myriad:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Myriad RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Myriad demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Myriad demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Myriad - Home** as it would be used only for the front page of your site.

Animation
-----

The animated elements that trigger as you scroll down the page are handled via classes applied to modules. These classes are either included in the **Module Class Suffix** or in-line in the content.

You can find a visual example as well as the class names of classes that are supported by Myriad [on the Animate.css project site][animation].

The element that triggers this animation during scrolling is explained in greater detail in the [WOW.js Documentation][animation2].

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You can find these settings by navigating to **Admin > Menus > Main Menu > Home**. Once there, you will want to select the **Page Display** tab.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to ` rt-myriad-style`. 

>> NOTE: There is a space before the page class.

RokBooster Settings
-----

In order for the sample content to appear properly in conjunction with RokBooster, we added a set of exceptions to RokBooster, which can be entered by navigating to **Administrator > Extensions > Plugin Manager > System - RokBooster > Advanced** and entering the following in the **Ignored Files** field.

~~~ .html
/media/editors/tinymce/jscripts/tiny_mce/tiny_mce.js
/images/rocketlauncher/home/fp-fullstrip/img-01.jpg
/images/rocketlauncher/home/fp-fullstrip/img-02.jpg
/images/rocketlauncher/home/fp-fullstrip/img-03.jpg
/images/rocketlauncher/home/fp-fullstrip/img-04.jpg
/images/rocketlauncher/home/fp-fullstrip/img-05.jpg
/templates/rt_myriad/roksprocket/layouts/strips/themes/apollo/apollo.css
~~~

RokSprocket and RocketLauncher Settings
------

Some aspects of the RokSprocket demo content in the Slideshow position are hard-coded in the **demo.less** file. This includes images for the following modules:

* [Slideshow - RokSprocket (Features)](demo_module_1.md)
* [FullStrip - RokSprocket (Strips)](demo_module_2.md)
* [FirstFullWidth - RokSprocket (Features)](demo_module_3.md)

If you wish to use custom images for these modules, you can do so by either switching the **Demo Style** setting in the **Template Settings** to **Custom** or remove the **fp-presets-images** suffix from the **Module Class Suffix** field in the module's **Advanced** settings. 

To switch the **Demo Style** setting, you will need to navigate to **Administration -> Template Manager -> Myriad Template** and selecting the **Style** tab. By default, this setting will be set to the preset selected. By switching this option to **Custom** it will ignore the preset settings for the RokSprocket module found in **Demo.less**.

For reference, and in the event that you wish to modify this code to meet your individual needs, here is the section of the demo.less file that sets this behavior.

~~~ .css
// Demo Preset Images
.demostyleImage(@index) when (@index > 0) {
    (~".demostyle-type-preset@{index}") {
        .fp-preset-images {
            &.fp-slideshow .sprocket-features-index-1 .sprocket-features-img-container.sprocket-fullslideshow-image {
                background-image: url(../../../images/rocketlauncher/home/fp-slideshow/img-01-preset-@{index}.jpg) !important;
                background-position: center;
            }

            &.fp-roksprocket-strips-fullstrip {
                .sprocket-strips-apollo-item {
                    img {
                        background-size: 100%;
                    }
                    img[src$="img-01.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-01-preset-@{index}.jpg);
                    }
                    img[src$="img-02.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-02-preset-@{index}.jpg);
                    }
                    img[src$="img-03.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-03-preset-@{index}.jpg);
                    }
                    img[src$="img-04.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-04-preset-@{index}.jpg);
                    }
                    img[src$="img-05.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-05-preset-@{index}.jpg);
                    }
                    img[src$="img-06.jpg"] {
                        background-image: url(../../../images/rocketlauncher/home/fp-fullstrip/img-06-preset-@{index}.jpg);
                    }
                }
            }

            &.fp-roksprocket-slideshow-firstfullwidth .sprocket-features-index-1 .sprocket-features-img-container img {
                background-image: url(../../../images/rocketlauncher/home/fp-firstfullwidth/img-01-preset-@{index}.jpg) !important;
                background-position: center;
            }
        }
    }
    .demostyleImage(@index - 1);
}
.demostyleImage(6);
.demostyle-type-preset4 .fp-preset-images.fp-roksprocket-slideshow-firstfullwidth .sprocket-features-index-1 .sprocket-features-img-container img {
    background-position: top left;
}
~~~

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[template2]: assets/myriad2.jpeg
[demooverride]: demo_override.md
[template]: assets/myriad.jpeg
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[module16]: demo_module_16.md
[module17]: demo_module_17.md
[module18]: demo_module_18.md
[module19]: demo_module_19.md
[module20]: demo_module_20.md
[module21]: demo_module_21.md
[module22]: demo_module_22.md
[module23]: demo_module_23.md
[mainmenu]: assets/menu_1.jpeg
[article]: assets/article.jpg
[demo11]: assets/demo_10.jpeg
[mobile]: assets/mobilemenu.jpeg
[mobile2]: mobilemenu.md
[sidepanelmodule]: demo_module_10.md
[sidepanel]: assets/sidepanel.jpeg
[animation]: http://daneden.github.io/animate.css/
[animation2]: http://mynameismatthieu.com/WOW/docs.html
