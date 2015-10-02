---
title: Ethereal: Recreating the Demo - Contact Page
description: Your Guide to Recreating Elements of the Ethereal Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ethereal:Ethereal

---

## Introduction

The **Contact** example page demonstrates how you can create a beautiful page with the Ethereal theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_contact.jpeg)

:   1. **Showcase - Custom HTML (Particle)** [12%, 40%, se]
    2. **Mainbar - Page Content** [23%, 9%, se]
    3. **Sidebar - Custom HTML (Widget)** [23%, 70%, se]
    4. **Bottom - Custom HTML (Particle)** [60%, 30%, se]
    5. **Footer - Custom HTML (Widget)** [70%, 10%, se]
    6. **Footer - Custom HTML (Widget)** [70%, 38%, se]
    7. **Footer - Custom HTML (Widget)** [70%, 65%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Sidebar](#sidebar-section)
4. [Bottom](#bottom-section)
5. [Footer](#footer-section)

## Showcase Section

![](assets/page_contact_1.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">Contact</h2>
  <div class="g-layercontent-subtitle">Keep in Touch with Us</div>
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

## Mainbar Section

![](assets/page_contact_2.jpeg)

The **Mainbar** section is set to `60`% width and both the **Sidebar** and **Aside** sections are set to `20`%.

The page's contact form is a **Contact Form** particle.

Settings used in our demo for each of these particles can be found below.

### Contact Form

#### Particle Settings

| Field            | Setting        |
| :-----           | :-----         |
| Particle Name    | `Contact Form` |
| CSS Classes      | Blank          |
| Header           | Blank          |
| Email Address    | Custom         |
| Enable reCAPTCHA | Unchecked      |
| Site Key         | Blank          |
| Secret Key       | Blank          |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

## Aside Section

![](assets/page_contact_3.jpeg)

The **Aside** section is set to `20`% width.

This area of the page is a **Text** widget. You will find the settings used in our demo below.


### Custom HTML (Widget)

### Details

| Field      | Setting           |
| :-----     | :-----            |
| Title      | `Contact Details` |
| Show Title | Hide              |
| Position   | `aside`           |
| Status     | Published         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block size-100">
    <div class="g-content ">
      <p><img src="images/rocketlauncher/pages/contact/img-01.jpg" alt="image"></p>
      <p><strong>Ethereal</strong> is only available as part of the Club Subscription. Please use the RocketLauncher to install an equivalent of the demo onto your site.</p>
    </div>
  </div>  
</div>

<div class="g-grid">
  <div class="g-block size-100">
    <div class="g-content ">
      <h2 class="g-title">Contact Details</h2>
      <div class="g-contact ">
        <div class="g-contact-item">
          <div class="g-contact-icon"><span class="fa fa-phone fa-fw"></span></div>
          <div class="g-contact-label">Call Us</div>
          <div class="g-contact-text">+1(555)-555-555</div>
        </div>
        <div class="g-contact-item">
          <div class="g-contact-icon"><span class="fa fa-map-marker fa-fw"></span></div>
          <div class="g-contact-label">Office</div>
          <div class="g-contact-text">555 RocketTheme Blvd, CO</div>
        </div>
        <div class="g-contact-item">
          <div class="g-contact-icon"><span class="fa fa-envelope fa-fw"></span></div>
          <div class="g-contact-label">Say Hi</div>
          <div class="g-contact-text">hello@no-reply.com</div>
        </div>
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

![](assets/page_contact_4.jpeg)

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
  <h2 class="g-layercontent-title">Got Billing and Payments Questions?</h2>
  <div class="g-layercontent-subtitle">Email Us for Questions Involving Payments, Billing, and Membership.</div>
  <a href="http://www.rockettheme.com/wordpress/themes/ethereal" class="button button-2">Send Email</a>
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

![](assets/page_aboutus_6.jpeg)

:   1. **Custom HTML (Widget) 1** [20%, 5%, se]
    2. **Custom HTML (Widget) 2** [20%, 38%, se]
    3. **Custom HTML (Widget) 3** [20%, 65%, se]

This area of the page is made up of three **Text** widgets spanning three different widget positions: `footer-a`, `footer-b`, and `footer-c`. You will find the settings used in our demo below.


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
