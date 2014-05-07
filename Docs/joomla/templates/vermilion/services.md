---
title: Vermilion: Recreating the Demo - Services Page
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

Introduction
-----

The **Services** example page demonstrates how you can create a content rich page with the Vermilion template. Here is some information to help you replicate this page as it appears in the demo.

Page Display Options
-----

![][servicespage2]

The **Services** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `services` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][servicespage3]

The page's content body is set in the **Services** article. You will find the content used in the article below.

~~~ .html
<h3>Why Should You Choose Us?</h3>
<p>Efficiently unleash cross-media information without cross-media value.
Quickly maximize timely deliverables for real-time schemas. Dramatically
maintain clicks-and-mortar solutions without functional solutions.</p>
<p>Completely synergize resource sucking relationships via premier niche
markets. Professionally cultivate one-to-one customer service with robust
ideas. Dynamically innovate resource-leveling customer service for state of the
art customer service.</p>
<p><a class="readon" href=
"http://www.rockettheme.com/joomla/templates/vermilion">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][servicespage]

:   1. **Custom HTML - Services** [11%, 45%, se]
    2. **Breadcrumbs** [16%, 18%, se]
    3. **Custom HTML - Services: Chart JS** [19%, 18%, se]
    4. **Custom HTML - Our Core Service** [37%, 18%, se]
    5. **Article Content** [50%, 18%, se]
    6. **Custom HTML - Grid System** [60%, 18%, se]
    7. **Custom HTML - Save Your Time and Effort** [73%, 40%, se]
    8. **Custom HTML - Vermilion Demo** [80%, 18%, se]
    9. **Custom HTML - Sample Contact Info** [80%, 52%, se]

1. [Custom HTML - Services](services.md#custom-html---services)
2. [Breadcrumbs](services.md#breadcrumbs)
3. [Custom HTML - Services: Chart JS](services.md#custom-html---services:-chart-js)
4. [Custom HTML - Our Core Service](services.md#custom-html---our-core-service)
5. [Article Content](services.md#mainbody)
6. [Custom HTML - Grid System](services.md#custom-html---grid-system)
7. [Custom HTML - Save Your Time and Effort](services.md#custom-html---save-your-time-and-effort)
8. [Custom HTML - Vermilion Demo](services.md#custom-html---vermilion-demo)
9. [Custom HTML - Sample Contact Info](services.md#custom-html---sample-contact-info)

### Custom HTML - Services

![][servicespage4]

#### Module 

| Option      | Setting                                                    |
| :---------- | :-----------                                               |
| Title       | `Services[span class="rt-title-tag"]What We Can Do[/span]` |
| Show Title  | Yes                                                        |
| Position    | top-a                                                      |
| Status      | Published                                                  |
| Access      | Public                                                     |

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

![][servicespage5]

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

### Custom HTML - Services: Chart JS

![][servicespage6]

>> More information about Chart.js support can be found [here](charts.md).

#### Module 

| Option      | Setting              |
| :---------- | :-----------         |
| Title       | `Services: Chart JS` |
| Show Title  | Hide                 |
| Position    | feature-a            |
| Status      | Published            |
| Access      | Public               |

#### Content

~~~ .html
<p>The two charts shown below are the sample chart canvas based on Chart.js.
Chart.js is an easy, object oriented client side graphs for designers and
developers. For more information how to create great looking charts using
Chart.js, please visit <a href="http://www.chartjs.org/">Chart.js</a> homepage
or download the script <a href=
"https://github.com/nnnick/Chart.js">here</a>.</p>
<p>&nbsp;</p>
<div class="gantry-row">
    &nbsp;
</div>
<div class="clear">
    &nbsp;
</div>
<p>&nbsp;</p>
<p class="success">NOTE: The canvas only works on modern browsers (Firefox,
Opera, Chrome, Safari, and Internet Explorer 9+) that support the HTML5 canvas
element. <a href="http://www.w3schools.com/html/html5_canvas.asp" target=
"_blank">Internet Explorer 8 and earlier versions, do not support the canvas
element.</a></p>
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

### Custom HTML - Our Core Service

![][servicespage7]

#### Module 

| Option      | Setting                                       |
| :---------- | :-----------                                  |
| Title       | `Services: Our Core Service - We Do Our Best` |
| Show Title  | Hide                                          |
| Position    | maintop-a                                     |
| Status      | Published                                     |
| Access      | Public                                        |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Our Core Service</h3>
            <p>Globally incubate standards compliant channels before scalable
            benefits. Quickly disseminate superior deliverables whereas
            web-enabled applications.</p>
            <div class="hidden-tablet">
                <h3>We Do Our Best</h3>
                <p>Proactively envisioned multimedia based expertise and
                cross-media growth strategies.</p>
                <ul>
                    <li>HTML5 &amp; CSS3</li>
                    <li>Gantry Framework</li>
                    <li>RokSprocket Styling</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img alt="image" src=
            "images/rocketlauncher/pages/services/img-01.jpg"></span>
        </div>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
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

### Custom HTML - Grid System

![][servicespage8]

#### Module 

| Option      | Setting                                                                          |
| :---------- | :-----------                                                                     |
| Title       | `Services: Grid System - Custom Interface - Flexible Layouts - Ultimate Control` |
| Show Title  | Hide                                                                             |
| Position    | mainbottom-a                                                                     |
| Status      | Published                                                                        |
| Access      | Public                                                                           |

#### Content

~~~ .html
<div class="gantry-width-25">
    <img alt="image" src="images/rocketlauncher/pages/services/img-02.jpg">
    <div class="gantry-width-spacer">
        <h4>Grid System</h4>
        <p>Objectively innovate empowered manufactured products with parallel
        platforms.</p>
    </div>
</div>
<div class="gantry-width-25">
    <img alt="image" src="images/rocketlauncher/pages/services/img-03.jpg">
    <div class="gantry-width-spacer">
        <h4>Custom Interface</h4>
        <p>Proactively envisioned multimedia based expertise and effective
        cross-media strategies.</p>
    </div>
</div>
<div class="gantry-width-25">
    <img alt="image" src="images/rocketlauncher/pages/services/img-04.jpg">
    <div class="gantry-width-spacer">
        <h4>Flexible Layouts</h4>
        <p>Interactively coordinate proactive e-commerce via process-centric
        outside the box.</p>
    </div>
</div>
<div class="gantry-width-25">
    <img alt="image" src="images/rocketlauncher/pages/services/img-05.jpg">
    <div class="gantry-width-spacer">
        <h4>Ultimate Control</h4>
        <p>Holistically pontificate installed base portals after maintainable
        affordable products.</p>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `nopaddingall` |

### Custom HTML - Save Your Time and Effort

![][servicespage9]

#### Module 

| Option      | Setting                     |
| :---------- | :-----------                |
| Title       | `Save Your Time and Effort` |
| Show Title  | Show                        |
| Position    | extension-a                 |
| Status      | Published                   |
| Access      | Public                      |

#### Content

~~~ .html
<p>We Always Create Real Value and Work with Passion</p>
<p><a class="readon largemargintop" href="http://www.rockettheme.com/joomla/templates/vermilion">Purchase Vermilion</a></p>
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

### Custom HTML - Vermilion Demo

![][servicespage10]

#### Module 

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Vermilion Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Vermilion can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/vermilion">Vermilion RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][servicespage11]

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
<div class="gantry-width-40">
<div class="gantry-width-spacer"><img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" /></div>
</div>
<div class="gantry-width-60">
<div class="gantry-width-spacer"><span class="rt-intro-text">+1(123)456-5555-555</span><br /> Vermilion Theme, LLC<br /> 123 Joomla! Boulevard<br /> Seattle, WA 00000, USA<br /> <a href="#">noreply@domain.com</a></div>
</div>
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

[servicespage]: assets/page_services.jpeg
[servicespage2]: assets/page_services_2.jpeg
[servicespage3]: assets/page_services_3.jpeg
[servicespage4]: assets/page_services_4.jpeg
[servicespage5]: assets/page_services_5.jpeg
[servicespage6]: assets/page_services_6.jpeg
[servicespage7]: assets/page_services_7.jpeg
[servicespage8]: assets/page_services_8.jpeg
[servicespage9]: assets/page_services_9.jpeg
[servicespage10]: assets/page_services_10.jpeg
[servicespage11]: assets/page_services_11.jpeg
