---
title: Ethereal: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Ethereal Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ethereal:Ethereal

---

## Introduction

The **About Us** example page demonstrates how you can create a beautiful page with the Ethereal theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_aboutus.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [11%, 45%, se]
    2. **Mainbar - Page Content** [16%, 10%, se]
    3. **Plugin - Custom HTML (Widget)** [28%, 10%, se]
    4. **Bottom - Custom HTML (Widget)** [47%, 10%, se]
    5. **Footer - Custom HTML (Widget)** [72%, 10%, se]
    6. **Footer - Custom HTML (Widget)** [72%, 38%, se]
    7. **Footer - Custom HTML (Widget)** [72%, 65%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)
4. [Footer](#footer-section)

## Showcase Section

![](assets/page_aboutus_2.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

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
| Widget Class Suffix | `flush center` |

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

## Plugin Section

![](assets/page_aboutus_4.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                                 |
| :-----     | :-----                                  |
| Title      | `Sophisticated - Responsive - Powerful` |
| Show Title | Hide                                    |
| Position   | `plugin-a`                           |
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
| Widget Class Suffix | Blank       |

## Bottom Section

![](assets/page_aboutus_5.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

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
    <a href="http://www.rockettheme.com/wordpress/themes/ethereal" class="button button-2">Download Ethereal</a>
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

## Footer Section

![](assets/page_aboutus_6.jpeg)

:   1. **Custom HTML (Widget) 1** [20%, 5%, se]
    2. **Custom HTML (Widget) 2** [20%, 38%, se]
    3. **Custom HTML (Widget) 3** [20%, 65%, se]

This area of the page is made up of three **Text** widgets spanning three different widget positions: `footer-a`, `footer-b`, and `footer-c`. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget) 1

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `About Ethereal` |
| Show Title | Show             |
| Position   | `footer-a`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Ethereal can be constructed on your site.</p>
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
            <li><a href="http://www.rockettheme.com/docs/wordpress/themes/ethereal">Guide</a></li>
            <li><a href="http://www.rockettheme.com/forum/wordpress-theme-ethereal">Support</a></li>
            <li><a href="http://www.rockettheme.com/wordpress/themes/ethereal">Download</a></li>
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
