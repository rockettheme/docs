---
title: Callisto: Recreating the Demo - Pricing Page
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

## Introduction

The **Pricing** example page demonstrates how you can create a beautiful page with the Callisto template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Text** widgets.

## Layout Manager

![Layout Manager](assets/layout_pricing.jpeg)

This is a look at the **Layout Manager** for the **Callisto - Pages - Pricing** outline. We have detailed the various particles represented here in the sections below.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_pricing.jpeg)

:   1. **Header - Logo** [6%, 11%, se]
    2. **Header - Icon Menu** [6%, 55%, se]
    3. **Navigation - Menu** [10%, 11%, se]
    4. **Navigation - Social** [10%, 78%, se]
    5. **Showcase - Custom HTML** [13%, 40%, se]
    6. **Mainbar - Custom HTML** [19%, 10%, se]
    7. **Mainbar - Custom HTML** [19%, 38%, se]
    8. **Mainbar - Custom HTML** [19%, 65%, se]
    9. **Mainbar - Custom HTML** [29%, 10%, se]
    10. **Mainbar - Custom HTML** [29%, 38%, se]
    11. **Mainbar - Custom HTML** [29%, 65%, se]
    12. **Mainbar - Content List** [40%, 11%, se]
    13. **Mainbar - Info List** [55%, 11%, se]
    14. **Mainbar - Info List** [55%, 38%, se]
    15. **Mainbar - Info List** [55%, 65%, se]
    16. **Extension - Custom HTML** [70%, 40%, se]
    17. **Footer - Custom HTML** [80%, 11%, se]
    18. **Footer - Newsletter** [80%, 38%, se]
    19. **Footer - Custom HTML - Copyright** [80%, 65%, se]
    20. **Copyright - Copyright** [92%, 40%, se]

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

![](assets/page_pricing_1.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `Awesome Plans` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Awesome Plans</h2>
    <div class="g-layercontent-subtitle">Choose the Plan That Suits Your Needs</div>
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

![](assets/page_pricing_2.jpeg)

:   1. **Custom HTML 1** [6%, 6%, se]
    2. **Custom HTML 2** [6%, 36%, se]
    3. **Custom HTML 3** [6%, 66%, se]
    4. **Custom HTML 4** [55%, 6%, se]
    5. **Info List 1** [69%, 6%, se]
    6. **Info List 2** [69%, 50%, se]

The **Mainbar** section itself renders as 100% of the page width as there are no particles or positions assigned to the Sidebar section. With this in mind, the **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Basic` |

**Custom HTML**
~~~ .html
<ul class="g-pricingtable">
    <li class="g-pricingtable-title">Basic</li>
    <li class="g-pricingtable-price">$28</li>
    <li class="g-pricingtable-desc">Globally incubate standards compliant channels</li>
    <li class="g-pricingtable-item">5GB Storage</li>
    <li class="g-pricingtable-item">10 Users</li>
    <li class="g-pricingtable-item">20 Emails</li>
    <li class="g-pricingtable-item">Online Store</li>
    <li class="g-pricingtable-item">Custom Domain</li>
    <li class="g-pricingtable-item">Unlimited Departments</li>
    <li class="g-pricingtable-cta"><a href="http://www.rockettheme.com/wordpress/themes/callisto" class="button button-3">Sign Up</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting  |
| :-----        | :-----   |
| Particle Name | `Standard` |

**Custom HTML**
~~~ .html
<ul class="g-pricingtable">
    <li class="g-pricingtable-title">Standard</li>
    <li class="g-pricingtable-price">$58</li>
    <li class="g-pricingtable-desc">Globally incubate standards compliant channels</li>
    <li class="g-pricingtable-item">5GB Storage</li>
    <li class="g-pricingtable-item">10 Users</li>
    <li class="g-pricingtable-item">20 Emails</li>
    <li class="g-pricingtable-item">Online Store</li>
    <li class="g-pricingtable-item">Custom Domain</li>
    <li class="g-pricingtable-item">Unlimited Departments</li>
    <li class="g-pricingtable-cta"><a href="http://www.rockettheme.com/wordpress/themes/callisto" class="button button-3">Sign Up</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 3 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Pro` |

**Custom HTML**
~~~ .html
<ul class="g-pricingtable">
    <li class="g-pricingtable-title">Pro</li>
    <li class="g-pricingtable-price">$88</li>
    <li class="g-pricingtable-desc">Globally incubate standards compliant channels</li>
    <li class="g-pricingtable-item">5GB Storage</li>
    <li class="g-pricingtable-item">10 Users</li>
    <li class="g-pricingtable-item">20 Emails</li>
    <li class="g-pricingtable-item">Online Store</li>
    <li class="g-pricingtable-item">Custom Domain</li>
    <li class="g-pricingtable-item">Unlimited Departments</li>
    <li class="g-pricingtable-cta"><a href="http://www.rockettheme.com/wordpress/themes/callisto" class="button button-3">Sign Up</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 4 (Particle)

#### Particle Settings

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Try it Out` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Try it Out for 10 Days Free</h2>
<ul>
    <li>All plans come with awesome support by email and phone. There is no hidden fee!</li>
    <li>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/wordpress/themes/callisto">View Professional Plan</a>.</li>
</ul>
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | Blank            |
| Variations     | `Box 3, Rounded` |
| Tag Attributes | Blank            |
| Block Size     | `100%`           |

### Info List 1 (Particle)

#### Particle Settings

| Field                         | Setting                                                                                                                                                                                   |
| :-----                        | :-----                                                                                                                                                                                    |
| Particle Name                 | `Common`                                                                                                                                                                                  |
| CSS Classes                   | Blank                                                                                                                                                                                     |
| Title                         | `Common Queries and Questions`                                                                                                                                                            |
| Info Lists Item 1 Title       | `1. What prices are our services?`                                                                                                                                                        |
| Info Lists Item 1 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 1 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 2 Title       | `2. What is our refund policy?`                                                                                                                                                           |
| Info Lists Item 2 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 2 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 3 Title       | `3. What payment methods do we accept?`                                                                                                                                                   |
| Info Lists Item 3 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 3 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |

### Info List 2 (Particle)

#### Particle Settings

| Field                         | Setting                                                                                                                                                                                   |
| :-----                        | :-----                                                                                                                                                                                    |
| Particle Name                 | `Common Cont.`                                                                                                                                                                            |
| CSS Classes                   | Blank                                                                                                                                                                                     |
| Title                         | `&nbsp;`                                                                                                                                                                                  |
| Info Lists Item 1 Title       | `4. What delivery options do we offer?`                                                                                                                                                   |
| Info Lists Item 1 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 1 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 2 Title       | `5. What support options are available?`                                                                                                                                                  |
| Info Lists Item 2 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 2 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 3 Title       | `6. What additional services are available?`                                                                                                                                              |
| Info Lists Item 3 Link        | `#`                                                                                                                                                                                       |
| Info Lists Item 3 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |

## Extension Section

![](assets/page_pricing_3.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting          |
| :-----        | :-----           |
| Particle Name | `No Hidden Fees` |

**Custom HTML**
~~~ .html
<div class="g-layercontent">
    <h2 class="g-layercontent-title">No Hidden Fees</h2>
    <div class="g-layercontent-subtitle">No Credit Card Required and No Long-Term Contracts</div>
    <a href="#" class="button button-2">Sign Up</a>
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
