---
title: Ethereal: Recreating the Demo - FAQ Page
description: Your Guide to Recreating Elements of the Ethereal Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ethereal:Ethereal

---

## Introduction

The **FAQ** example page demonstrates how you can create a beautiful page with the Ethereal template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Custom HTML** modules.

## Layout Manager

![Layout Manager](assets/layout_faqpage.jpeg)

This is a look at the **Layout Manager** for the **Ethereal - Pages - FAQ** outline. We have detailed the various particles represented here in the sections below.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_faqpage.jpeg)

:   1. **Header - Logo** [6%, 11%, se]
    2. **Header - Icon Menu** [6%, 55%, se]
    3. **Navigation - Menu** [9%, 11%, se]
    4. **Navigation - Social** [9%, 78%, se]
    5. **Showcase - Custom HTML** [13%, 35%, se]
    6. **Mainbar - Info List** [17%, 11%, se]
    7. **Mainbar - Info List** [17%, 52%, se]
    8. **Mainbar - Custom HTML** [33%, 10%, se]
    9. **Mainbar - Custom HTML** [33%, 38%, se]
    10. **Mainbar - Custom HTML** [33%, 65%, se]
    11. **Mainbar - Custom HTML** [44%, 10%, se]
    12. **Mainbar - Custom HTML** [44%, 30%, se]
    13. **Mainbar - Custom HTML** [44%, 52%, se]
    14. **Mainbar - Custom HTML** [44%, 71%, se]
    15. **Mainbar - Custom HTML** [53%, 10%, se]
    16. **Mainbar - Custom HTML** [53%, 30%, se]
    17. **Mainbar - Custom HTML** [53%, 52%, se]
    18. **Mainbar - Custom HTML** [53%, 71%, se]
    19. **Mainbar - Custom HTML** [63%, 10%, se]
    20. **Mainbar - Custom HTML** [63%, 30%, se]
    21. **Mainbar - Custom HTML** [63%, 52%, se]
    22. **Mainbar - Custom HTML** [63%, 71%, se]
    17. **Extension - Custom HTML** [75%, 30%, se]
    18. **Footer - Custom HTML** [82%, 11%, se]
    19. **Footer - Newsletter** [82%, 38%, se]
    20. **Footer - Custom HTML - Copyright** [82%, 65%, se]
    21. **Copyright - Copyright** [92%, 40%, se]

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
| Text          | `Ethereal` |
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

![](assets/page_faqpage_1.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting                      |
| :-----        | :-----                       |
| Particle Name | `Frequently Asked Questions` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Frequently Asked Questions</h2>
    <div class="g-layercontent-subtitle">Common Queries and Questions</div>
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

![](assets/page_faqpage_2.jpeg)

:   1. **Info List 1** [8%, 7%, se]
    2. **Info List 2** [8%, 51%, se]
    3. **Custom HTML 1** [33%, 8%, se]
    4. **Custom HTML 2** [33%, 40%, se]
    5. **Custom HTML 3** [33%, 68%, se]
    6. **Custom HTML 4** [49%, 7%, se]
    7. **Custom HTML 5** [49%, 30%, se]
    8. **Custom HTML 6** [49%, 51%, se]
    9. **Custom HTML 7** [49%, 73%, se]
    10. **Custom HTML 8** [65%, 7%, se]
    11. **Custom HTML 9** [65%, 30%, se]
    12. **Custom HTML 10** [65%, 51%, se]
    13. **Custom HTML 11** [65%, 73%, se]
    14. **Custom HTML 12** [79%, 7%, se]
    15. **Custom HTML 13** [79%, 30%, se]
    16. **Custom HTML 14** [79%, 51%, se]
    17. **Custom HTML 15** [79%, 73%, se]

The **Mainbar** section itself renders as 100% of the page width as there are no particles or positions assigned to the Sidebar section. With this in mind, the **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Info List 1 (Particle)

#### Particle Settings

| Field                         | Setting                                                                                                                                                                                   |
| :-----                        | :-----                                                                                                                                                                                    |
| Particle Name                 | `What prices?`                                                                                                                                                                            |
| CSS Classes                   | Blank                                                                                                                                                                                     |
| Title                         | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Title       | `What prices are our services?`                                                                                                                                                           |
| Info Lists Item 1 Link        | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 2 Title       | `What is our refund policy?`                                                                                                                                                              |
| Info Lists Item 2 Link        | Blank                                                                                                                                                                                     |
| Info Lists Item 2 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 3 Title       | `What payments methods do we accept?`                                                                                                                                                     |
| Info Lists Item 3 Link        | Blank                                                                                                                                                                                     |
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
| Particle Name                 | `What Delivery?`                                                                                                                                                                          |
| CSS Classes                   | Blank                                                                                                                                                                                     |
| Title                         | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Title       | `What delivery options do we offer?`                                                                                                                                                      |
| Info Lists Item 1 Link        | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 2 Title       | `What support options are available?`                                                                                                                                                     |
| Info Lists Item 2 Link        | Blank                                                                                                                                                                                     |
| Info Lists Item 2 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 3 Title       | `What additional services are available?`                                                                                                                                                 |
| Info Lists Item 3 Link        | Blank                                                                                                                                                                                     |
| Info Lists Item 3 Description | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Email` |

**Custom HTML**
~~~ .html
<span class="fa fa-envelope fa-3x"></span>
<h2 class="g-title">Email</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
<a href="#" class="button button-3">Send Email</a>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `center`   |
| Variations     | `Box Blue` |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%`      |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Phone` |

**Custom HTML**
~~~ .html
<span class="fa fa-phone fa-3x"></span>
<h2 class="g-title">Phone</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
<a href="#" class="button button-3">Talk Now</a>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `center`   |
| Variations     | `Box Blue` |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 3 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Chat` |

**Custom HTML**
~~~ .html
<span class="fa fa-comments fa-3x"></span>
<h2 class="g-title">Chat</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
<a href="#" class="button button-3">Ask Us</a>
~~~

#### Block Settings

| Field          | Setting      |
| :-----         | :-----       |
| CSS ID         | Blank        |
| CSS Classes    | `center`     |
| Variations     | `Box Purple` |
| Tag Attributes | Blank        |
| Block Size     | `33.3333%`   |

### Custom HTML 4 (Particle)

#### Particle Settings

| Field         | Setting        |
| :-----        | :-----         |
| Particle Name | `Installation` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Installation</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 5 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Basic Usage` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Basic Usage</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 6 (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `Customization` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Customization</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 7 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Development` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Development</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 8 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Accounts` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Accounts</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 9 (Particle)

#### Particle Settings

| Field         | Setting        |
| :-----        | :-----         |
| Particle Name | `Subscription` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Subscription</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 10 (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Security` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Security</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 11 (Particle)

#### Particle Settings

| Field         | Setting        |
| :-----        | :-----         |
| Particle Name | `Organization` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Organization</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 12 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Partnership` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Partnership</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 13 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Live Widget` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Live Widget</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 14 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Web API` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Web API</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

### Custom HTML 15 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Legal Stuff` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Legal Stuff</h2>
<ul>
  <li><a href="#">Lorem Ipsum</a></li>
  <li><a href="#">Dolor Amat</a></li>
  <li><a href="#">Figus Terido</a></li>
  <li><a href="#">Savios Menor</a></li>
</ul>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `25%`   |

## Extension Section

![](assets/page_faqpage_3.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting                        |
| :-----        | :-----                         |
| Particle Name | `FAQ Didn't Solve Your Problem?` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">FAQ Didn't Solve Your Problem?</h2>
    <div class="g-layercontent-subtitle">Get Direct Access to the Team Via Phone, Email or Live Chat.</div>
    <a href="#" class="button button-2">Contact Us</a>
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
| Particle Name | `About Ethereal` |

**Custom HTML**
~~~ .html
<h2 class="g-title">About Ethereal</h2>

<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Ethereal can be constructed on your site.</p>
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
