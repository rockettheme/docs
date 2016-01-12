---
title: Requiem: Recreating the Demo - Pricing Page
description: Your Guide to Recreating Elements of the Requiem Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/requiem:Requiem

---

## Introduction

The **Pricing** example page demonstrates how you can create a beautiful page with the Requiem template. Here is some information to help you replicate this page as it appears in the demo.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_pricing.png)

:   1. **Header - Info List (particle)** [8%, 40%, se]
    2. **Above - Custom HTML (module)** [15%, 9% se]
    3. **Mainbar - Page Content** [45%, 9%, se]
    4. **Extension - Image Grid (particle)** [52%, 9%, se]
    5. **Bottom - Info List (particle)** [80%, 40%, se]
    6. **Footer - Custom HTML** [86%, 7%, se]
    7. **Footer - Newsletter** [86%, 36%, se]
    8. **Footer - Custom HTML** [86%, 65%, se]

1. [Header](#showcase-section)
2. [Above](#above-section)
3. [Mainbar](#mainbar-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)
6. [Footer](#footer-section)

## Header Section

![](assets/page_pricing_1.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `Pricing - Header` |
| Show Title | Hide                |
| Position   | `header-a`          |
| Status     | Published           |

### Particle Settings

| Option                              | Setting                                 |
| :----------                         | :----------                             |
| CSS Classes                         | `center`, `g-layercontent`, `noborder`  |
| Title                               | Blank                                   |
| Intro                               | Blank                                   |
| Grid Column                         | 1 Column                                |
| Info Lists Item 1 Name              | `Awesome Plans`                         |
| Info Lists Item 1 Image             | Blank                                   |
| Info Lists Item 1 Image Location    | Left                                    |
| Info Lists Item 1 Text Style        | Header                                  |
| Info Lists Item 1 Image Style       | Compact                                 |
| Info Lists Item 1 Description       | `Choose the Plan That Suits Your Needs` |
| Info Lists Item 1 Tag               | Blank                                   |
| Info Lists Item 1 Sub Tag           | Blank                                   |
| Info Lists Item 1 Label             | Blank                                   |
| Info Lists Item 1 Link              | Blank                                   |
| Info Lists Item 1 Icon              | Blank                                   |
| Info Lists Item 1 Read More Classes | Blank                                   |

## Above Section

![](assets/page_pricing_2.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting         |
| :-----     | :-----          |
| Title      | `Pricing Table` |
| Show Title | Hide            |
| Position   | `above-a`       |
| Status     | Published       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block size-33-3">
    <div class="g-content">
      <ul class="g-pricingtable">
        <li class="g-pricingtable-title">Basic
        </li>
        <li class="g-pricingtable-price">$28
        </li>
        <li class="g-pricingtable-desc">Globally incubate standards compliant channels
        </li>
        <li class="g-pricingtable-item">5GB Storage
        </li>
        <li class="g-pricingtable-item">10 Users
        </li>
        <li class="g-pricingtable-item">20 Emails
        </li>
        <li class="g-pricingtable-item">Online Store
        </li>
        <li class="g-pricingtable-item">Custom Domain
        </li>
        <li class="g-pricingtable-item">Unlimited Departments
        </li>
        <li class="g-pricingtable-cta">
          <a class="button button-3" href="http://www.rockettheme.com/joomla/templates/requiem">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
  <div class="g-block size-33-3">
    <div class="g-content">
      <ul class="g-pricingtable">
        <li class="g-pricingtable-title">Standard
        </li>
        <li class="g-pricingtable-price">$58
        </li>
        <li class="g-pricingtable-desc">Globally incubate standards compliant channels
        </li>
        <li class="g-pricingtable-item">5GB Storage
        </li>
        <li class="g-pricingtable-item">10 Users
        </li>
        <li class="g-pricingtable-item">20 Emails
        </li>
        <li class="g-pricingtable-item">Online Store
        </li>
        <li class="g-pricingtable-item">Custom Domain
        </li>
        <li class="g-pricingtable-item">Unlimited Departments
        </li>
        <li class="g-pricingtable-cta">
          <a class="button button-3" href="http://www.rockettheme.com/joomla/templates/requiem">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
  <div class="g-block size-33-3">
    <div class="g-content">
      <ul class="g-pricingtable">
        <li class="g-pricingtable-title">Pro
        </li>
        <li class="g-pricingtable-price">$88
        </li>
        <li class="g-pricingtable-desc">Globally incubate standards compliant channels
        </li>
        <li class="g-pricingtable-item">5GB Storage
        </li>
        <li class="g-pricingtable-item">10 Users
        </li>
        <li class="g-pricingtable-item">20 Emails
        </li>
        <li class="g-pricingtable-item">Online Store
        </li>
        <li class="g-pricingtable-item">Custom Domain
        </li>
        <li class="g-pricingtable-item">Unlimited Departments
        </li>
        <li class="g-pricingtable-cta">
          <a class="button button-3" href="http://www.rockettheme.com/joomla/templates/requiem">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

## Mainbar Section

![](assets/page_pricing_3.png)

The **Mainbar** section includes the **Pricing** article, displayed through the **Page Content** particle. Here are the settings found in the **Pricing** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `Pricing`      |
| Alias    | `pricing`      |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<div class="g-block  size-100">
  <div class="g-content">
    <h2 class="g-title">
      Try it Out for 10 Days Free
    </h2>
    <ul>
      <li>All plans come with awesome support by email and phone. There is no hidden fee!
      </li>
      <li>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/joomla/templates/requiem">View Professional Plan</a>.
      </li>
    </ul>
  </div>
</div>
~~~

## Extension Section

![](assets/page_pricing_4.png)

This area of the page is an **Image Grid** particle placed within a **Gantry 5 Particle** module in the `extension-a` module position. We have included the settings for this particle below.

### Info List (Particle)

### Particle Settings

| Field                         | Setting      |
| :-----                        | :-----       |
| Particle Name                 | `Image Grid` |
| CSS Classes                   | Blank        |
| Title                         | None         |
| Intro                         | None         |
| Grid Column                   | 4 Columns    |
| Album                         | `clients`    |
| Image Grid Item 1 Name        | `Image 1`    |
| Image Grid Item 1 Promo Image | Custom       |
| Image Grid Item 1 Caption     | `Image 1`    |


## Bottom Section

![](assets/page_pricing_5.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                    |
| :-----     | :-----                     |
| Title      | `Pricing - No Hidden Fees` |
| Show Title | Hide                       |
| Position   | `bottom-a`                 |
| Status     | Published                  |

#### Particle Settings

| Option                              | Setting                                               |
| :----------                         | :----------                                           |
| CSS Classes                         | `center`, `g-layercontent`, `noborder`                |
| Title                               | Blank                                                 |
| Intro                               | Blank                                                 |
| Grid Column                         | 1 Column                                              |
| Info Lists Item 1 Name              | `No Hidden Fees`                                      |
| Info Lists Item 1 Image             | Blank                                                 |
| Info Lists Item 1 Image Location    | Left                                                  |
| Info Lists Item 1 Text Style        | Header                                                |
| Info Lists Item 1 Image Style       | Compact                                               |
| Info Lists Item 1 Description       | `No Credit Card Required and No Long-Term Contracts`  |
| Info Lists Item 1 Tag               | Blank                                                 |
| Info Lists Item 1 Sub Tag           | Blank                                                 |
| Info Lists Item 1 Label             | `Sign Up`                                             |
| Info Lists Item 1 Link              | `http://www.rockettheme.com/joomla/templates/requiem` |
| Info Lists Item 1 Icon              | Blank                                                 |
| Info Lists Item 1 Read More Classes | Blank                                                 |

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