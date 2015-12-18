---
title: Isotope: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Isotope Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/isotope:Isotope

---

# Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Isotope theme. Here is some information to help you replicate this page as it appears in the demo.

# Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_blog.png)

:   1. **Header - Info List (Particle)** [3%, 45%, se]
    2. **Mainbar - Page Content** [7%, 5%, se]
    3. **Aside - RokAjaxSearch (Widget)** [7%, 75%, se]
    4. **Aside - Custom HTML (Widget)** [11%, 75%, se]
    5. **Aside - Login Form (Particle)** [19%, 75%, se]
    6. **Bottom - Custom HTML (Particle)** [87%, 35%, se]
    7. **Bottom - Text (Widget)** [93%, 8%, se]
    8. **Bottom - Newsletter (Particle)** [93%, 35%, se]
    9. **Bottom - Text (Widget)** [93%, 65%, se]

1. [Header](#header-section)
2. [Mainbar](#mainbar-section)
3. [Aside](#aside-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)
6. [Footer](#footer-section)

# Header Section

![](assets/page_blog_1.jpeg)

This area of the page is a **Info List** particle. You will find the settings used in our demo below.

### Particle Settings

| Field                 | Setting                              |
| :-----                | :-----                               |
| Particle Name         | `Blog - Header`                      |
| CSS Classes           | `center` `g-layercontent` `noborder` |
| Title                 | Blank                                |
| Intro                 | Blank                                |
| Grid Column           | 1 Column                             |
| Item 1 Name           | `Our Blog`                           |
| Item 1 Image          | Blank                                |
| Item 1 Image Location | Left                                 |
| Item 1 Text Style     | Header                               |
| Item 1 Image Style    | Compact                              |
| Item 1 Description    | `Read the Latest News`               |
| Item 1 Tag            | Blank                                |
| Item 1 Sub Tag        | Blank                                |
| Item 1 Label          | Blank                                |
| Item 1 Link           | Blank                                |
| Item 1 Icon           | Blank                                |
| Read More Classes     | Blank                                |

### Block Settings

| Option         | Setting     |
| :----------    | :---------- |
| CSS ID         | Blank       |
| CSS Classes    | Blank       |
| Variations     | Blank       |
| Tag Attributes | Blank       |
| Fixed Size     | Unchecked   |
| Block Size     | `100%`      |

# Mainbar Section

![](assets/page_blog_2.jpeg)

The **Mainbar** section includes several articles assigned to the **WordPress Blog** category, displayed through the **Page Content** particle. Here are the settings found in the **Dramatically visualize customer directed convergence without revolutionary ROI** article.

| Option   | Setting                                                                          |
| :-----   | :-----                                                                           |
| Title    | `Dramatically visualize customer directed convergence without revolutionary ROI` |
| Alias    | `dramatically-visualize-customer-directed-convergence-without-revolutionary-roi` |
| Status   | Published                                                                        |
| Featured | No                                                                               |
| Category | `WordPress Blog`                                                                    |

**Content Body**

~~~ .html
<p><img src="images/rocketlauncher/pages/blog/img-01.jpg" alt="Sample Blog"></p>
<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI. Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
<a class="button" href="#">Read More</a>
~~~

# Aside Section

![](assets/page_blog_3.png)

:   1. **RokAjaxSearch (Widget)** [7%, 4%, se]
    2. **Custom HTML (Widget)** [20%, 4%, se]
    3. **Login (Widget)** [60%, 4%, se]

This area of the page consists of the **Aside** section, which sits to the right of the **Mainbar** section in the **Layout Manager**.

Here is a breakdown of the widgets used in the `aside` widget position assigned to the **Aside** section in the **Layout Manager** for the **Blog** sample page:

* RokAjaxSearch (Widget)
* Text (Widget)
* Login Form (Particle)

## RokAjaxSearch (Widget)

The Site Search area of the front page is a **RokAjaxSearch** widget that allows visitors to search your site using the powerful RokAjaxSearch tool.

### Details

| Option      | Setting           |
| :---------- | :----------       |
| Title       | `Search Our Site` |

## Custom HTML (Widget)

### Details

| Field                        | Setting           |
| :-----                       | :-----            |
| Title                        | `Gantry 5 Guides` |
| Automatically Add Paragraphs | Unchecked         |
| Custom Class(es)             | Blank             |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
  <li><a href="http://docs.gantry.org/gantry5/basics/installation">Installation</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/gantry-admin">Gantry Admin Configuration</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/styles">Theme Styles</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/settings">Theme Settings Panel</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/layout-manager">Layout Manager</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/menu-editor">Menu Editor</a></li>
  <li><a href="http://docs.gantry.org/gantry5/configure/assignments">Assignments</a></li>
  <li><a href="http://docs.gantry.org/gantry5/particles/particles">Gantry Particles</a></li>
  <li><a href="http://docs.gantry.org/gantry5/particles/mobile-menu">Mobile Menu</a></li>
  <li><a href="http://docs.gantry.org/gantry5/advanced">Advanced Customizaton</a></li>
</ul>
~~~

## Gantry 5 Particle (Login Form) (Widget)

### Details

| Field       | Setting  |
| :-----      | :-----   |
| CSS Classes | Blank    |
| Title       | `Login`  |
| Greeting    | `Hi, %s` |
| Pre Text    | Blank    |
| Post Text   | Blank    |

## Extension Section

![](assets/page_blog_4.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

This area of the page is a **Info List** particle. You will find the settings used in our demo below.

### Particle Settings

| Field                 | Setting                                                       |
| :-----                | :-----                                                        |
| Particle Name         | `Blog - Share Some Ideas`                                     |
| CSS Classes           | `center` `g-layercontent` `noborder`                          |
| Title                 | Blank                                                         |
| Intro                 | Blank                                                         |
| Grid Column           | 1 Column                                                      |
| Item 1 Name           | `Share Some Ideas`                                            |
| Item 1 Image          | Blank                                                         |
| Item 1 Image Location | Left                                                          |
| Item 1 Text Style     | Header                                                        |
| Item 1 Image Style    | Compact                                                       |
| Item 1 Description    | `Do You Have a Tip or an Idea for a Story? Tell Us About It.` |
| Item 1 Tag            | Blank                                                         |
| Item 1 Sub Tag        | Blank                                                         |
| Item 1 Label          | `Submit Article`                                              |
| Item 1 Link           | `http://www.rockettheme.com/wordpress/themes/isotope`           |
| Item 1 Icon           | Blank                                                         |
| Read More Classes     | Blank                                                         |

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

![](assets/page_aboutus_8.png)

:   1. **Text (Widget)** [20%, 2%, se]
    2. **Newsletter (Particle)** [20%, 35%, se]
    3. **Text (Widget)** [20%, 67%, se]

This area of the page is made up of three particles.

### Text (Widget)

The **Text** widget here was placed in the **Bottom A** widget position. The widget position is created within the layout manager by using a **Widget Position** particle. The particle is assigned `bottom-a` as a key and `gantry` as its Chrome.

Below, you will find the widget settings we used in the demo:

### Widget Settings

| Field                        | Setting                                                                                                                              |
| :-----                       | :-----                                                                                                                               |
| Title                        | `About Isotope`                                                                                                                        |
| Content                      | `Isotope is available for purchase or part of a club membership from RocketTheme, inclusive of the RocketLauncher, theme and plugins.` |
| Automatically Add Paragraphs | Unchecked                                                                                                                            |
| Custom class(es)             | Blank                                                                                                                                |

### Newsletter (Particle)

The **Newsletter** particle here was placed in the **Bottom B** widget position. The widget position is created within the layout manager by using a **Widget Position** particle. The particle is assigned `bottom-b` as a key and `gantry` as its Chrome.

Below, you will find the particle settings we used in the demo:

### Particle Settings

| Field          | Setting                                                                                       |
| :-----         | :-----                                                                                        |
| Particle Name  | `Newsletter`                                                                                  |
| CSS Classes    | Blank                                                                                         |
| Heading Text   | `Subscribe to our newsletter and stay updated on the latest developments and special offers!` |
| InputBox Text  | `Email Address`                                                                               |
| Button Text    | `Join`                                                                                        |
| Feedburner URI | Custom                                                                                        |
| Button Classes | `button-4`                                                                                    |

### Text (Widget)

The **Text** widget here was placed in the **Bottom C** widget position. The widget position is created within the layout manager by using a **Widget Position** particle. The particle is assigned `bottom-c` as a key and `gantry` as its Chrome.

Below, you will find the widget settings we used in the demo:

### Widget Settings

| Field                        | Setting                                                                                                                              |
| :-----                       | :-----                                                                                                                               |
| Title                        | `Sample Sitemap`                                                                                                                        |
| Automatically Add Paragraphs | Unchecked                                                                                                                            |
| Custom class(es)             | Blank                                                                                                                                |

**Content**

~~~ .html
<div class="g-grid g-sample-sitemap">
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/">Home</a></li>
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/overview/">Features</a></li>
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/typography/"><span class="hidden-tablet">Typography</span><span class="visible-tablet">Content</span></a></li>
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/particles/">Particles</a></li>
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/block-variations/">Variations</a></li>
    </ul>
  </div>
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/typography/">Buttons</a></li>
      <li><a href="http://demo.rockettheme.com/live/wordpress/isotope/overview/">Pages</a></li>
      <li><a href="http://www.rockettheme.com/docs/wordpress/themes/isotope">Guide</a></li>
      <li><a href="http://www.rockettheme.com/forum/wordpress-theme-isotope">Support</a></li>
      <li><a href="http://www.rockettheme.com/wordpress/themes/isotope">Download</a></li>
    </ul>
  </div>
</div>
~~~