---
title: Ambrosia: Recreating the Demo - Our Team Page
description: Your Guide to Recreating Elements of the Ambrosia Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/ambrosia:Ambrosia

---

## Introduction

The **Our Team** example page demonstrates how you can create a beautiful page with the Ambrosia template. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_ourteam.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [9%, 45%, se]
    2. **Mainbar - Page Content** [14%, 15%, se]
    3. **Feature - Custom HTML (Widget)** [30%, 15%, se]
    4. **Plugin - Custom HTML (Widget)** [35%, 15%, se]
    5. **Bottom - Custom HTML (Widget)** [75%, 35%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Feature](#feature-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)
  
## Showcase Section

![](assets/page_ourteam_1.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `Our Team - Header` |
| Show Title | Hide                |
| Position   | `showcase-a`        |
| Status     | Published           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">Our Team</h2>
  <div class="g-layercontent-subtitle">Meet the People Behind Ambrosia</div>
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

![](assets/page_ourteam_2.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                 |
| :-----     | :-----                  |
| Title      | `Joe Jensen - Paul Lee` |
| Show Title | Hide                    |
| Position   | `feature-a`             |
| Status     | Published               |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box4 size-50">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-01.jpg">
      <h2>
        Joe Jensen
      </h2>
      <p>
        Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.
      </p>
      <p>
        Image attribution: <a href="http://www.flickr.com/photos/astragony/8260117875/sizes/l/">AMaze by Daniele Zedda</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box4 size-50">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-02.jpg">
      <h2>
        Paul Lee
      </h2>
      <p>
        Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.
      </p>
      <p>
        Image attribution: <a href="http://www.flickr.com/photos/astragony/4728211246/sizes/l/">Stare by JohnONolan</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
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

![](assets/page_ourteam_3.jpeg)

The **Mainbar** section includes the **Our Team** article, displayed through the **Page Content** particle. Here are the settings found in the **Our Team** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `Our Team`     |
| Alias    | `our-team`     |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<h3><em>"Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service." - Robert Smith</em></h3>
~~~

## Plugin Section

![](assets/page_ourteam_4.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting       |
| :-----     | :-----        |
| Title      | `Team Photos` |
| Show Title | Hide          |
| Position   | `plugin-a` |
| Status     | Published     |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-03.jpg">
      <h2 class="g-title">
        Louis Wells
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="https://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">JohnONolan</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-04.jpg">
      <h2 class="g-title">
        Sara Valdez
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">Thomas Leuthard</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-05.jpg">
      <h2 class="g-title">
        Joseph Hart
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">Daniele Zedda</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-06.jpg">
      <h2 class="g-title">
        Amy Guzman
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/mr-h/4217144639/sizes/l/">AllansBrain</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-07.jpg">
      <h2 class="g-title">
        Randy Hicks
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-08.jpg">
      <h2 class="g-title">
        Grace Patel
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-09.jpg">
      <h2 class="g-title">
        Roy Fisher
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-10.jpg">
      <h2 class="g-title">
        Pamela Little
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-11.jpg">
      <h2 class="g-title">
        Scott Bell
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5327739397/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
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

## Bottom Section

![](assets/page_ourteam_5.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting         |
| :-----     | :-----          |
| Title      | `We Are Hiring` |
| Show Title | Hide            |
| Position   | `bottom-a`      |
| Status     | Published       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">We Are Hiring</h2>
  <div class="g-layercontent-subtitle">Join Our Awesome Team with a Great Work Environment</div>
  <a href="http://www.rockettheme.com/wordpress/templates/ambrosia" class="button button-2">Join Ambrosia</a>
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
