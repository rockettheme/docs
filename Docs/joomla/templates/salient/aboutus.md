---
title: Salient: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Salient Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/salient:Salient

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Salient template. Here is some information to help you replicate this page as it appears in the demo.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_about.png)

:   1. **Showcase - Custom HTML (Module)** [10%, 45%, se]
    2. **Above - Custom HTML (Module)** [18%, 10%, se]
    3. **Mainbar - Page Content** [32%, 10%, se]
    4. **Extension - Custom HTML (Module)** [55%, 10%, se]
    5. **Bottom - Custom HTML (Module)** [72%, 10%, se]

1. [Showcase](#showcase-section)
2. [Above](#above-section)
3. [Mainbar](#mainbar-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)

## Showcase Section

![](assets/page_aboutus_1.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `About Us - Header` |
| Show Title | Hide                |
| Position   | `showcase-a`        |
| Status     | Published           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">About Us</h2>
  <div class="g-layercontent-subtitle">Who We Are</div>
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

![](assets/page_aboutus_2.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting                         |
| :-----     | :-----                          |
| Title      | `Missions - Values - Solutions` |
| Show Title | Hide                            |
| Position   | `above-a`                     |
| Status     | Published                       |

### Custom Output

Enter the following in the **Custom Output** text editor.

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

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `flush center` |

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

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting                                 |
| :-----     | :-----                                  |
| Title      | `Sophisticated - Responsive - Powerful` |
| Show Title | Hide                                    |
| Position   | `extension-a`                           |
| Status     | Published                               |

### Custom Output

Enter the following in the **Custom Output** text editor.

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

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

## Bottom Section

![](assets/page_aboutus_5.png)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting                                |
| :-----     | :-----                                 |
| Title      | `We Always Try to Create a Difference` |
| Show Title | Hide                                   |
| Position   | `bottom-a`                             |
| Status     | Published                              |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent">
  <h2 class="g-layercontent-title">We Always Try to Create a Difference</h2>
  <div class="g-layercontent-subtitle">Versatile and Flexible Features Powered by the Gantry Framework.</div>
  <a href="http://www.rockettheme.com/joomla/templates/salient" class="button">Download Salient</a>
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