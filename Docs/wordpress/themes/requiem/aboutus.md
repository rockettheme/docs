---
title: Requiem: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Requiem Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/requiem:Requiem

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Requiem theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_about.jpeg)

:   1. **Header - Custom HTML (Particle)** [10%, 45%, se]
    2. **Feature - Custom HTML (Particle)** [18%, 8%, se]
    3. **Mainbar - Page Content** [30%, 8%, se]
    4. **Plugin - Custom HTML (Particle)** [55%, 8%, se]
    5. **Bottom - Custom HTML (Particle)** [73%, 30%, se]

1. [Header](#header-section)
2. [Feature](#feature-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#extension-section)
4. [Bottom](#bottom-section)

## Header Section

![](assets/page_aboutus_1.jpeg)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List (Particle)

### Particle Settings

| Field                              | Setting                              |
| :-----                             | :-----                               |
| Particle Name                      | `About Us - Header`                  |
| CSS Classes                        | `center` `g-layercontent` `noborder` |
| Title                              | Blank                                |
| Intro                              | Blank                                |
| Grid Column                        | 1 Column                             |
| Info List Item 1 Name              | About Us                             |
| Info List Item 1 Image             | Blank                                |
| Info List Item 1 Image Location    | Left                                 |
| Info List Item 1 Text Style        | Header                               |
| Info List Item 1 Image Style       | Compact                              |
| Info List Item 1 Description       | `Who We Are`                         |
| Info List Item 1 Tag               | Blank                                |
| Info List Item 1 Sub Tag           | Blank                                |
| Info List Item 1 Label             | Blank                                |
| Info List Item 1 Link              | Blank                                |
| Info List Item 1 Icon              | Blank                                |
| Info List Item 1 Read More Classes | Blank                                |

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

![](assets/page_aboutus_2.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle) 2

### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Custom HTML` |

### Custom HTML

~~~ .html
<div class="g-grid">
  <div class="g-block box-blue center size-33-3">
    <div class="g-content">
      <h2 class="g-title">Our Mission</h2>

      <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
    </div>
  </div>

  <div class="g-block box1 center size-33-3">
    <div class="g-content">
      <h2 class="g-title">Our Values</h2>

      <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
    </div>
  </div>

  <div class="g-block box-orange center size-33-3">
    <div class="g-content">
      <h2 class="g-title">Our Solution</h2>

      <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
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

![](assets/page_aboutus_3.jpeg)

The **Mainbar** section includes the **About Us** post, displayed through the **Page Content** particle. Here are the settings found in the **About Us** post.

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

![](assets/page_aboutus_4.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle) 3

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-dashboard fa-fw fa-2x"></span> Sophisticated</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-arrows-alt fa-fw fa-2x"></span> Responsive</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-sliders fa-fw fa-2x"></span> Powerful</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
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

![](assets/page_aboutus_5.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle) 3

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-layercontent">
  <h2 class="g-layercontent-title">We Always Try to Create a Difference</h2>
  <div class="g-layercontent-subtitle">Versatile and Flexible Features Powered by the Gantry Framework.</div>
  <a href="http://www.rockettheme.com/wordpress/themes/requiem" class="button button-2">Download Requiem</a>
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