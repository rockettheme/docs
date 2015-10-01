---
title: Ambrosia: Recreating the Demo - Clients Page
description: Your Guide to Recreating Elements of the Ambrosia Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/ambrosia:Ambrosia

---

## Introduction

The **Clients** example page demonstrates how you can create a beautiful page with the Ambrosia template. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_clients.jpeg)

:   1. **Showcase - Custom HTML (Widget)** [11%, 45%, se]
    2. **Mainbar - Page Content** [20%, 10%, se]
    3. **Plugin - Custom HTML (Widget)** [28%, 10%, se]
    4. **Bottom - Custom HTML (Widget)** [60%, 35%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Plugin](#plugin-section)
4. [Bottom](#bottom-section)

## Showcase Section

![](assets/page_clients_1.jpeg)

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

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

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

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

This area of the page is a **Custom HTML** widget. You will find the settings used in our demo below.

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
    <a href="http://www.rockettheme.com/wordpress/templates/ambrosia" class="button button-2">Contact Us</a>
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
