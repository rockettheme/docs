---
title: Requiem: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Requiem Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/requiem:Requiem

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Requiem template. Here is some information to help you replicate this page as it appears in the demo.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_about.png)

:   1. **Header - Custom HTML (Module)** [8%, 45%, se]
    2. **Above - Custom HTML (Module)** [18%, 10%, se]
    3. **Mainbar - Page Content** [32%, 10%, se]
    4. **Extension - Custom HTML (Module)** [57%, 10%, se]
    5. **Bottom - Custom HTML (Module)** [72%, 10%, se]
    6. **Footer - Custom HTML** [86%, 7%, se]
    7. **Footer - Newsletter** [86%, 36%, se]
    8. **Footer - Custom HTML** [86%, 65%, se]

1. [Header](#header-section)
2. [Above](#above-section)
3. [Mainbar](#mainbar-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)
6. [Footer](#footer-section)

## Header Section

![](assets/page_aboutus_1.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `About Us - Header` |
| Show Title | Hide                |
| Position   | `header-a`          |
| Status     | Published           |

### Particle Settings

| Option                              | Setting                                |
| :----------                         | :----------                            |
| CSS Classes                         | `center`, `g-layercontent`, `noborder` |
| Title                               | Blank                                  |
| Intro                               | Blank                                  |
| Grid Column                         | 1 Column                               |
| Info Lists Item 1 Name              | `About Us`                             |
| Info Lists Item 1 Image             | Blank                                  |
| Info Lists Item 1 Image Location    | Left                                   |
| Info Lists Item 1 Text Style        | Header                                 |
| Info Lists Item 1 Image Style       | Compact                                |
| Info Lists Item 1 Description       | `Who We Are`                           |
| Info Lists Item 1 Tag               | Blank                                  |
| Info Lists Item 1 Sub Tag           | Blank                                  |
| Info Lists Item 1 Label             | Blank                                  |
| Info Lists Item 1 Link              | Blank                                  |
| Info Lists Item 1 Icon              | Blank                                  |
| Info Lists Item 1 Read More Classes | Blank                                  |

## Above Section

![](assets/page_aboutus_2.png)

This area of the page is an **Block Content** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                                  |
| :-----     | :-----                                   |
| Title      | `About Us - Mission - Values - Solution` |
| Show Title | Hide                                     |
| Position   | `above-a`                                |
| Status     | Published                                |

### Particle Settings

| Option                        | Setting                                                                                                                                                               |
| :----------                   | :----------                                                                                                                                                           |
| Image                         | Blank                                                                                                                                                                 |
| Headline                      | Blank                                                                                                                                                                 |
| Description                   | Blank                                                                                                                                                                 |
| Link                          | Blank                                                                                                                                                                 |
| Link Text                     | Blank                                                                                                                                                                 |
| CSS Classes                   | Blank                                                                                                                                                                 |
| Content Item 1 Name           | `Our Mission`                                                                                                                                                         |
| Content Item 1 Title          | `Our Mission`                                                                                                                                                         |
| Content Item 1 Icon           | Blank                                                                                                                                                                 |
| Content Item 1 Image          | Blank                                                                                                                                                                 |
| Content Item 1 Sub title      | Blank                                                                                                                                                                 |
| Content Item 1 Description    | `Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.` |
| Content Item 1 CSS Classes    | `center`, `box-blue`                                                                                                                                                  |
| Content Item 1 Button Label   | Blank                                                                                                                                                                 |
| Content Item 1 Button Link    | Blank                                                                                                                                                                 |
| Content Item 1 Button Classes | Blank                                                                                                                                                                 |

## Mainbar Section

![](assets/page_aboutus_3.png)

The **Mainbar** section includes the **About Us** article, displayed through the **Page Content** particle. Here are the settings found in the **About Us** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `About Us`     |
| Alias    | `about-us`     |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<div class="g-grid">
  <div class="g-block flush center size-100">
    <div class="g-content">
      <div class="g-layercontent g-layercontent-small">
        <h2 class="g-layercontent-title">
          Why You Should Join Us
        </h2>
        <div class="g-layercontent-subtitle">
          Choose the theme that suits your needs. 100% satisfaction guaranteed.
        </div>
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block flush size-100">
    <div class="g-content">
      <div class="g-grid center">
        <div class="g-block nopaddingall">
          <div class="g-content">
            <img alt="image" src="images/rocketlauncher/pages/about-us/img-01.jpg">
            <h2 class="g-title">
              Introduction
            </h2>
          </div>
        </div>
        <div class="g-block nopaddingall">
          <div class="g-content">
            <img alt="image" src="images/rocketlauncher/pages/about-us/img-02.jpg">
            <h2 class="g-title">
              Mission
            </h2>
          </div>
        </div>
        <div class="g-block nopaddingall">
          <div class="g-content">
            <img alt="image" src="images/rocketlauncher/pages/about-us/img-03.jpg">
            <h2 class="g-title">
              Business
            </h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
~~~

## Extension Section

![](assets/page_aboutus_4.png)

This area of the page is an **Block Content** particle. You will find the settings used in our demo below.

### Block Content Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                                            |
| :-----     | :-----                                             |
| Title      | `About Us - Sophisticated - Responsive - Powerful` |
| Show Title | Hide                                               |
| Position   | `extension-a`                                      |
| Status     | Published                                          |

### Particle Settings

| Option                        | Setting                                                              |
| :----------                   | :----------                                                          |
| Image                         | Blank                                                                |
| Headline                      | Blank                                                                |
| Description                   | Blank                                                                |
| Link                          | Blank                                                                |
| Link Text                     | Blank                                                                |
| CSS Classes                   | Blank                                                                |
| Content Item 1 Name           | `Our Mission`                                                        |
| Content Item 1 Title          | `Sophisticated`                                                      |
| Content Item 1 Icon           | `fa fa-dashboard fa-fw fa-2x`                                        |
| Content Item 1 Image          | Blank                                                                |
| Content Item 1 Sub title      | Blank                                                                |
| Content Item 1 Description    | `Dynamically procrastinate B2C users after installed base benefits.` |
| Content Item 1 CSS Classes    | `box-gray`                                                           |
| Content Item 1 Button Label   | Blank                                                                |
| Content Item 1 Button Link    | Blank                                                                |
| Content Item 1 Button Classes | Blank                                                                |

## Bottom Section

![](assets/page_aboutus_5.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                                           |
| :-----     | :-----                                            |
| Title      | `About Us - We Always Try to Create a Difference` |
| Show Title | Hide                                              |
| Position   | `bottom-a`                                        |
| Status     | Published                                         |

#### Particle Settings

| Option                              | Setting                                                            |
| :----------                         | :----------                                                        |
| CSS Classes                         | `center`, `g-layercontent`, `noborder`                             |
| Title                               | Blank                                                              |
| Intro                               | Blank                                                              |
| Grid Column                         | 1 Column                                                           |
| Info Lists Item 1 Name              | `We Always Try to Create a Difference`                             |
| Info Lists Item 1 Image             | Blank                                                              |
| Info Lists Item 1 Image Location    | Left                                                               |
| Info Lists Item 1 Text Style        | Header                                                             |
| Info Lists Item 1 Image Style       | Compact                                                            |
| Info Lists Item 1 Description       | `Versatile and Flexible Features Powered by the Gantry Framework.` |
| Info Lists Item 1 Tag               | Blank                                                              |
| Info Lists Item 1 Sub Tag           | Blank                                                              |
| Info Lists Item 1 Label             | `Download Requiem`                                                 |
| Info Lists Item 1 Link              | `http://www.rockettheme.com/joomla/templates/requiem`              |
| Info Lists Item 1 Icon              | Blank                                                              |
| Info Lists Item 1 Read More Classes | Blank                                                              |

## Footer Section

![](assets/page_aboutus_6.png)

:   1. **Custom HTML 1** [30%, 5%, se]
    2. **Newsletter** [30%, 38%, se]
    3. **Custom HTML 2** [30%, 70%, se]

The **Footer** section is made up of two modules and one particle in a single row. This includes a **Newsletter** particle surrounded by two **Custom HTML** modules.

Settings used in our demo for each of these modules and particle can be found below.

### Custom HTML 1 (Module)

#### Module settings

| Field        | Setting         |
| :-----       | :-----          |
| Module Title | `About Requiem` |
| Show Title   | Show            |
| Position     | `footer-a`      |

**Custom HTML**
~~~ .html
Requiem is available for purchase or part of a club membership from RocketTheme, inclusive of the RocketLauncher, template, addons and sources.
~~~

### Newsletter (Particle)

#### Particle Settings

| Field          | Setting           |
| :-----         | :-----            |
| Particle Name  | `Newsletter`      |
| CSS Classes    | Blank             |
| Title          | `Newsletter`      |
| InputBox Text  | `Email Address`   |
| Button Text    | `Join`            |
| Feedburner URI | `rocketthemeblog` |
| Button Classes | `button-4`        |


**Heading Text**
~~~ .html
Subscribe to our newsletter and stay updated on the latest developments and special offers!
~~~

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `33.3%` |

### Custom HTML 2 (Module)

#### Module settings

| Field        | Setting          |
| :-----       | :-----           |
| Module Title | `Sample Sitemap` |
| Show Title   | Show             |
| Position     | `footer-c`       |

**Custom HTML**
~~~ .html
<div class="g-grid g-sample-sitemap">
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="index.php">Home</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=105">Features</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=106">Typography</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=106">Particles</a></li>
      <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=107">Variations</a></li>
    </ul>
  </div>
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=106">Buttons</a></li>
      <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=111">Pages</a></li>
      <li><a href="http://www.rockettheme.com/docs/joomla/templates/requiem">Guide</a></li>
      <li><a href="http://www.rockettheme.com/forum/joomla-template-requiem">Support</a></li>
      <li><a href="http://www.rockettheme.com/joomla/templates/requiem">Download</a></li>
    </ul>   
  </div>  
</div>
~~~