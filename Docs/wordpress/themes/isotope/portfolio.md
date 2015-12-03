---
title: Isotope: Recreating the Demo - Portfolio Page
description: Your Guide to Recreating Elements of the Isotope Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/isotope:Isotope

---

## Introduction

The **Portfolio** example page demonstrates how you can create a beautiful page with the Isotope theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_portfolio.jpeg)

:   1. **Showcase - Custom HTML (Particle)** [3%, 45%, se]
    2. **Mainbar - Page Content** [10%, 20%, se]
    3. **Feature - Custom HTML (Particle)** [28%, 20%, se]
    4. **Extension - Custom HTML (Particle)** [58%, 20%, se]
    5. **Bottom - Custom HTML (Particle)** [76%, 35%, se]
    6. **Footer - Custom HTML (Particle)** [85%, 20%, se]
    7. **Footer - Custom HTML (Particle)** [85%, 45%, se]
    8. **Footer - Custom HTML (Particle)** [85%, 70%, se]

1. [Showcase](#showcase-section)
2. [Feature](#feature-section)
3. [Mainbar](#mainbar-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)
6. [Footer](#footer-section)

## Showcase Section

![](assets/page_portfolio_1.jpeg)

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
  <h2 class="g-layercontent-title">Portfolio</h2>
  <div class="g-layercontent-subtitle">What We Have Already Done</div>
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

![](assets/page_portfolio_2.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-grid">
  <div class="g-block box4 rounded nopaddingall size-67">
    <div class="g-content ">
      <div class="g-contentlist ">
        <div class="g-grid">
          <div style="background-image: url(wp-content://rocketlauncher/pages/portfolio/img-01.jpg)" class="g-block size-33 g-contentlist-img">
            <div class="g-contentlist-img-tag">On Going</div>
          </div>
          <div class="g-block size-67 g-contentlist-text">
            <div class="g-content">
              <h3 class="g-contentlist-headline">Isotope Premium Project</h3>
              <h5 class="g-contentlist-subtitle">Website Redesign and Publishing</h5>
              <div class="g-contentlist-desc">Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</div>
              <a class="button button-2" href="#">Check Project</a>             
            </div>
          </div>
        </div>
        <div class="g-grid g-contentlist-list">
          <div class="g-block">
            <div class="g-content">
              <div class="g-listgrid g-listgrid-2cols">
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-user fa-fw"></span>
                  <span>Mr. Great Client</span>
                  </a>
                </div>
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-check-square-o fa-fw"></span>
                  <span>Graphic</span>
                  </a>
                </div>
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-calendar fa-fw"></span>
                  <span>01/01/2086</span>
                  </a>
                </div>
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-check-square-o fa-fw"></span>
                  <span>HTML/CSS</span>
                  </a>
                </div>
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-tags fa-fw"></span>
                  <span>design, cover, logo</span>
                  </a>
                </div>
                <div class="g-listgrid-item">
                  <a href="#">
                  <span class="fa fa-check-square-o fa-fw"></span>
                  <span>Gantry</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="g-block size-33">
    <div class="g-content ">
      <h2 class="g-title">Responsive Layout</h2>
      <p><img alt="image" src="wp-content://rocketlauncher/pages/portfolio/img-02.jpg"></p>
      <p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits.</p>
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

![](assets/page_portfolio_3.jpeg)

The **Mainbar** section includes the **Portfolio** article, displayed through the **Page Content** particle. Here are the settings found in the **Portfolio** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `Portfolio`     |
| Alias    | `portfolio`     |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<div class="g-grid">
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Magazine</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Magazine" src="images/rocketlauncher/pages/portfolio/img-03.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Magazine</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Logo</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Logo" src="images/rocketlauncher/pages/portfolio/img-04.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Logo</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Brochure</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Brochure" src="images/rocketlauncher/pages/portfolio/img-05.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Brochure</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Decorations</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Decorations" src="images/rocketlauncher/pages/portfolio/img-06.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Decorations</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Illustrations</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Illustrations" src="images/rocketlauncher/pages/portfolio/img-07.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Illustrations</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
  <div class="g-block center  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Photos</h2>
      <div class="g-promoimage ">
        <figure class="g-promoimage-effect">
          <span class="g-promoimage-iconbutton fa fa-file-text-o"></span>
          <img alt="Photos" src="images/rocketlauncher/pages/portfolio/img-08.jpg">
          <div class="g-promoimage-caption">
            <div class="g-promoimage-title">Photos</div>
            <div class="g-promoimage-icon">
            </div>
            <div class="g-promoimage-desc">Short project description here</div>
          </div>
        </figure>
      </div>
    </div>
  </div>
</div>
~~~

## Extension Section

![](assets/page_portfolio_4.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

### Custom HTML (Particle)

### Particle Settings

| Field              | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

### Custom HTML

~~~ .html
<div class="g-grid">
  <div class="g-block  size-33-3">
    <div class="g-content ">
      <h2 class="g-title">Upcoming Projects</h2>
      <div class="g-infolist ">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">404 Pages</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Badges</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Stickers</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="g-block  size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="hidden-phone">&nbsp;</span><span class="visible-phone">More Upcoming Projects</span></h2>
      <div class="g-infolist ">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Banners</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Sliders</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="Tables">New item</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="g-block  size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="hidden-phone">&nbsp;</span><span class="visible-phone">More Upcoming Projects</span></h2>
      <div class="g-infolist ">
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Forms</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Newsletter</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
        <div class="g-infolist-item">
          <div class="g-infolist-item-text">
            <div class="g-infolist-item-title"><a href="#">Interfaces</a></div>
            <div class="g-infolist-item-desc">Collaboratively administrate empowered markets via plug-and-play networks</div>
          </div>
        </div>
      </div>
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

![](assets/page_portfolio_5.jpeg)

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
  <h2 class="g-layercontent-title">100% Satisfaction Guaranteed</h2>
  <div class="g-layercontent-subtitle">Will You be the Next to Join Our Happy Clients?</div>
  <a href="http://www.rockettheme.com/wordpress/themes/isotope" class="button button-2">Join Now</a>
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

![](assets/page_aboutus_8.jpeg)

:   1. **Logo (Particle)** [20%, 2%, se]
    2. **Horizontal Menu (Particle)** [20%, 35%, se]
    3. **Social (Particle)** [20%, 67%, se]

This area of the page is made up of three particles.

### Logo (Particle)

### Particle Settings

| Field         | Setting               |
| :-----        | :-----                |
| Particle Name | `Logo`                |
| URL           | Blank                 |
| Rel           | Blank                 |
| Image         | Custom                |
| Alt           | `Isotope`              |
| Text          | `Isotope`              |
| CSS Classes   | `g-loto` `g-logo-alt` |

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `25%`       |

### Horizontal Menu (Particle)

### Particle Settings

| Field            | Setting               |
| :-----           | :-----                |
| Particle Name    | `Horizontal Menu`     |
| CSS Classes      | Blank                 |
| Target           | New Window            |
| Menu Item 1 Name | `Gantry`              |
| Menu Item 1 Text | `Gantry`              |
| Menu ITem 1 Link | `http://gantry.org`   |

### Block Settings

| Option         | Setting                  |
| :----------    | :----------              |
| CSS ID         | Blank                    |
| CSS Classes    | `g-horizontalmenu-block` |
| Variations     | Center                   |
| Tag Attributes | Blank                    |
| Fixed Size     | Unchecked                |
| Block Size     | `50%`                    |

### Social (Particle)

### Particle Settings

| Field                | Setting                               |
| :-----               | :-----                                |
| Particle Name        | `Social`                              |
| CSS Classes          | `social`                              |
| Title                | Blank                                 |
| Social Item 1 Name   | `Facebook`                            |
| Social Item 1 Text   | Blank                                 |
| Social Item 1 Link   | `http://www.facebook.com/RocketTheme` |
| Social Item 1 Target | New Window                            |

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `25%`       |