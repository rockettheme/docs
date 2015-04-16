---
title: Audacity: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Audacity Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/audacity:Audacity

---

Main Top Section
-----

![Feature](assets/demo_4.jpeg)

:   1. **RokSprocket (Features)** [9%, 7%, se]
    2. **Text** [67%, 7%, se]
    3. **RokSprocket (Tabs)** [9%, 73%, se]

Here is the widget breakdown for the Main Top section:

* [RokSprocket (Features)](#roksprocket-(features))
* [Text](#text)
* [Gantry Divider](#gantry-divider)
* [RokSprocket (Tabs)](#roksprocket-(tabs))

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option | Setting |
| :----- | :-----  |
| Image  | Custom  |
| Link   | Custom  |

**Title**

~~~ .html
<span class="rt-displayinline"><span class="visible-desktop">The </span>Gantry<span class="visible-desktop"> Framework provides</span><span class="hidden-desktop">,</span> a powerful foundation</span>
~~~

**Description**

~~~ .html
<p><span class="rt-displayinline">Gantry is a cross-platform framework with a vast library of standardized features and functions<span class="visible-desktop">, to make powerful, flexible themes</span>.</span></p><p class="visible-large">Themes are easy to manage with Gantry, with its a rich and intuitive user interface, allowing for swift but extensive customization.</p>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting        |
| :--------------- | :------------- |
| Display Limit    | ∞              |
| Theme            | Showcase       |
| Article Titles   | Show           |
| Article Text     | Show           |
| Preview Length   | ∞              |
| Strip HTML Tags  | No             |
| Arrow Navigation | Hide           |
| Pagination       | Show           |
| Animation        | Crossfade      |
| Autoplay         | Disable        |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

| Option            | Setting                                          |
| :---------------- | :----------------------------------------------- |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Widget Variations | Box 1                                            |
| Custom Variations | `fp-roksprocket-showcase-maintop`                |

Leaving everything else at its default setting, select **Save**.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-img-wrapper">
                <img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-maintop/img-01.jpg" alt="image" />
                <span class="rt-icon-tag"><i class="fa fa-camera"></i></span>
            </div>
            <p>A versatile, content switchblade plugin with a rich UI <span><a class="learnmore" href="#">Learn More</a></span></p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-img-wrapper">
                <img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-maintop/img-02.jpg" alt="image" />
                <span class="rt-icon-tag"><i class="fa fa-database"></i></span>
            </div>
            <p>A powerful cross-platform framework with various features <span><a class="learnmore" href="#">Learn More</a></span></p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-img-wrapper">
                <img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-maintop/img-03.jpg" alt="image" />
                <span class="rt-icon-tag"><i class="fa fa-car"></i></span>
            </div>
            <p>Menus with advanced features such as multiple columns <span><a class="learnmore" href="#">Learn More</a></span></p>
        </div>
    </div>      
    <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting        |
| :---------------- | :---------     |
| Custom Variations | `fp-maintop-a` |

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket Tabs

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label**, **Link**, and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

| Option    | Setting |
| :-----    | :-----  |
| Tab Label | `Top`   |
| Icon      | None    |
| Link      | Custom  |

*Description*

~~~ .html
<div>
    <img alt="image" src=
    "http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-feature/img-03.jpg">

    <h2 class="title"><span><span class="hidden-tablet">Media Presentation
    with</span> RokBox</span></h2>

    <p class="rt-title-tag">Modal</p>

    <p><span>Present HTML DOM, videos from Y<span class=
    "hidden-tablet">ou</span>T<span class="hidden-tablet">ube</span>, Maps and
    Images.</span></p>
</div>
<hr>

<div>
    <img alt="image" src=
    "http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-feature/img-04.jpg">

    <h2 class="title"><span>R<span class=
    "hidden-tablet">ight-</span>T<span class=
    "hidden-tablet">o-</span>L<span class="hidden-tablet">eft Gantry &amp;
    Theme</span> Support</span></h2>

    <p class="rt-title-tag">Multi-Language</p>

    <p><span>Audacity has basic <span class="hidden-tablet">structural</span>
    support for Right-To-Left <span class=
    "visible-large">languages</span>.</span></p>
</div>
~~~

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Display Limit   | ∞              |
| Tabs Position   | Top            |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | 0              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

|       Option      |                     Setting                      |
| :---------------- | :----------------------------------------------- |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Custom Variations | `fp-roksprocket-tabs-maintop`                  |

Leaving everything else at its default setting, select **Save**.