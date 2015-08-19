---
title: Callisto: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Callisto template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Text** widgets.

## Layout Manager

![Layout Manager](assets/layout_aboutus.jpeg)

This is a look at the **Layout Manager** for the **Callisto - Pages - About Us** outline. We have detailed the various particles represented here in the sections below.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_aboutus.jpeg)

:   1. **Header - Logo** [6%, 9%, se]
    2. **Header - Icon Menu** [6%, 55%, se]
    3. **Navigation - Menu** [9%, 9%, se]
    4. **Navigation - Social** [9%, 83%, se]
    5. **Showcase - Custom HTML** [12%, 45%, se]
    6. **Mainbar - Custom HTML** [18%, 10%, se]
    7. **Mainbar - Custom HTML** [18%, 38%, se]
    8. **Mainbar - Custom HTML** [18%, 65%, se]
    9. **Mainbar - Custom HTML** [29%, 33%, se]
    10. **Mainbar - Custom HTML** [35%, 10%, se]
    11. **Mainbar - Custom HTML** [50%, 10%, se]
    12. **Mainbar - Custom HTML** [50%, 38%, se]
    13. **Mainbar - Custom HTML** [50%, 65%, se]
    14. **Mainbar - Info List** [60%, 10%, se]
    15. **Mainbar - Info List** [60%, 38%, se]
    16. **Mainbar - Info List** [60%, 65%, se]
    17. **Extension - Custom HTML** [70%, 30%, se]
    18. **Footer - Custom HTML** [80%, 10%, se]
    19. **Footer - Newsletter** [80%, 38%, se]
    20. **Footer - Custom HTML** [80%, 65%, se]
    21. **Copyright - Copyright** [90%, 40%, se]

1. [Header](#header-section)
2. [Navigation](#navigation-section)
3. [Showcase](#showcase-section)
4. [Mainbar](#mainbar-section)
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
| Particle Name       | `Social`                                         |
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

![](assets/page_aboutus_3.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field          | Setting    |
| :-----         | :-----     |
| Particle Name | `About Us` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">About Us</h2>
    <div class="g-layercontent-subtitle">Who We Are</div>
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

![](assets/page_aboutus_4.jpeg)

:   1. **Custom HTML 1** [5%, 5%, se]
    2. **Custom HTML 2** [5%, 35%, se]
    3. **Custom HTML 3** [5%, 66%, se]
    4. **Custom HTML 4** [25%, 35%, se]
    5. **Custom HTML 5** [35%, 7%, se]
    6. **Custom HTML 6** [61%, 7%, se]
    7. **Custom HTML 7** [61%, 36%, se]
    8. **Custom HTML 8** [61%, 67%, se]
    9. **Info List 1** [77%, 7%, se]
    10. **Info List 2** [77%, 36%, se]
    11. **Info List 3** [77%, 67%, se]

The **Mainbar** section is made up 11 particles, 8 of which are **Custom HTML** particles, spanning five rows. The Mainbar section itself renders as 100% of the page width as there are no particles or positions assigned to the Sidebar section. With this in mind, the **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Our Mission` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Our Mission</h2>
<p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
~~~

#### Block Settings

| Field          | Setting                 |
| :-----         | :-----                  |
| CSS ID         | Blank                   |
| CSS Classes    | `center, no margin all` |
| Variations     | `Box Blue`              |
| Tag Attributes | Blank                   |
| Block Size     | `33.3333%`              |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field          | Setting      |
| :-----         | :-----       |
| Particle Name | `Our Values` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Our Values</h2>
<p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
~~~

#### Block Settings

| Field          | Setting                 |
| :-----         | :-----                  |
| CSS ID         | Blank                   |
| CSS Classes    | `center, no margin all` |
| Variations     | `Box 1`                 |
| Tag Attributes | Blank                   |
| Block Size     | `33.3333%`              |

### Custom HTML 3 (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `Our Solutions` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Our Solution</h2>
<p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
~~~

#### Block Settings

| Field          | Setting                 |
| :-----         | :-----                  |
| CSS ID         | Blank                   |
| CSS Classes    | `center, no margin all` |
| Variations     | `Box Orange`            |
| Tag Attributes | Blank                   |
| Block Size     | `33.3333%`              |

### Custom HTML 4 (Particle)

#### Particle Settings

| Field         | Setting                  |
| :-----        | :-----                   |
| Particle Name | `Why You Should Join Us` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Why You Should Join Us</h2>
    <div class="g-layercontent-subtitle">Choose the theme that suits your needs. 100% satisfaction guaranteed.</div>
</div>
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | `center, center` |
| Variations     | `Box 2`          |
| Tag Attributes | Blank            |
| Block Size     | `100%`           |

### Custom HTML 5 (Particle)

#### Particle Settings

| Field         | Setting                             |
| :-----        | :-----                              |
| Particle Name | `Introduction - Mission - Business` |

**Custom HTML**
~~~ .html
<div class="g-grid center">
    <div class="g-block">
        <div class="g-content">
          <img src="http://placehold.it/480x320" alt="image">
          <h2 class="g-title">Introduction</h2>
        </div>
    </div>
    <div class="g-block">
        <div class="g-content">
          <img src="http://placehold.it/480x320" alt="image">
          <h2 class="g-title">Mission</h2>
        </div>
    </div>
    <div class="g-block">
        <div class="g-content">
          <img src="http://placehold.it/480x320" alt="image">
          <h2 class="g-title">Business</h2>
        </div>
    </div>
</div>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | `flush` |
| Variations     | `Box 2` |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

### Custom HTML 6 (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `Sophisticated` |

**Custom HTML**
~~~ .html
<h2 class="g-title"><span class="fa fa-dashboard fa-fw fa-3x"></span> Sophiscated</h2>
<p>Dynamically procrastinate B2C users after installed base benefits.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 7 (Particle)

#### Particle Settings

| Field         | Setting      |
| :-----        | :-----       |
| Particle Name | `Responsive` |

**Custom HTML**
~~~ .html
<h2 class="g-title"><span class="fa fa-arrows-alt fa-fw fa-3x"></span> Responsive</h2>
<p>Dynamically procrastinate B2C users after installed base benefits.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 8 (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Powerful` |

**Custom HTML**
~~~ .html
<h2 class="g-title"><span class="fa fa-sliders fa-fw fa-3x"></span> Powerful</h2>
<p>Dynamically procrastinate B2C users after installed base benefits.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Info List 1 (Particle)

#### Particle Settings

| Field                         | Setting                                                                     |
| :-----                        | :-----                                                                      |
| Particle Name                 | `Modern Design`                                                             |
| CSS Classes                   | Blank                                                                       |
| Title                         | Blank                                                                       |
| Info Lists Item 1 Title       | `Modern Design`                                                             |
| Info Lists Item 1 Link        | `#`                                                                         |
| Info Lists Item 1 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |
| Info Lists Item 2 Title       | `Awesome Support`                                                           |
| Info Lists Item 2 Link        | `#`                                                                         |
| Info Lists Item 2 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Info List 2 (Particle)

#### Particle Settings

| Field                         | Setting                                                                     |
| :-----                        | :-----                                                                      |
| Particle Name                 | `Huge Features`                                                             |
| CSS Classes                   | Blank                                                                       |
| Title                         | Blank                                                                       |
| Info Lists Item 1 Title       | `Huge Features`                                                             |
| Info Lists Item 1 Link        | `#`                                                                         |
| Info Lists Item 1 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |
| Info Lists Item 2 Title       | `Demo Content`                                                              |
| Info Lists Item 2 Link        | `#`                                                                         |
| Info Lists Item 2 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Info List 3 (Particle)

#### Particle Settings

| Field                         | Setting                                                                     |
| :-----                        | :-----                                                                      |
| Particle Name                 | `Multi Purpose`                                                             |
| CSS Classes                   | Blank                                                                       |
| Title                         | Blank                                                                       |
| Info Lists Item 1 Title       | `Multi Purpose`                                                             |
| Info Lists Item 1 Link        | `#`                                                                         |
| Info Lists Item 1 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |
| Info Lists Item 2 Title       | `Gantry 5`                                                                  |
| Info Lists Item 2 Link        | `#`                                                                         |
| Info Lists Item 2 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

## Extension Section

![](assets/page_aboutus_5.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting                                |
| :-----        | :-----                                 |
| Particle Name | `We Always Try to Create a Difference` |

**Custom HTML**
~~~ .html
<div class="g-layercontent">
    <h2 class="g-layercontent-title">We Always Try to Create a Difference</h2>
    <div class="g-layercontent-subtitle">Versatile and Flexible Features Powered by the Gantry Framework.</div>
    <a href="#" class="button button-2">Download Callisto</a>
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
| Particle Name | `Sample Sitemap` |

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
| Particle Name  | `Copyright`        |
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
