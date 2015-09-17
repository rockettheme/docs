---
title: Ethereal: Recreating the Demo - Clients Page
description: Your Guide to Recreating Elements of the Ethereal Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ethereal:Ethereal

---

## Introduction

The **Clients** example page demonstrates how you can create a beautiful page with the Ethereal theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_clients.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [11%, 45%, se]
    2. **Mainbar - Page Content** [17%, 10%, se]
    3. **Plugin - Custom HTML (Widget)** [28%, 10%, se]
    4. **Bottom - Custom HTML (Widget)** [55%, 35%, se]
    5. **Footer - Custom HTML (Widget)** [70%, 10%, se]
    6. **Footer - Custom HTML (Widget)** [70%, 38%, se]
    7. **Footer - Custom HTML (Widget)** [70%, 65%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)
4. [Footer](#footer-section)

## Showcase Section

![](assets/page_clients_1.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting            |
| :-----     | :-----             |
| Title      | `Clients - Header` |
| Show Title | Hide               |
| Position   | `showcase-a`       |
| Status     | Published          |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Clients</h2>
    <div class="g-layercontent-subtitle">Our Happy Customers</div>
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

![](assets/page_clients_2.jpeg)

The **Mainbar** section includes the **Clients** article, displayed through the **Page Content** particle. Here are the settings found in the **Clients** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `Clients`      |
| Alias    | `clients`      |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<p class="center">Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.<span class="visible-desktop"> Dramatically maintain clicks-and-mortar solutions without functional solutions. Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. </p>
~~~

## Plugin Section

![](assets/page_clients_3.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                                 |
| :-----     | :-----                                  |
| Title      | `Clients Grid` |
| Show Title | Hide                                    |
| Position   | `plugin-a`                           |
| Status     | Published                               |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block center flush size-100">
    <div class="g-content ">
      <div class="g-imagegrid ">
        <div class="g-imagegrid-wrapper g-imagegrid-4cols">
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 1" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-01.jpg" class="g-imagegrid-link"><img alt="Client 1" src="images/rocketlauncher/pages/clients/img-01.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 2" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-02.jpg" class="g-imagegrid-link"><img alt="Client 2" src="images/rocketlauncher/pages/clients/img-02.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 3" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-03.jpg" class="g-imagegrid-link"><img alt="Client 3" src="images/rocketlauncher/pages/clients/img-03.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 4" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-04.jpg" class="g-imagegrid-link"><img alt="Client 4" src="images/rocketlauncher/pages/clients/img-04.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 5" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-05.jpg" class="g-imagegrid-link"><img alt="Client 5" src="images/rocketlauncher/pages/clients/img-05.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 6" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-06.jpg" class="g-imagegrid-link"><img alt="Client 6" src="images/rocketlauncher/pages/clients/img-06.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 7" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-07.jpg" class="g-imagegrid-link"><img alt="Client 7" src="images/rocketlauncher/pages/clients/img-07.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 8" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-08.jpg" class="g-imagegrid-link"><img alt="Client 8" src="images/rocketlauncher/pages/clients/img-08.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 9" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-09.jpg" class="g-imagegrid-link"><img alt="Client 9" src="images/rocketlauncher/pages/clients/img-09.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 10" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-10.jpg" class="g-imagegrid-link"><img alt="Client 10" src="images/rocketlauncher/pages/clients/img-10.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 11" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-11.jpg" class="g-imagegrid-link"><img alt="Client 11" src="images/rocketlauncher/pages/clients/img-11.jpg"></a>
          </div>
          <div class="g-imagegrid-item">
            <a data-rokbox-caption="Client 12" data-rokbox-album="Clients" data-rokbox="" href="images/rocketlauncher/pages/clients/img-12.jpg" class="g-imagegrid-link"><img alt="Client 12" src="images/rocketlauncher/pages/clients/img-12.jpg"></a>
          </div>
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

| Option              | Setting        |
| :----------         | :----------    |
| Widget Class Suffix | `flush center` |

## Bottom Section

![](assets/page_clients_4.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                   |
| :-----     | :-----                    |
| Title      | `Willing to Work With Us` |
| Show Title | Hide                      |
| Position   | `bottom-a`                |
| Status     | Published                 |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Willing to Work With Us</h2>
    <div class="g-layercontent-subtitle">Have a Project for Us?</div>
    <a href="http://www.rockettheme.com/wordpress/themes/ethereal" class="button button-2">Contact Us</a>
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
