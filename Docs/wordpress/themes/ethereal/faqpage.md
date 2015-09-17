---
title: Ethereal: Recreating the Demo - FAQ Page
description: Your Guide to Recreating Elements of the Ethereal Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ethereal:Ethereal

---

## Introduction

The **FAQ** example page demonstrates how you can create a beautiful page with the Ethereal theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_faqpage.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [8%, 40%, se]
    2. **Feature - Custom HTML (Widget)** [15%, 15% se]
    3. **Mainbar - Page Content** [25%, 15%, se]
    4. **Plugin - Custom HTML (Widget)** [40%, 15%, se]
    5. **Bottom - Custom HTML (Widget)** [65%, 35%, se]
    6. **Footer - Custom HTML (Widget)** [75%, 15%, se]
    7. **Footer - Custom HTML (Widget)** [75%, 38%, se]
    8. **Footer - Custom HTML (Widget)** [75%, 65%, se]

1. [Showcase](#showcase-section)
2. [Feature](#feature-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)
4. [Footer](#footer-section)

## Showcase Section

![](assets/page_faqpage_1.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `Frequently Asked Questions - Header` |
| Show Title | Hide                |
| Position   | `showcase-a`        |
| Status     | Published           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Frequently Asked Questions</h2>
    <div class="g-layercontent-subtitle">Common Queries and Questions</div>
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

![](assets/page_faqpage_2.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                |
| :-----     | :-----                 |
| Title      | `Email - Phone - Chat` |
| Show Title | Hide                   |
| Position   | `feature-a`            |
| Status     | Published              |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box-blue center  size-33-3">
    <div class="g-content ">
      <span class="fa fa-envelope fa-3x"></span>
      <h2 class="g-title">Email</h2>
      <p>Collaboratively administrate empowered markets via available great networks.</p>
      <a class="button button-3" href="">Send Email</a>
    </div>
  </div>
  <div class="g-block box-orange center  size-33-3">
    <div class="g-content ">
      <span class="fa fa-phone fa-3x"></span>
      <h2 class="g-title">Phone</h2>
      <p>Collaboratively administrate empowered markets via available great networks.</p>
      <a class="button button-3" href="">Talk Now</a>
    </div>
  </div>
  <div class="g-block box-grey center  size-33-3">
    <div class="g-content ">
      <span class="fa fa-comments fa-3x"></span>
      <h2 class="g-title">Chat</h2>
      <p>Collaboratively administrate empowered markets via available great networks.</p>
      <a class="button button-3" href="">Ask Us</a>
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

![](assets/page_faqpage_3.jpeg)

The **Mainbar** section includes the **Frequently Asked Questions** article, displayed through the **Page Content** particle. Here are the settings found in the **Frequently Asked Questions** article.

| Option   | Setting                      |
| :-----   | :-----                       |
| Title    | `Frequently Asked Questions` |
| Alias    | `frequently-asked-questions` |
| Status   | Published                    |
| Featured | No                           |
| Category | `Sample Pages`               |

**Content Body**

~~~ .html
<div class="g-grid">
  <div class="g-block size-50">
    <div class="g-content ">
      <div class="g-infolist ">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What prices are our services?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What is our refund policy?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What payments methods do we accept?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="g-block size-50">
    <div class="g-content ">
      <div class="g-infolist ">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What delivery options do we offer?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What support options are available?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="">What additional services are available?</a></div>
            <div class="g-infolist-item-desc">Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
~~~

## Plugin Section

![](assets/page_faqpage_4.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting       |
| :-----     | :-----        |
| Title      | `FAQ List`    |
| Show Title | Hide          |
| Position   | `plugin-a` |
| Status     | Published     |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<section id="g-mainbar">
  <div class="g-grid">
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Installation</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Basic Usage</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Customization</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Development</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="g-grid">
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Accounts</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Subscription</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Security</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Organization</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="g-grid">
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Partnership</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Live Widget</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Web API</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
    <div class="g-block size-25">
      <div class="g-content ">
        <h2 class="g-title">Legal Stuff</h2>
        <ul>
          <li><a href="">Lorem Ipsum</a></li>
          <li><a href="">Dolor Amat</a></li>
          <li><a href="">Figus Terido</a></li>
          <li><a href="">Savios Menor</a></li>
        </ul>
      </div>
    </div>
  </div>
</section>
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

![](assets/page_faqpage_5.jpeg)

This area of the page is a **Text** widget. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) widgets are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Widget)

### Details

| Field      | Setting                          |
| :-----     | :-----                           |
| Title      | `FAQ Didn't Solve Your Problem?` |
| Show Title | Hide                             |
| Position   | `bottom-a`                       |
| Status     | Published                        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">FAQ Didn't Solve Your Problem?</h2>
    <div class="g-layercontent-subtitle">Get Direct Access to the Team Via Phone, Email or Live Chat.</div>
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
