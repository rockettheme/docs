---
title: Antares: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Antares Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/antares:Antares

---

# Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Antares template. Here is some information to help you replicate this page as it appears in the demo.

# Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_blog.png)

:   1. **Header - Custom HTML (Module)** [3%, 45%, se]
    2. **Mainbar - Page Content** [8%, 5%, se]
    3. **Aside - RokAjaxSearch (Module)** [8%, 75%, se]
    4. **Aside - Custom HTML (Module)** [12%, 75%, se]
    5. **Aside - Login (Module)** [20%, 75%, se]
    6. **Aside - Who's Online (Module)** [27%, 75%, se]
    7. **Extension - Info List (Particle)** [88%, 35%, se]
    8. **Bottom - Custom HTML (Module)** [78%, 8%, se]
    7. **Bottom - Newsletter (Particle)** [78%, 35%, se]
    8. **Bottom - Custom HTML (Module)** [78%, 65%, se]

1. [Header](#header-section)
2. [Mainbar](#mainbar-section)
3. [Aside](#aside-section)
4. [Extension](#extension-section)
5. [Bottom](#bottom-section)

# Header Section

![](assets/page_blog_1.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting         |
|:-----------|:----------------|
| Title      | `Blog - Header` |
| Show Title | Hide            |
| Position   | `header-a`      |
| Status     | Published       |

### Particle Settings

| Option                              | Setting                                |
|:------------------------------------|:---------------------------------------|
| CSS Classes                         | `center`, `g-layercontent`, `noborder` |
| Title                               | Blank                                  |
| Intro                               | Blank                                  |
| Grid Column                         | 1 Column                               |
| Info Lists Item 1 Name              | `Our Blog`                             |
| Info Lists Item 1 Image             | Blank                                  |
| Info Lists Item 1 Image Location    | Left                                   |
| Info Lists Item 1 Text Style        | Header                                 |
| Info Lists Item 1 Image Style       | Compact                                |
| Info Lists Item 1 Description       | `Read the Latest News`                 |
| Info Lists Item 1 Tag               | Blank                                  |
| Info Lists Item 1 Sub Tag           | Blank                                  |
| Info Lists Item 1 Label             | Blank                                  |
| Info Lists Item 1 Link              | Blank                                  |
| Info Lists Item 1 Icon              | Blank                                  |
| Info Lists Item 1 Read More Classes | Blank                                  |

# Mainbar Section

![](assets/page_blog_2.png)

The **Mainbar** section includes several articles assigned to the **Joomla Blog** category, displayed through the **Page Content** particle. Here are the settings found in the **Dramatically visualize customer directed convergence without revolutionary ROI** article.

| Option   | Setting                                                                          |
|:---------|:---------------------------------------------------------------------------------|
| Title    | `Dramatically visualize customer directed convergence without revolutionary ROI` |
| Alias    | `dramatically-visualize-customer-directed-convergence-without-revolutionary-roi` |
| Status   | Published                                                                        |
| Featured | No                                                                               |
| Category | `Joomla Blog`                                                                    |

**Content Body**

~~~ .html
<p><img src="images/rocketlauncher/pages/blog/img-01.jpg" alt="Sample Blog"></p>
<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI. Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
<a class="button" href="#">Read More</a>
~~~

# Aside Section

![](assets/page_blog_3.png)

:   1. **RokAjaxSearch (Module)** [7%, 15%, se]
    2. **Custom HTML (Module)** [20%, 15%, se]
    3. **Login (Module)** [50%, 15%, se]
    4. **Who's Online (Module)** [80%, 15%, se]

This area of the page consists of the **Aside** section, which sits to the right of the **Mainbar** section in the **Layout Manager**.

Here is a breakdown of the modules used in the `aside` module position assigned to the **Aside** section in the **Layout Manager** for the **Blog** sample page:

* RokAjaxSearch (Module)
* Custom HTML (Module)
* Login (Module)
* Who's Online (Module)

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

## RokAjaxSearch (Module)

The Site Search area of the front page is a **mod_rokajaxsearch** module that allows visitors to search your site using the powerful RokAjaxSearch tool.

### Details

| Option     | Setting           |
|:-----------|:------------------|
| Title      | `Search Our Site` |
| Show Title | Show              |
| Position   | aside             |
| Status     | Published         |
| Access     | Public            |

### Module

| Option                            | Setting                                                  |
|:----------------------------------|:---------------------------------------------------------|
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Light                                                    |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

### Advanced

| Option              | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Custom HTML (Module)

### Details

| Field      | Setting                                 |
|:-----------|:----------------------------------------|
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

| Option                    | Setting |
|:--------------------------|:--------|
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

| Option              | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Login (Module)

### Details

| Field      | Setting   |
|:-----------|:----------|
| Title      | `Login`   |
| Show Title | Show      |
| Position   | `aside`   |
| Status     | Published |

### Options

| Field                   | Setting |
|:------------------------|:--------|
| Pre-text                | Blank   |
| Post-text               | Blank   |
| Login Redirection Page  | Default |
| Logout Redirection Page | Default |
| Show Greeting           | Yes     |
| Show Name/Username      | Name    |
| Encrypt Login Form      | No      |
| Display Labels          | Icons   |

### Advanced

| Field               | Setting |
|:--------------------|:--------|
| Module Class Suffix | `box3`  |

## Who's Online (Module)

### Details

| Field      | Setting        |
|:-----------|:---------------|
| Title      | `Who's Online` |
| Show Title | Show           |
| Position   | `aside`        |
| Status     | Published      |

### Options

| Field   | Setting             |
|:--------|:--------------------|
| Display | # of Guests / Users |


### Advanced

| Field               | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Extension Section

![](assets/page_blog_4.png)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                   |
|:-----------|:--------------------------|
| Title      | `Blog - Share Some Ideas` |
| Show Title | Hide                      |
| Position   | `bottom-a`                |
| Status     | Published                 |

#### Particle Settings

| Option                              | Setting                                                       |
|:------------------------------------|:--------------------------------------------------------------|
| CSS Classes                         | `center`, `g-layercontent`, `noborder`                        |
| Title                               | Blank                                                         |
| Intro                               | Blank                                                         |
| Grid Column                         | 1 Column                                                      |
| Info Lists Item 1 Name              | `Share Some Ideas`                                            |
| Info Lists Item 1 Image             | Blank                                                         |
| Info Lists Item 1 Image Location    | Left                                                          |
| Info Lists Item 1 Text Style        | Header                                                        |
| Info Lists Item 1 Image Style       | Compact                                                       |
| Info Lists Item 1 Description       | `Do You Have a Tip or an Idea for a Story? Tell Us About It.` |
| Info Lists Item 1 Tag               | Blank                                                         |
| Info Lists Item 1 Sub Tag           | Blank                                                         |
| Info Lists Item 1 Label             | `Submit Article`                                              |
| Info Lists Item 1 Link              | `http://www.rockettheme.com/joomla/templates/antares`          |
| Info Lists Item 1 Icon              | Blank                                                         |
| Info Lists Item 1 Read More Classes | Blank                                                         |

## Bottom Section

![](assets/page_aboutus_6.png)

:   1. **Custom HTML (Module)** [20%, 2%, se]
    2. **Newsletter (Particle)** [20%, 35%, se]
    3. **Custom HTML (Module)** [20%, 67%, se]

This area of the page is made up of three items. Two of them are **Custom HTML** modules, with a **Newsletter** particle in-between. These items are placed in the **Bottom A**, **Bottom B**, and **Bottom C** module positions which each are set at `33.3%` width.

### Custom HTML (Module)

The **Custom HTML** module here was placed in the **Bottom A** module position. The module position is created within the layout manager by using a **Module Position** particle. The particle is assigned `bottom-a` as a key and `gantry` as its Chrome.

Below, you will find the module settings we used in the demo:

### Module Settings

| Field      | Setting                                                                                                                                  |
| :-----     | :-----                                                                                                                                   |
| Title      | `About Antares`                                                                                                                          |
| Content    | `Antares is available for purchase or part of a club membership from RocketTheme, inclusive of the RocketLauncher, template and addons.` |
| Show Title | Show                                                                                                                                     |
| Position   | bottom-a                                                                                                                                 |

### Newsletter (Particle)

The **Newsletter** particle here was placed in the **Bottom B** module position. The module position is created within the layout manager by using a **Particle Position** particle. The particle is assigned `bottom-b` as a key and `gantry` as its Chrome.

Below, you will find the particle settings we used in the demo:

### Particle Settings

| Field          | Setting                                                                                       |
| :-----         | :-----                                                                                        |
| Particle Name  | `Newsletter`                                                                                  |
| CSS Classes    | Blank                                                                                         |
| Title          | `Subscribe Here`                                                                              |
| Heading Text   | `Subscribe to our newsletter and stay updated on the latest developments and special offers!` |
| InputBox Text  | `Email Address`                                                                               |
| Button Text    | `Join`                                                                                        |
| Feedburner URI | Custom                                                                                        |
| Button Classes | `button-4`                                                                                    |

### Custom HTML (Module)

The **Custom HTML** module here was placed in the **Bottom C** module position. The module position is created within the layout manager by using a **Module Position** particle. The particle is assigned `bottom-c` as a key and `gantry` as its Chrome.

Below, you will find the module settings we used in the demo:

### Module Settings

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `Sample Sitemap` |
| Show Title | Show             |
| Position   | `bottom-c`       |

**Content**

~~~ .html
<div class="g-grid g-sample-sitemap">
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="index.php">Home</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=105">Features</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=106"><span class="hidden-tablet">Typography</span><span class="visible-tablet">Content</span></a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=168">Particles</a></li>
      <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=107">Variations</a></li>
    </ul>
  </div>
  <div class="g-block">
    <ul class="nomarginall noliststyle">
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=106">Buttons</a></li>
      <li><a href="index.php?option=com_gantry5&amp;view=custom&amp;Itemid=105">Pages</a></li>
      <li><a href="http://www.rockettheme.com/docs/joomla/templates/antares">Guide</a></li>
      <li><a href="http://www.rockettheme.com/forum/joomla-template-antares">Support</a></li>
      <li><a href="http://www.rockettheme.com/joomla/templates/antares">Download</a></li>
    </ul>   
  </div>  
</div>
~~~
