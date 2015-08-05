---
title: Salient: Recreating the Demo - Portfolio Page
description: Your Guide to Recreating Elements of the Salient Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/salient:Salient

---

## Introduction

The **Portfolio** example page demonstrates how you can create a beautiful page with the Salient template. Here is some information to help you replicate this page as it appears in the demo.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_portfolio.png)

:   1. **Showcase - Custom HTML (Module)** [10%, 45%, se]
    2. **Above - Custom HTML (Module)** [18%, 5%, se]
    3. **Extension - Custom HTML (Module)** [45%, 5%, se]
    4. **Bottom - Custom HTML (Module)** [70%, 30%, se]

1. [Showcase](#showcase-section)
2. [Above](#above-section)
3. [Extension](#extension-section)
4. [Bottom](#bottom-section)

## Showcase Section

![](assets/page_portfolio_1.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting              |
| :-----     | :-----               |
| Title      | `Portfolio - Header` |
| Show Title | Hide                 |
| Position   | `showcase-a`         |
| Status     | Published            |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Portfolio</h2>
    <div class="g-layercontent-subtitle">What We Have Already Done</div>
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
| Module Class Suffix | `flush center` |

## Above Section

![](assets/page_portfolio_2.png)

This area of the page is a **Content List** particle rendered via a **Gantry 5 Particle** module placed in the `feature-a` position.

### Content List (Particle)

### Details

| Field                    | Setting                                                                                                                                                                                                                         |
| :-----                   | :-----                                                                                                                                                                                                                          |
| Particle Name            | `Content List`                                                                                                                                                                                                                  |
| CSS Classes              | Blank                                                                                                                                                                                                                           |
| Title                    | Blank                                                                                                                                                                                                                           |
| Image                    | Custom                                                                                                                                                                                                                          |
| Image Tag                | `On Going`                                                                                                                                                                                                                      |
| Headline                 | `Salient Premium Project`                                                                                                                                                                                                      |
| Subtitle                 | `Website Redesign and Publishing`                                                                                                                                                                                               |
| Description              | `Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.` |
| Label                    | `Check Project`                                                                                                                                                                                                                 |
| Link                     | `#`                                                                                                                                                                                                                             |
| Icon                     | Blank                                                                                                                                                                                                                           |
| Read More Classes        | Blank                                                                                                                                                                                                                           |
| Grid Column              | 2 Columns                                                                                                                                                                                                                       |
| Content List Item 1 Name | `Mr. Great Client`                                                                                                                                                                                                              |
| Content List Item 1 Icon | `fa fa-user fa-fw`                                                                                                                                                                                                              |
| Content List Item 1 Text | `Mr. Great Client`                                                                                                                                                                                                              |
| Content List Item 1 Link | Blank                                                                                                                                                                                                                           |


## Extension Section

![](assets/page_portfolio_3.png)

This area of the page is an **Info List** particle rendered via a **Gantry 5 Particle** module placed in the `extension-a` position.

### Info List (Particle)

### Details

| Field                        | Setting                                                                     |
| :-----                       | :-----                                                                      |
| Particle Name                | `Info List`                                                                 |
| CSS Classes                  | Blank                                                                       |
| Title                        | `Upcoming Projects`                                                         |
| Intro                        | Blank                                                                       |
| Grid Column                  | 3 Columns                                                                   |
| Info List Item 1 Name        | `404 Pages`                                                                 |
| Info List Item 1 Location    | Left                                                                        |
| Info List Item 1 Text Style  | Compact                                                                     |
| Info List Item 1 Image Style | Compact                                                                     |
| Info List Item 1 Description | `Collaboratively administrate empowered markets via plug-and-play networks` |
| Info List Item 1 Tag         | Blank                                                                       |
| Info List Item 1 Sub Tag     | Blank                                                                       |
| Info List Item 1 Label       | Blank                                                                       |
| Info List Item 1 Link        | `#`                                                                         |
| Info List Item 1 Icon        | Blank                                                                       |
| Info List Item 1 CSS Classes | Blank                                                                       |

## Bottom Section

![](assets/page_portfolio_4.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting                        |
| :-----     | :-----                         |
| Title      | `100% Satisfaction Guaranteed` |
| Show Title | Hide                           |
| Position   | `bottom-a`                     |
| Status     | Published                      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">100% Satisfaction Guaranteed</h2>
  <div class="g-layercontent-subtitle">Will You be the Next to Join Our Happy Clients?</div>
  <a href="http://www.rockettheme.com/joomla/templates/salient" class="button">Join Now</a>
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
| Module Class Suffix | `flush center` |
