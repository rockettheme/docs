---
title: Callisto: Recreating the Demo - Our Team Page
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

## Introduction

The **Our Team** example page demonstrates how you can create a beautiful page with the Callisto template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Text** widgets.

## Layout Manager

![Layout Manager](assets/layout_ourteam.jpeg)

This is a look at the **Layout Manager** for the **Callisto - Pages - Our Team** outline. We have detailed the various particles represented here in the sections below.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_ourteam.jpeg)

:   1. **Header - Logo** [6%, 12%, se]
    2. **Header - Icon Menu** [6%, 55%, se]
    3. **Navigation - Menu** [8%, 12%, ne]
    4. **Navigation - Social** [8%, 78%, se]
    5. **Showcase - Custom HTML** [11%, 45%, se]
    6. **Mainbar - Custom HTML** [14%, 15%, se]
    7. **Mainbar - Custom HTML** [14%, 52%, se]
    8. **Mainbar - Custom HTML** [32%, 15%, se]
    9. **Mainbar - Custom HTML** [37%, 15%, se]
    10. **Mainbar - Custom HTML** [37%, 40%, se]
    11. **Mainbar - Custom HTML** [37%, 65%, se]
    12. **Mainbar - Custom HTML** [50%, 15%, se]
    13. **Mainbar - Custom HTML** [50%, 40%, se]
    14. **Mainbar - Custom HTML** [50%, 65%, se]
    15. **Mainbar - Custom HTML** [65%, 15%, se]
    16. **Mainbar - Custom HTML** [65%, 40%, se]
    17. **Mainbar - Custom HTML** [65%, 65%, se]
    18. **Extension - Custom HTML** [79%, 40%, se]
    19. **Footer - Custom HTML** [85%, 15%, se]
    20. **Footer - Newsletter** [85%, 40%, se]
    21. **Footer - Custom HTML - Copyright** [85%, 65%, se]
    22. **Copyright - Copyright** [92%, 40%, se]

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
| Particle Name          | `Icon Menu`      |
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

![](assets/page_ourteam_1.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `The Team` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">The Team</h2>
    <div class="g-layercontent-subtitle">Meet the People Behind Callisto</div>
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

![](assets/page_ourteam_2.jpeg)

:   1. **Custom HTML 1** [5%, 10%, se]
    2. **Custom HTML 2** [5%, 52%, se]
    3. **Custom HTML 3** [30%, 10%, se]
    4. **Custom HTML 4** [38%, 10%, se]
    5. **Custom HTML 5** [38%, 38%, se]
    6. **Custom HTML 6** [38%, 65%, se]
    7. **Custom HTML 7** [56%, 10%, se]
    8. **Custom HTML 8** [56%, 38%, se]
    9. **Custom HTML 9** [56%, 65%, se]
    10. **Custom HTML 10** [76%, 10%, se]
    11. **Custom HTML 11** [76%, 38%, se]
    12. **Custom HTML 12** [76%, 65%, se]

The **Mainbar** section is made up 12 particles, all of which are **Custom HTML** particles, spanning five rows. The Mainbar section itself renders as 100% of the page width as there are no particles or positions assigned to the Sidebar section. With this in mind, the **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting      |
| :-----        | :-----       |
| Particle Name | `Joe Jensen` |

**Custom HTML**
~~~ .html
<img src="http://placehold.it/550x350" alt="image">

<h2>Joe Jensen</h2>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.</p>

<div class="g-social">
    <a href="#" target="_blank">
        <span class="fa fa-twitter fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-facebook fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-google fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-linkedin fa-fw"></span>
    </a>    
</div>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Paul Lee` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-02.jpg" alt="image">

<h2>Paul Lee</h2>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.</p>

<p>Image attribution: <a href="http://www.flickr.com/photos/astragony/4728211246/sizes/l/">Stare by JohnONolan</a>.</p>

<div class="g-social">
    <a href="#" target="_blank">
        <span class="fa fa-twitter fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-facebook fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-google fa-fw"></span>
    </a>
    <a href="#" target="_blank">
        <span class="fa fa-linkedin fa-fw"></span>
    </a>    
</div>
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | `Box 3` |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |

### Custom HTML 3 (Particle)

#### Particle Settings

| Field         | Setting                |
| :-----        | :-----                 |
| Particle Name | `Completely Synergize` |

**Custom HTML**
~~~ .html
<h3><em>"Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service." - Robert Smith</em></h3>
~~~

#### Block Settings

| Field          | Setting  |
| :-----         | :-----   |
| CSS ID         | Blank    |
| CSS Classes    | `center` |
| Variations     | `Box 2`  |
| Tag Attributes | Blank    |
| Block Size     | `100%`   |

### Custom HTML 4 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Louis Wells` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-03.jpg" alt="image">

<h2 class="g-title">Louis Wells</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="https://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">JohnONolan</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 5 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Sara Valdez` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-04.jpg" alt="image">

<h2 class="g-title">Sara Valdez</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">Thomas Leuthard</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 6 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Joseph Hart` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-05.jpg" alt="image">

<h2 class="g-title">Joseph Hart</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">Daniele Zedda</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
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
| Particle Name | `Amy Guzman` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-06.jpg" alt="image">

<h2 class="g-title">Amy Guzman</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/mr-h/4217144639/sizes/l/">AllansBrain</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
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

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Randy Hicks` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-07.jpg" alt="image">

<h2 class="g-title">Randy Hicks</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">carianoff</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 9 (Particle)

#### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Grace Patel` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-08.jpg" alt="image">

<h2 class="g-title">Grace Patel</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">carianoff</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 10 (Particle)

#### Particle Settings

| Field         | Setting      |
| :-----        | :-----       |
| Particle Name | `Roy Fisher` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-09.jpg" alt="image">

<h2 class="g-title">Roy Fisher</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">carianoff</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 11 (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `Pamela Little` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-10.jpg" alt="image">

<h2 class="g-title">Pamela Little</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">carianoff</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 12 (Particle)

#### Particle Settings

| Field         | Setting      |
| :-----        | :-----       |
| Particle Name | `Scott Bell` |

**Custom HTML**
~~~ .html
<img src="gantry-theme://images/demo/pages/pages/our-team/img-11.jpg" alt="image">

<h2 class="g-title">Scott Bell</h2>

<p>Collaboratively administrate empowered markets via available great networks.</p>

<p>Image by <a href="http://www.flickr.com/photos/carianoff/5327739397/sizes/l/">carianoff</a>.</p>

<div class="g-social">
  <a href="#" target="_blank">
      <span class="fa fa-twitter fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-facebook fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-google fa-fw"></span>
  </a>
  <a href="#" target="_blank">
      <span class="fa fa-linkedin fa-fw"></span>
  </a>  
</div>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

## Extension Section

![](assets/page_ourteam_3.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting         |
| :-----        | :-----          |
| Particle Name | `We Are Hiring` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">We Are Hiring</h2>
    <div class="g-layercontent-subtitle">Join Our Awesome Team with a Great Work Environment</div>
    <a href="#" class="button button-2">Join Callisto</a>
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
