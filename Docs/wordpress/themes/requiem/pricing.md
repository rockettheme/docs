---
title: Requiem: Recreating the Demo - Pricing Page
description: Your Guide to Recreating Elements of the Requiem Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/requiem:Requiem

---

## Introduction

The **Pricing** example page demonstrates how you can create a beautiful page with the Requiem theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_pricing.jpeg)

:   1. **Header - Info List (Particle)** [7%, 40%, se]
    2. **Feature - Custom HTML (Particle)** [15%, 5% se]
    3. **Mainbar - Page Content** [43%, 5%, se]
    4. **Extension - Custom HTML (Particle)** [52%, 5%, se]
    5. **Bottom - Custom HTML (Particle)** [78%, 40%, se]
    5. **Footer - Custom HTML (Widget)** [88%, 5%, se]
    6. **Footer - Custom HTML (Widget)** [88%, 35%, se]
    7. **Footer - Custom HTML (Widget)** [88%, 64%, se]

1. [Header](#header-section)
2. [Feature](#feature-section)
2. [Mainbar](#mainbar-section)
3. [Extension](#extension-section)
4. [Bottom](#bottom-section)
4. [Footer](#footer-section)

## Header Section

![](assets/page_pricing_1.jpeg)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List (Particle)

### Particle Settings

| Field                              | Setting                                 |
| :-----                             | :-----                                  |
| Particle Name                      | `Pricing - Header`                      |
| CSS Classes                        | `center` `g-layercontent` `noborder`    |
| Title                              | Blank                                   |
| Intro                              | Blank                                   |
| Grid Column                        | 1 Column                                |
| Info List Item 1 Name              | `Awesome Plans`                         |
| Info List Item 1 Image             | Blank                                   |
| Info List Item 1 Image Location    | Left                                    |
| Info List Item 1 Text Style        | Header                                  |
| Info List Item 1 Image Style       | Compact                                 |
| Info List Item 1 Description       | `Choose the Plan That Suits Your Needs` |
| Info List Item 1 Tag               | Blank                                   |
| Info List Item 1 Sub Tag           | Blank                                   |
| Info List Item 1 Label             | Blank                                   |
| Info List Item 1 Link              | Blank                                   |
| Info List Item 1 Icon              | Blank                                   |
| Info List Item 1 Read More Classes | Blank                                   |

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `100%`      |

## Feature Section

![](assets/page_pricing_2.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/themes/requiem">Sign Up</a>
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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/themes/requiem">Sign Up</a>
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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/themes/requiem">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</div>
~~~

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `100%`      |

## Mainbar Section

![](assets/page_pricing_3.jpeg)

The **Mainbar** section includes the **Pricing** post, displayed through the **Page Content** particle. Here are the settings found in the **Pricing** post.

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
      <li>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/wordpress/themes/requiem">View Professional Plan</a>.
      </li>
    </ul>
  </div>
</div>
~~~

## Extension Section

![](assets/page_pricing_4.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-grid">
  <div class="g-block size-50">
    <div class="g-content">
      <h2 class="g-title">
        Common Queries and Questions
      </h2>
      <div class="g-infolist">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">1. What prices are our services?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">2. What is our refund policy?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">3. What payments methods do we accept?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="g-block size-50">
    <div class="g-content">
      <h2 class="g-title">
        <span class="hidden-phone">&nbsp;</span><span class="visible-phone">More Common Queries and Questions</span>
      </h2>
      <div class="g-infolist">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">4. What delivery options do we offer?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">5. What support options are available?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title">
              <a href="#">6. What additional services are available?</a>
            </div>
            <div class="g-infolist-item-desc">
              Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
~~~

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `100%`      |

## Bottom Section

![](assets/page_pricing_5.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-layercontent">
  <h2 class="g-layercontent-title">No Hidden Fees</h2>
  <div class="g-layercontent-subtitle">No Credit Card Required and No Long-Term Contracts</div>
  <a href="http://www.rockettheme.com/wordpress/themes/requiem" class="button button-2">Sign Up</a>
</div>
~~~

### Block Settings

| Option         | Setting          |
| :----------    | :----------      |
| CSS ID         | Blank            |
| CSS Classes    | `flush` `center` |
| Variations     | Blank            |
| Tag Attributes | Blank            |
| Fixed Size     | Unchecked        |
| Block Size     | `100%`           |

## Footer Section

![](assets/page_aboutus_6.png)

:   1. **Custom HTML (Widget) 1** [20%, 5%, se]
    2. **Custom HTML (Widget) 2** [20%, 38%, se]
    3. **Custom HTML (Widget) 3** [20%, 65%, se]

This area of the page is made up of three **Text** widgets spanning three different widget positions: `footer-a`, `footer-b`, and `footer-c`. You will find the settings used in our demo below.


### Custom HTML (Widget) 1

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `About Requiem` |
| Show Title | Show             |
| Position   | `footer-a`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Requiem can be constructed on your site.</p>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Widget Class Suffix | Blank       |

### Custom HTML (Widget) 2

### Details

| Field      | Setting      |
| :-----     | :-----       |
| Title      | `Newsletter` |
| Show Title | Show         |
| Position   | `footer-b`   |
| Status     | Published    |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-newsletter">
  <div class="g-newsletter-headtext">
    Subscribe to our newsletter and stay updated on the latest developments and special offers!
  </div>
  <form onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify" class="g-newsletter-form">
    <input type="text" name="email" placeholder="Email Address" class="g-newsletter-inputbox"> <input type="hidden" name="uri" value="rocketthemeblog"> <input type="hidden" value="en_US" name="loc"> <input type="submit" value="Join" class="g-newsletter-button button button-3" name="Submit">
  </form>
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
| Widget Class Suffix | Blank       |

### Custom HTML (Widget) 3

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `Sample Sitemap` |
| Show Title | Show             |
| Position   | `footer-c`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="index.php">Home</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=105">Features</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Typography</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Particles</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=107">Variations</a></li>
        </ul>
    </div>
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Buttons</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=111">Pages</a></li>
            <li><a href="http://www.rockettheme.com/docs/wordpress/themes/requiem">Guide</a></li>
            <li><a href="http://www.rockettheme.com/forum/wordpress-theme-requiem">Support</a></li>
            <li><a href="http://www.rockettheme.com/wordpress/themes/requiem">Download</a></li>
        </ul>       
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
| Widget Class Suffix | Blank       |
