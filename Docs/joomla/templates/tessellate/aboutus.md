---
title: Tessellate: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

The **About Us** example page demonstrates how you can create a beautiful page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][aboutuspage2]

The **About Us** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `about-us` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][aboutuspage7]

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Tessellate, the Powerful Template</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][aboutuspage]

:   1. **RokAjaxSearch** [5%, 25%, se]
    2. **Custom HTML - About Us** [14%, 45%, se]
    3. **Breadcrumbs** [21%, 11%, se]
    4. **Custom HTML - About Us: Introduction** [24%, 11%, se]
    5. **Article Content** [38%, 11%, se]
    6. **Custom HTML - Our Mission** [50%, 11%, se]
    7. **Custom HTML - We Always Try to Create a Difference** [70%, 28%, se]
    8. **Custom HTML - Tessellate Demo** [77%, 10%, se]
    9. **Custom HTML - Sample Contact Info** [77%, 51%, se]
    10. **Menu - Copyright Menu** [92%, 75%, se]

1. [RokAjaxSearch](aboutus.md#rokajaxsearch)
2. [Custom HTML - About Us](aboutus.md#custom-html---about-us)
3. [Breadcrumbs](aboutus.md#breadcrumbs)
4. [Custom HTML - About Us: Introduction](aboutus.md#custom-html---about-us:-introduction)
5. [Article Content](aboutus.md#mainbody)
6. [Custom HTML - Our Mission](aboutus.md#custom-html---about-us:-our-mission---our-values---our-solution)
7. [Custom HTML - We Always Try to Create a Difference](aboutus.md#custom-html---we-always-try-to-create-a-difference)
8. [Custom HTML - Tessellate Demo](aboutus.md#custom-html---tessellate-demo)
9. [Custom HTML - Sample Contact Info](aboutus.md#custom-html---sample-contact-info)
10. [Menu - Copyright Menu](aboutus.md#menu---copyright-menu)

### RokAjaxSearch

![][aboutuspage3]

#### Details

|   Option   |      Setting       |
| :--------- | :----------------- |
| Title      | `FP RokAjaxSearch` |
| Show Title | Hide               |
| Position   | header-b           |
| Status     | Published          |
| Access     | Public             |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Module

| Option                            | Setting                                                  |
| :----------                       | :----------                                              |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
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

### Custom HTML - About Us

![][aboutuspage4]

#### Module

| Option      | Setting                                                          |
| :---------- | :-----------                                                     |
| Title       | `About Us[span class="rt-title-tag"]Welcome to Tessellate[/span]` |
| Show Title  | Yes                                                              |
| Position    | top-a                                                            |
| Status      | Published                                                        |
| Access      | Public                                                           |

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

| Option                    | Setting                                       |
| :----------               | :----------                                   |
| Module Class Suffix       | `rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![][aboutuspage5]

#### Module

| Option              | Setting       |
| :----------         | :-----------  |
| Title               | `Breadcrumbs` |
| Show You Are Here   | No            |
| Show Home           | Yes           |
| Text for Home Entry |               |
| Show Last           | Yes           |
| Text Separator      |               |
| Show Title          | Hide          |
| Status              | Published     |
| Access              | Public        |

##### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### Custom HTML - About Us: Introduction

![][aboutuspage6]

#### Module

| Option      | Setting                                      |
| :---------- | :-----------                                 |
| Title       | `About Us: Introduction - Mission Statement` |
| Show Title  | Hide                                         |
| Position    | feature-a                                    |
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

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-title-center` |

### Custom HTML - About Us: Our Mission - Our Values - Our Solution

![][aboutuspage8]

#### Module

| Option      | Setting                                             |
| :---------- | :-----------                                        |
| Title       | `About Us: Our Mission - Our Values - Our Solution` |
| Show Title  | Hide                                                |
| Position    | mainbottom-a                                           |
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

![][aboutuspage9]

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

<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon largemargintop">Download Tessellate</a></p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `rt-center`    |

### Custom HTML - Tessellate Demo

![][aboutuspage10]

#### Module

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Tessellate Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Tessellate can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/tessellate">Tessellate RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][aboutuspage11]

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
            <span>Tessellate Theme, LLC</span><br />
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

### Menu - Copyright Menu

![][aboutuspage12]

### Details

| Option      | Setting             |
| :---------- | :----------         |
| Title       | `FP Copyright Memu` |
| Show Title  | Hide                |
| Position    | copyright-b         |
| Status      | Published           |
| Access      | Public              |

### Basic Options

| Option              | Setting        |
| :----------         | :----------    |
| Select Menu         | Copyright Menu |
| Base Item           | Current        |
| Start Level         | 1              |
| End Level           | All            |
| Show Sub-menu Items | Yes            |

### Advanced Options

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `rt-horizmenu` |

[aboutuspage]: assets/page_aboutus.jpeg
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
[aboutuspage12]: assets/demo_21.jpeg
[aboutuspage13]: assets/page_aboutus_12.jpeg
[aboutuspage14]: assets/page_aboutus_13.jpeg
