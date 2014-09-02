---
title: Nuance: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

Introduction
-----

The **About Us** example page demonstrates how you can create a beautiful page with the Nuance template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][aboutusmenu]

The **About Us** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `about-us` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][aboutuspage4]

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Nuance, the Powerful Template</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/nuance" class="readon">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][aboutuspage]

:   1. **Custom HTML - About Us** [13%, 45%, se]
    2. **Custom HTML - About Us: Introduction** [20%, 13%, se]
    3. **Article Content** [34%, 13%, se]
    4. **Custom HTML - Our Mission** [46%, 13%, se]
    5. **Custom HTML - We Always Try to Create a Difference** [66%, 28%, se]
    6. **Custom HTML - Nuance Demo** [74%, 13%, se]
    7. **Custom HTML - Sample Contact Info** [74%, 51%, se]

1. [Custom HTML - About Us](aboutus.md#custom-html---about-us)

2. [Custom HTML - About Us: Introduction](aboutus.md#custom-html---about-us:-introduction)

3. [Article Content](aboutus.md#mainbody)

4. [Custom HTML - Our Mission](aboutus.md#custom-html---about-us:-our-mission---our-values---our-solution)

5. [Custom HTML - We Always Try to Create a Difference](aboutus.md#custom-html---we-always-try-to-create-a-difference)

6. [Custom HTML - Nuance Demo](aboutus.md#custom-html---nuance-demo)

7. [Custom HTML - Sample Contact Info](aboutus.md#custom-html---sample-contact-info)    

### Custom HTML - About Us

![][aboutuspage2]

#### Module

| Option      | Setting                                                       |
| :---------- | :-----------                                                  |
| Title       | `About Us[span class="rt-title-tag"]Welcome to Nuance[/span]` |
| Show Title  | Yes                                                           |
| Position    | showcase-a                                                    |
| Status      | Published                                                     |
| Access      | Public                                                        |

#### Content

~~~ .html
&nbsp;
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                                                        |
| :----------         | :----------                                                                    |
| Module Class Suffix | `rt-top-large-padding nomarginall rt-center rt-title-large rt-nomodulecontent` |

### Custom HTML - About Us: Introduction

![][aboutuspage3]

#### Module

| Option      | Setting                                      |
| :---------- | :-----------                                 |
| Title       | `About Us: Introduction - Mission Statement` |
| Show Title  | Hide                                         |
| Position    | maintop-a                                    |
| Status      | Published                                    |
| Access      | Public                                       |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-01.jpg" alt="image" /></span>
            </div>
        </div>

        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Introduction</h3>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. Quickly drive clicks-and-mortar catalysts for change.</p>
                <div class="hidden-tablet">
                    <h3>More About Us</h3>
                    <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                      |
| :----------         | :----------                                  |
| Module Class Suffix | `box2 nomarginall rt-title-center rt-square` |

### Custom HTML - About Us: Our Mission - Our Values - Our Solution

![][aboutuspage5]

#### Module

| Option      | Setting                                             |
| :---------- | :-----------                                        |
| Title       | `About Us: Our Mission - Our Values - Our Solution` |
| Show Title  | Hide                                                |
| Position    | mainbottom-a                                        |
| Status      | Published                                           |
| Access      | Public                                              |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-02.jpg" alt="image" /></span>
                <h4>Our Mission</h4>
                <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-03.jpg" alt="image" /></span>
                <h4>Our Values</h4>
                <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-04.jpg" alt="image" /></span>
                <h4>Our Solution</h4>
                <p>Engage worldwide methodologies with web-enabled technology. Interactively coordinate proactive e-commerce via process-centric outside the box thinking.</p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### Custom HTML - We Always Try to Create a Difference

![][aboutuspage6]

#### Module

| Option      | Setting                                |
| :---------- | :-----------                           |
| Title       | `We Always Try to Create a Difference` |
| Show Title  | Show                                   |
| Position    | extension-a                            |
| Status      | Published                              |
| Access      | Public                                 |

#### Content

~~~ .html
<p>Utilized with Versatile and Flexible Features Powered by the Gantry Framework.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/nuance" class="readon largemargintop">Download Nuance</a></p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Nuance Demo

![][aboutuspage7]

#### Module

| Option      | Setting       |
| :---------- | :-----------  |
| Title       | `Nuance Demo` |
| Show Title  | Yes           |
| Position    | footer-a      |
| Status      | Published     |
| Access      | Public        |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Nuance can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/nuance">Nuance RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![][aboutuspage8]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Sample Contact Info` |
| Show Title  | Yes                   |
| Position    | footer-b              |
| Status      | Published             |
| Access      | Public                |

#### Content

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Nuance Theme, LLC</span><br />
            <span>123 Joomla! Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

[aboutuspage]: assets/page_aboutus.jpeg
[aboutusmenu]: assets/page_aboutus_menu.jpeg
[aboutuspage2]: assets/page_aboutus_1.jpeg
[aboutuspage3]: assets/page_aboutus_2.jpeg
[aboutuspage4]: assets/page_aboutus_3.jpeg
[aboutuspage5]: assets/page_aboutus_4.jpeg
[aboutuspage6]: assets/page_aboutus_5.jpeg
[aboutuspage7]: assets/page_aboutus_6.jpeg
[aboutuspage8]: assets/page_aboutus_7.jpeg
[aboutuspage9]: assets/page_aboutus_8.jpeg
[aboutuspage10]: assets/page_aboutus_9.jpeg
[aboutuspage11]: assets/page_aboutus_10.jpeg
[aboutuspage12]: assets/page_aboutus_12.jpeg
[aboutuspage13]: assets/page_aboutus_13.jpeg
[aboutuspage14]: assets/page_aboutus_14.jpeg
