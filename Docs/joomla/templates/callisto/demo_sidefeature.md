---
title: Callisto: Recreating the Demo - Sidefeature Section
description: Your Guide to Recreating Elements of the Callisto Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/callisto:Callisto

---

## Introduction

![](assets/demo_sidebar_1.jpeg)

:   1. **Sidefeature A - RokAjaxSearch** [10%, 13%, se]
    2. **Sidefeature B - RokSProcket (Tabs)** [33%, 13%, se]

The **Sidefeature** section sits side-by-side with the **Mainfeature** section in the **Layout Manager**. It is set to take up `33%` of the total width of the page, and each **Particle** or **Module Position** will take up the full 33% if set to `100%` width, individually.

The **Sidefeature** section is made up of two **Module Positions**. These positions, once placed and set up in the **Layout Manager** make it possible to assign Modules to them that appear on your site.

![](assets/demo_mainfeature_lm.jpeg)

Settings used in our demo for each of these particles can be found below.

## Section Settings

![](assets/demo_sidebar_settings.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS Classes    | Blank   |
| Tag Attributes | Blank   |

## Module Position (sidefeature-a)

### Particle Settings

![](assets/demo_sidebar_2.jpeg)

| Field         | Setting                    |
| :-----        | :-----                     |
| Particle Name | `Position - RokAjaxSearch` |
| Key           | `sidefeature-a`            |
| Chrome        | `gantry`                   |

### Block Settings

![](assets/demo_sidebar_3.jpeg)

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | Blank            |
| Variations     | `Box 1, Rounded` |
| Tag Attributes | Blank            |
| Block Size     | `100%`           |

## Assigned Module(s)

The `sidefeature-a` module position is host to a single **RokAjaxSearch** module that allows visitors to search your site using the powerful RokAjaxSearch tool.

### Details

![](assets/demo_sidebar_4.jpeg)

| Option      | Setting           |
| :---------- | :----------       |
| Title       | `Search Our Site` |
| Show Title  | Show              |
| Position    | sidefeature-a     |
| Status      | Published         |
| Access      | Public            |

### Module

![](assets/demo_sidebar_6.jpeg)

| Option                            | Setting                                                  |
| :----------                       | :----------                                              |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

### Advanced

![](assets/demo_sidebar_5.jpeg)

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

## Module Position (sidefeature-b)

### Particle Settings

![](assets/demo_sidebar_7.jpeg)

| Field         | Setting                       |
| :-----        | :-----                        |
| Particle Name | `Position - RokSprocket Tabs` |
| Key           | `sidefeature-b`               |
| Chrome        | `gantry`                      |

### Block Settings

![](assets/demo_sidebar_8.jpeg)

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `nopaddingall` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `100%`         |

## Assigned Module(s)

This area of the page is a **RokSprocket** module utilizing the **Simple** content provider and the **Tabs** layout.

The settings used in our demo are listed below.

### Details

![](assets/demo_sidebar_9.jpeg)

| Option           | Setting               |
| :--------------- | :-------------------- |
| Title            | `FP RokSprocket Tabs` |
| Show Title       | Hide                  |
| Access           | Public                |
| Position         | `sidefeature-a`       |
| Status           | Published             |
| Content Provider | Simple                |
| Layout Mode      | Tabs                  |

### Simple Content Provider

The **Tab Label** and **Description** fields in each item have been altered. A couple examples of these article changes can be found below.

#### Article 1

| Option    | Setting |
| :-----    | :-----  |
| Tab Label | `Guide` |
| Icon      | None    |
| Link      | None    |

**Description**

~~~ .html
<div class="g-infolist">
    <div class="g-infolist-item g-infolist-with-img">
        <div class="g-infolist-item-img g-block size-22 hidden-phone"><img alt=
        "image" src=
        "templates/rt_callisto/images/demo/home/feature/roksprocket-tabs/img-01.jpg"></div>

        <div class="g-infolist-item-text g-block size-68">
            <div class="g-infolist-item-title">
                <a href="http://docs.gantry.org"><span>Introduce yourself to
                the <span class="visible-large">new and</span> <span class=
                "hidden-tablet">powerful</span> Gantry 5 Framework</span></a>
            </div>

            <div class="g-infolist-item-desc">
                <span>Gantry benefits from an extensive, and ever expanding,
                catalog of online and freely available documentation covering
                basic to <span class="hidden-tablet">more</span> advanced
                topics.</span>
            </div>
        </div>
    </div>

    <div class="g-infolist-item g-infolist-with-img">
        <div class="g-infolist-item-img g-block size-22 hidden-phone"><img alt=
        "image" src=
        "templates/rt_callisto/images/demo/home/feature/roksprocket-tabs/img-02.jpg"></div>

        <div class="g-infolist-item-text g-block size-68">
            <div class="g-infolist-item-title">
                <a href="http://www.rockettheme.com/docs"><span>Template
                <span class="hidden-tablet">specific</span> help guides to
                assist in <span class="visible-large">installation,</span>
                setup and <span class="visible-tablet">use</span><span class=
                "hidden-tablet">configuration</span></span></a>
            </div>

            <div class="g-infolist-item-desc">
                <span>The RocketTheme site provides free documentation for all
                our templates and extensions, to supplement understanding
                <span class="visible-large">of their various features and
                capabilities</span>.</span>
            </div>
        </div>
    </div>
</div>
~~~

#### Article 2

| Option    | Setting   |
| :-----    | :-----    |
| Tab Label | `Support` |
| Icon      | None      |
| Link      | None      |

**Description**

~~~ .html
<div class="g-infolist">
    <div class="g-infolist-item g-infolist-with-img">
        <div class="g-infolist-item-img g-block size-22 hidden-phone"><img alt=
        "image" src=
        "templates/rt_callisto/images/demo/home/feature/roksprocket-tabs/img-03.jpg"></div>

        <div class="g-infolist-item-text g-block size-68">
            <div class="g-infolist-item-title">
                <a href="http://www.rockettheme.com/forum"><span>A <span class=
                "hidden-tablet">community</span> forum to ask the <span class=
                "visible-large">moderators and</span> developers
                questions</span></a>
            </div>

            <div class="g-infolist-item-desc">
                Our forums are monitored by a team of moderators, as well as
                the developers, to assist in general questions and problems
                relating to the templates and extensions.
            </div>
        </div>
    </div>

    <div class="g-infolist-item g-infolist-with-img">
        <div class="g-infolist-item-img g-block size-22 hidden-phone"><img alt=
        "image" src=
        "templates/rt_callisto/images/demo/home/feature/roksprocket-tabs/img-04.jpg"></div>

        <div class="g-infolist-item-text g-block size-68">
            <div class="g-infolist-item-title">
                <a href="https://github.com/gantry/">Gantry is community driven
                <span class="visible-large">and offers direct chat via
                Gitter</span></a>
            </div>

            <div class="g-infolist-item-desc">
                Github allows for an system where you can contribute code, post
                issues and feedback on the Gantry open source project.
                <span class="hidden-tablet">Discuss Gantry live with us via
                Gitter.</span>
            </div>
        </div>
    </div>
</div>
~~~

### Layout Options

![](assets/demo_sidebar_10.jpeg)

| Option                | Setting               |
| :-------------------- | :-------------------- |
| Theme                 | Default               |
| Display Limit         | `∞`                   |
| Tabs Position         | Top                   |
| Animation             | Slide and Fade        |
| Autoplay              | Disable               |
| Autoplay Delay        | `5`                   |
| Image Resize          | Disable               |
| Preview Length        | `0`                   |
| Strip HTML Tags       | No                    |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

### Advanced

![](assets/demo_sidebar_11.jpeg)

| Option              | Setting               |
| :------------------ | :-------------------- |
| Module Class Suffix |                       |
