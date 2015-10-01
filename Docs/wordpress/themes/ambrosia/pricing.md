---
title: Ambrosia: Recreating the Demo - Pricing Page
description: Your Guide to Recreating Elements of the Ambrosia Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/ambrosia:Ambrosia

---

## Introduction

The **Pricing** example page demonstrates how you can create a beautiful page with the Ambrosia template. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_pricing.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [11%, 40%, se]
    2. **Feature - Custom HTML (Widget)** [17%, 12% se]
    3. **Mainbar - Page Content** [45%, 12%, se]
    4. **Plugin - Info List (Particle)** [52%, 12%, se]
    5. **Bottom - Custom HTML (Widget)** [67%, 40%, se]

1. [Showcase](#showcase-section)
2. [Feature](#feature-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)

## Showcase Section

![](assets/page_pricing_1.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                  |
| :-----     | :-----                   |
| Title      | `Awesome Plans - Header` |
| Show Title | Hide                     |
| Position   | `showcase-a`             |
| Status     | Published                |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Awesome Plans</h2>
    <div class="g-layercontent-subtitle">Choose the Plan that Suits Your Needs</div>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Widget Class Suffix | `flush center` |

## Feature Section

![](assets/page_pricing_2.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting         |
| :-----     | :-----          |
| Title      | `Pricing Table` |
| Show Title | Hide            |
| Position   | `feature-a`     |
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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/templates/ambrosia">Sign Up</a>
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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/templates/ambrosia">Sign Up</a>
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
          <a class="button button-3" href="http://www.rockettheme.com/wordpress/templates/ambrosia">Sign Up</a>
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
| Widget Class Suffix | Blank       |

## Mainbar Section

![](assets/page_pricing_3.jpeg)

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
      <li>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/wordpress/templates/ambrosia">View Professional Plan</a>.
      </li>
    </ul>
  </div>
</div>
~~~

## Plugin Section

![](assets/page_pricing_4.jpeg)

This area of the page is an **Info List** particle placed within a **Gantry 5 Particle** widget in the `plugin-a` widget position. We have included the settings for this particle below.

### Info List (Particle)

### Particle Settings

| Field                            | Setting                                                                                                                                                                                   |
| :-----                           | :-----                                                                                                                                                                                    |
| Particle Name                    | `Info List`                                                                                                                                                                               |
| CSS Classes                      | Blank                                                                                                                                                                                     |
| Title                            | None                                                                                                                                                                                      |
| Intro                            | None                                                                                                                                                                                      |
| Grid Column                      | 2 Columns                                                                                                                                                                                 |
| Info Lists Item 1 Name           | `1. What prices are your services?`                                                                                                                                                       |
| Info Lists Item 1 Image          | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Image Location | Left                                                                                                                                                                                      |
| Info Lists Item 1 Text Style     | Compact                                                                                                                                                                                   |
| Info Lists Item 1 Image Style    | Compact                                                                                                                                                                                   |
| Info Lists Item 1 Description    | `Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.` |
| Info Lists Item 1 Tag            | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Sub Tag        | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Label          | Blank                                                                                                                                                                                     |
| Info Lists Item 1 Link           | `#`                                                                                                                                                                                       |
| Info Lists Item 1 Icon           | Blank                                                                                                                                                                                     |
| Info Lists Item 1 CSS Classes    | Blank                                                                                                                                                                                     |


## Bottom Section

![](assets/page_pricing_5.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `No Hidden Fees` |
| Show Title | Hide             |
| Position   | `bottom-a`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent">
  <h2 class="g-layercontent-title">No Hidden Fees</h2>
  <div class="g-layercontent-subtitle">No Credit Card Required and No Long-Term Contracts</div>
  <a href="http://www.rockettheme.com/wordpress/templates/ambrosia" class="button">Sign Up</a>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Widget Class Suffix | `flush center` |
