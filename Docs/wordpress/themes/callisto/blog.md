---
title: Callisto: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

## Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Callisto template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Text** widgets.

## Layout Manager

![Layout Manager](assets/layout_blog.png)

This is a look at the **Layout Manager** for the **Callisto - Pages - Blog** outline. We have detailed the various particles represented here in the sections below.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_blog.jpeg)

:   1. **Header - Logo** [5%, 15%, se]
    2. **Header - Icon Menu** [5%, 55%, se]
    3. **Navigation - Menu** [7%, 15%, se]
    4. **Navigation - Social** [7%, 75%, se]
    5. **Showcase - Custom HTML** [9%, 40%, se]
    6. **Mainbar - Page Content** [11%, 15%, se]
    7. **Sidebar - Custom HTML** [11%, 63%, se]
    8. **Sidebar - Widget Position (sidebar-a)** [18%, 63%, se]
    9. **Sidebar - Widget Position (sidebar-b)** [31%, 63%, se]
    7. **Extension - Custom HTML** [84%, 30%, se]
    8. **Footer - Custom HTML** [88%, 15%, se]
    9. **Footer - Newsletter** [88%, 38%, se]
    10. **Footer - Custom HTML - Copyright** [88%, 65%, se]
    11. **Copyright - Copyright** [92%, 40%, se]

1. [Header](#header-section)
2. [Navigation](#navigation-section)
3. [Showcase](#showcase-section)
4. [Mainbar](#mainbar-section)
5. [Sidebar](#sidebar-section)
5. [Extension](#extension-section)
6. [Footer](#footer-section)
7. [Copyright](#copyright-section)

## Header Section

![](assets/page_aboutus_1.jpeg)

:   1. **Logo (Particle)** [40%, 5%, se]
    2. **Icon Menu (Particle)** [40%, 60%, se]

The **Header** section is made up of a position and two particles set in two rows. The first row hosts the **System Messages** position which remains invisible unless a system message is being displayed to the visitor.

In the second row, we have a **Logo** particle and an **Icon Menu** particle which make up the visual body of this area of the site. Settings used in our demo for each of these particles can be found below.

### Logo (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Logo`     |
| URL           | Blank      |
| Image         | Custom     |
| Text          | `Callisto` |
| CSS Classes   | `g-logo`   |

#### Block Settings

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `g-logo-block` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `56%`          |

### Icon Menu (Particle)

#### Particle Settings

| Field                  | Setting          |
| :-----                 | :-----           |
| CSS Classes            | Blank            |
| Target                 | Self             |
| Icon Menu Item 1 Title | `Features`       |
| Icon Menu Item 1 Icon  | `fa fa-diamond`  |
| Icon Menu Item 1 Text  | `Features`       |
| Icon Menu Item 1 Link  | `#`              |
| Icon Menu Item 2 Title | `Gantry 5`       |
| Icon Menu Item 2 Icon  | `fa fa-rocket`   |
| Icon Menu Item 2 Text  | `Gantry 5`       |
| Icon Menu Item 2 Link  | `#`              |
| Icon Menu Item 3 Title | `Addons`         |
| Icon Menu Item 3 Icon  | `fa fa-gear`     |
| Icon Menu Item 3 Text  | `Addons`         |
| Icon Menu Item 3 Link  | `#`              |
| Icon Menu Item 4 Title | `Download`       |
| Icon Menu Item 4 Icon  | `fa fa-download` |
| Icon Menu Item 4 Text  | `Download`       |
| Icon Menu Item 4 Link  | `#`              |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | `flush` |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `44%`   |

## Navigation Section

![](assets/page_aboutus_2.jpeg)

:   1. **Menu (Particle)** [40%, 5%, se]
    2. **Social** [40%, 85%, se]

The **Navigation** section is made up of two particles. The first is a **Menu** particle which displays a CMS-sourced menu which can be enhanced through Gantry's **Menu Editor**. The second particle in the section is the **Social** particle, displaying social links.

Settings used in our demo for each of these particles can be found below.

### Menu (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Menu`  |
| Base Path     | `/`     |
| Menu          | Custom  |
| Start Level   | `1`     |
| Max Levels    | `0`     |

#### Block Settings

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `g-menu-block` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `80%`          |

### Social (Particle)

#### Particle Settings

| Field               | Setting                                          |
| :-----              | :-----                                           |
| Title               | Social                                           |
| CSS Classes         | `social-items`                                   |
| Social Items        | `Features`                                       |
| Social Item 1 Title | `Twitter`                                        |
| Social Item 1 Icon  | `fa fa-twitter fa-fw`                            |
| Social Item 1 Text  | Blank                                            |
| Social Item 1 Link  | `http://twitter.com/rockettheme`                 |
| Social Item 2 Title | `Facebook`                                       |
| Social Item 2 Icon  | `fa fa-facebook fa-fw`                           |
| Social Item 2 Text  | Blank                                            |
| Social Item 2 Link  | `http://facebook.com/rockettheme`                |
| Social Item 3 Title | `Google`                                         |
| Social Item 3 Icon  | `fa fa-google fa-fw`                             |
| Social Item 3 Text  | Blank                                            |
| Social Item 3 Link  | `http://plus.google.com/+rockettheme`            |
| Social Item 4 Title | `RSS`                                            |
| Social Item 4 Icon  | `fa fa-rss fa-fw`                                |
| Social Item 4 Text  | Blank                                            |
| Social Item 4 Link  | `http://www.rockettheme.com/product-updates?rss` |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `20%`   |

## Showcase Section

![](assets/page_blog_1.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Custom HTML` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Our Blog</h2>
    <div class="g-layercontent-subtitle">Read the Latest News</div>
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | Blank           |
| Tag Attributes | Blank           |
| Block Size     | `100%`          |

## Mainbar Section

![](assets/page_blog_2.jpeg)

The **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Page Content

#### Particle Settings

| Field         | Setting        |
| :-----        | :-----         |
| Particle Name | `Page Content` |

#### Block Settings

| Field          | Setting       |
| :-----         | :-----        |
| CSS ID         | Blank         |
| CSS Classes    | `nomarginall` |
| Variations     | `Box 2`       |
| Tag Attributes | Blank         |
| Block Size     | `100%`        |

## Sidebar Section

![](assets/page_blog_3.jpeg)

:   1. **Custom HTML** [5%, 15%, se]
    2. **Widget Position (sidebar-a)** [27%, 15%, se]
    3. **Widget Position (sidebar-b)** [65%, 15%, se]
    4. **Widget Position (sidebar-c)** [85%, 15%, se]

The **Sidebar** section is set to `33`% width.

Settings used in our demo for each of these particles can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting           |
| :-----        | :-----            |
| Particle Name | `Gantry 5 Guides` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Gantry 5 Guides</h2>
<ul>
    <li><a href="http://docs.gantry.org/gantry5/basics/installation">Installation</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/gantry-admin">Gantry Admin Configuration</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/styles">Template Styles</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/settings">Template Settings Panel</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/layout-manager">Layout Manager</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/menu-editor">Menu Editor</a></li>
    <li><a href="http://docs.gantry.org/gantry5/configure/assignments">Assignments</a></li>
    <li><a href="http://docs.gantry.org/gantry5/particles/particles">Gantry Particles</a></li>
    <li><a href="http://docs.gantry.org/gantry5/particles/mobile-menu">Mobile Menu</a></li>
    <li><a href="http://docs.gantry.org/gantry5/advanced">Advanced Customizaton</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box Blue` |
| Tag Attributes | Blank      |
| Block Size     | `100%`     |

### Widget Position (sidebar-a)

#### Particle Settings

| Field         | Setting            |
| :-----        | :-----             |
| Particle Name | `Main Menu Widget` |
| Key           | `sidebar-a`        |
| Chrome        | gantry             |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

#### Assigned Widget(s)

The only widget assigned to the `sidebar-a` position is a **Widget Menu** widget. You will find the settings used in this widget listed below.

##### Widget Options

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Main Menu` |

### Widget Position (sidebar-b)

#### Particle Settings

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Site Meta` |
| Key           | `sidebar-b` |
| Chrome        | gantry      |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 2` |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

#### Assigned Widget(s)

The only widget assigned to the `sidebar-b` position is a **Meta** widget. You will find the settings used in this widget listed below.

##### Details

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Site Meta` |

## Extension Section

![](assets/page_blog_4.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Custom HTML` |

**Custom HTML**
~~~ .html
<div class="g-layercontent">
    <h2 class="g-layercontent-title">Share Some Idea</h2>
    <div class="g-layercontent-subtitle">Do You Have a Tip or an Idea for a Story? Tell Us About It.</div>
    <a href="#" class="button button-2">Submit Article</a>
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | `Box 1`         |
| Tag Attributes | Blank           |
| Block Size     | `100%`          |

## Footer Section

![](assets/page_aboutus_6.jpeg)

:   1. **Custom HTML 1** [30%, 5%, se]
    2. **Newsletter** [30%, 38%, se]
    3. **Custom HTML 2** [30%, 70%, se]

The **Footer** section is made up of three particles in a single row. This includes a **Newsletter** particle surrounded by two **Custom HTML** particles.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting          |
| :-----        | :-----           |
| Particle Name | `About Callisto` |

**Custom HTML**
~~~ .html
<h2 class="g-title">About Callisto</h2>

<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Callisto can be constructed on your site.</p>
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | Blank            |
| Variations     | Blank            |
| Tag Attributes | Blank            |
| Block Size     | `33.3333333333%` |

### Newsletter (Particle)

#### Particle Settings

| Field          | Setting           |
| :-----         | :-----            |
| Particle Name  | `Newsletter`      |
| CSS Classes    | Blank             |
| Title          | `Newsletter`      |
| Feedburner URI | `rocketthemeblog` |

**Heading Text**
~~~ .html
Subscribe to our newsletter and stay updated on the latest developments and special offers!
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | `flush, center`  |
| Variations     | `Box 1`          |
| Tag Attributes | Blank            |
| Block Size     | `33.3333666666%` |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting          |
| :-----        | :-----           |
| Particle Name | `Simple Sitemap` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Sample Sitemap</h2>

<div class="g-grid">
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="#">Home</a></li>
            <li><a href="#">Features</a></li>
            <li><a href="#">Typography</a></li>
            <li><a href="#">Particles</a></li>
            <li><a href="#">Variations</a></li>
        </ul>       
    </div>
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="#">Buttons</a></li>
            <li><a href="#">Pages</a></li>
            <li><a href="#">Guide</a></li>
            <li><a href="#">Support</a></li>
            <li><a href="#">Download</a></li>
        </ul>       
    </div>  
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | `Box 1`         |
| Tag Attributes | Blank           |
| Block Size     | `33.3333%`      |

## Copyright Section

![](assets/page_aboutus_7.jpeg)

The **Copyright** section contains a single **Copyright** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field           | Setting            |
| :-----          | :-----             |
| Particle Name   | `Copyright`        |
| Start Year      | `2007`             |
| End Year        | Now                |
| Copyright Owner | `RocketTheme, LLC` |

#### Block Settings

| Field          | Setting  |
| :-----         | :-----   |
| CSS ID         | Blank    |
| CSS Classes    | `center` |
| Variations     | Blank    |
| Tag Attributes | Blank    |
| Block Size     | `100%`   |
