---
title: Isotope: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Isotope Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/isotope:Isotope

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Isotope theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_aboutus.jpeg)

:   1. **Showcase - Custom HTML (Particle)** [5%, 45%, se]
    2. **Feature - Custom HTML (Particle)** [15%, 5%, se]
    3. **Mainbar - Page Content** [30%, 5%, se]
    4. **Plugin - Custom HTML (Particle)** [55%, 5%, se]
    5. **Bottom - Custom HTML (Particle)** [68%, 30%, se]

1. [Showcase](#showcase-section)
2. [Feature](#feature-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#extension-section)
4. [Bottom](#bottom-section)

## Showcase Section

![](assets/page_aboutus_1.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field         | Setting       |
| :-----        | :-----        |
| Particle Name | `Custom HTML` |

### Custom HTML

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">About Us</h2>
  <div class="g-layercontent-subtitle">Who We Are</div>
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
  <a href="http://www.rockettheme.com/wordpress/themes/isotope" class="button button-2">Download Isotope</a>
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