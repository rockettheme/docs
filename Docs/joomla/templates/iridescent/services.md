---
title: Iridescent: Recreating the Demo - Services Page
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

Introduction
-----

The **Services** example page demonstrates how you can create a content rich page with the Iridescent template. Here is some information to help you replicate this page as it appears in the demo.

Mainbody
-----

![](assets/page_services_6.jpeg)

The page's content body is set in the **Services** article. You will find the content used in the article below.

~~~ .html
<h3>Why Should You Choose Us?</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/iridescent" class="readon">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![](assets/page_services.jpeg)

:   1. **Custom HTML - Services** [9%, 45%, se]
    2. **Breadcrumbs** [12%, 12%, se]
    3. **Custom HTML - Services: Chart JS** [15%, 12%, se]
    4. **Custom HTML - Our Core Service** [46%, 12%, se]
    5. **Article Content** [60%, 12%, se]
    6. **Custom HTML - Grid System** [35%, 12%, se]
    7. **Custom HTML - Save Yourself Time and Effort** [71%, 33%, se]
    8. **Custom HTML - Iridescent Demo** [78%, 12%, se]
    9. **Custom HTML - Sample Contact Info** [78%, 52%, se]

1. [Custom HTML - Services](services.md#custom-html---services)
2. [Breadcrumbs](services.md#breadcrumbs)
3. [Custom HTML - Services: Chart JS](services.md#custom-html---services:-chart-js)
4. [Custom HTML - Our Core Service](services.md#custom-html---our-core-service)
5. [Article Content](services.md#mainbody)
6. [Custom HTML - Grid System](services.md#custom-html---grid-system)
7. [Custom HTML - Save Yourself Time and Effort](services.md#custom-html---save-your-time-and-effort)
8. [Custom HTML - Iridescent Demo](services.md#custom-html---iridescent-demo)
9. [Custom HTML - Sample Contact Info](services.md#custom-html---sample-contact-info)

### Custom HTML - Services

![](assets/page_services_1.jpeg)

#### Module

| Option      | Setting                                                    |
| :---------- | :-----------                                               |
| Title       | `Services[span class="rt-title-tag"]What We Can Do[/span]` |
| Show Title  | Yes                                                        |
| Position    | showcase-a                                                 |
| Status      | Published                                                  |
| Access      | Public                                                     |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

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

### Breadcrumbs

![](assets/page_services_2.jpeg)

#### Module

| Option              | Setting       |  
| :------------------ | :------------ |  
| Title               | `Breadcrumbs` |  
| Show You Are Here   | No            |  
| Show Home           | Yes           |  
| Text for Home Entry |               |  
| Show Last           | Yes           |  
| Text Separator      |               |  
| Show Title          | Hide          |  
| Position            | breadcrumb    |  
| Status              | Published     |  
| Access              | Public        |  

##### Advanced

| Option              | Setting                                                    |  
| :------------------ | :--------------------------------------------------------- |  
| Module Class Suffix | ` hidden-phone nomarginall medpaddingtop medpaddingbottom` |  

### Custom HTML - Services: Chart JS

![](assets/page_services_3.jpeg)

>> More information about Chart.js support can be found [here](charts.md).

#### Module

| Option      | Setting              |
| :---------- | :-----------         |
| Title       | `Services: Chart JS` |
| Show Title  | Hide                 |
| Position    | maintop-a            |
| Status      | Published            |
| Access      | Public               |

#### Content

~~~ .html
<p>The two charts shown below are the sample chart canvas based on Chart.js. Chart.js is an easy, object oriented client side graphs for designers and developers. For more information how to create great looking charts using Chart.js, please visit <a href="http://www.chartjs.org/">Chart.js</a> homepage or download the script <a href="https://github.com/nnnick/Chart.js">here</a>.</p>

<br />

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <canvas id="myChart-a" width="600" height="320"></canvas>

                <script type="text/javascript">
                    var lineChartData = {
                        labels : ["Joomla","Wordpress","Magento","phpBB","Kunena","Email","Forum"],
                        datasets : [
                            {
                                fillColor : "transparent",
                                strokeColor : "#97DBF2",
                                pointColor : "#97DBF2",
                                pointStrokeColor : "#97DBF2",
                                data : [600,500,900,800,500,400,700]
                            },
                            {
                                fillColor : "transparent",
                                strokeColor : "#DE4E33",
                                pointColor : "#DE4E33",
                                pointStrokeColor : "#DE4E33",
                                data : [200,400,600,300,900,200,500]
                            },
                        ]
                    },
                    options = {
                        //Boolean - If we want to override with a hard coded scale
                        scaleOverride : true,

                        //** Required if scaleOverride is true **
                        //Number - The number of steps in a hard coded scale
                        scaleSteps : 9,
                        //Number - The value jump in the hard coded scale
                        scaleStepWidth : 100,
                        //Number - The scale starting value
                        scaleStartValue : 100,

                        //String - Scale label font colour
                        scaleFontColor : "#FFFFFF",

                        //String - Colour of the scale line
                        scaleLineColor : "#FFFFFF",

                        //String - Colour of the grid lines
                        scaleGridLineColor : "#FFFFFF",

                        //Boolean - Whether the line is curved between points
                        bezierCurve : false,

                        //Number - Radius of each point dot in pixels
                        pointDotRadius : 8,

                        //Number - Pixel width of point dot stroke
                        pointDotStrokeWidth : 5,

                        //Number - Pixel width of dataset stroke
                        datasetStrokeWidth : 6,

                        //Boolean - Whether to fill the dataset with a colour
                        datasetFill : true,

                    }

                    //Get the context of the canvas element we want to select
                    var ctx = document.getElementById("myChart-a").getContext("2d");
                    var newChartA = new Chart(ctx).Line(lineChartData, options);

                </script>
            </div>
        </div>

        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <canvas id="myChart-b" width="600" height="320"></canvas>

                <script type="text/javascript">
                    var barChartData = {
                        labels : ["January","February","March","April","May","June","July"],
                        datasets : [
                            {
                                fillColor : "#D95240",
                                strokeColor : "#D95240",
                                data : [600,500,900,800,500,600,900]
                            },
                            {
                                fillColor : "#6FC6A0",
                                strokeColor : "#6FC6A0",
                                data : [700,300,800,700,600,500,800]
                            }
                        ]
                    },
                    options = {
                        //Boolean - If we want to override with a hard coded scale
                        scaleOverride : true,
                    
                        //** Required if scaleOverride is true **
                        //Number - The number of steps in a hard coded scale
                        scaleSteps : 9,
                        //Number - The value jump in the hard coded scale
                        scaleStepWidth : 100,
                        //Number - The scale starting value
                        scaleStartValue : 100,

                        //String - Scale label font colour
                        scaleFontColor : "#FFFFFF",

                        //String - Colour of the scale line
                        scaleLineColor : "#FFFFFF",

                        //String - Colour of the grid lines
                        scaleGridLineColor : "#FFFFFF"
                    }

                    //Get the context of the canvas element we want to select
                    var ctx = document.getElementById("myChart-b").getContext("2d");
                    var newChartB = new Chart(ctx).Bar(barChartData, options);

                </script>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div><br />

<p class="success">NOTE: The canvas only works on modern browsers (Firefox, Opera, Chrome, Safari, and Internet Explorer 9+) that support the HTML5 canvas element. <a target="_blank" href="http://www.w3schools.com/html/html5_canvas.asp">Internet Explorer 8 and earlier versions, do not support the canvas element.</a></p>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |      Setting       |
| :------------------ | :----------------- |
| Module Class Suffix | `box2 nomarginall` |

### Custom HTML - Our Core Service

![](assets/page_services_5.jpeg)

#### Module

|   Option   |                    Setting                    |
| :--------- | :-------------------------------------------- |
| Title      | `Services: Our Core Service - We Do Our Best` |
| Show Title | Hide                                          |
| Position   | expandedtop-a                                 |
| Status     | Published                                     |
| Access     | Public                                        |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Our Core Service</h3>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
                <div class="hidden-tablet">
                    <h3>We Do Our Best</h3>
                    <p>Proactively envisioned multimedia based expertise and cross-media growth strategies.</p>
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
                <span class="rt-image"><img src="images/rocketlauncher/pages/services/img-01.jpg" alt="image" /></span>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |      Setting       |
| :------------------ | :----------------- |
| Module Class Suffix | `box1 nomarginall` |

### Custom HTML - Grid System

![](assets/page_services_4.jpeg)

#### Module

|   Option   |                                     Setting                                      |
| :--------- | :------------------------------------------------------------------------------- |
| Title      | `Services: Grid System - Custom Interface - Flexible Layouts - Ultimate Control` |
| Show Title | Hide                                                                             |
| Position   | maintop-a                                                                        |
| Status     | Published                                                                        |
| Access     | Public                                                                           |

#### Content

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-25">
        <img src="images/rocketlauncher/pages/services/img-02.jpg" alt="image" />
        <div class="gantry-width-spacer">
            <h4>Grid System</h4>
            <p>Objectively innovate empowered manufactured products with parallel platforms.</p>
        </div>
    </div>

    <div class="gantry-width-25">
            <img src="images/rocketlauncher/pages/services/img-03.jpg" alt="image" />
        <div class="gantry-width-spacer">
            <h4>Custom Interface</h4>
            <p>Proactively envisioned multimedia based expertise and effective cross-media strategies.</p>
        </div>
    </div>

    <div class="gantry-width-25">
        <img src="images/rocketlauncher/pages/services/img-04.jpg" alt="image" />
        <div class="gantry-width-spacer">
            <h4>Flexible Layouts</h4>
            <p>Interactively coordinate proactive e-commerce via process-centric outside the box.</p>
        </div>
    </div>

    <div class="gantry-width-25">
        <img src="images/rocketlauncher/pages/services/img-05.jpg" alt="image" />
        <div class="gantry-width-spacer">
            <h4>Ultimate Control</h4>
            <p>Holistically pontificate installed base portals after maintainable affordable products.</p>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |             Setting             |
| :------------------ | :------------------------------ |
| Module Class Suffix | `box3 nomarginall nopaddingall` |

### Custom HTML - Save Yourself Time and Effort

![](assets/page_services_7.jpeg)

#### Module

|   Option   |             Setting             |
| :--------- | :------------------------------ |
| Title      | `Save Yourself Time and Effort` |
| Show Title | Show                            |
| Position   | extension-a                     |
| Status     | Published                       |
| Access     | Public                          |

#### Content

~~~ .html
<p>We Always Create the Real Value and Work with All Passion</p>

<p><a href="http://www.rockettheme.com/joomla/templates/iridescent" class="readon largemargintop">Purchase Iridescent</a></p>
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

### Custom HTML - Iridescent Demo

![](assets/page_aboutus_7.jpeg)

#### Module

|   Option   |      Setting      |
| :--------- | :---------------- |
| Title      | `Iridescent Demo` |
| Show Title | Yes               |
| Position   | footer-a          |
| Status     | Published         |
| Access     | Public            |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Iridescent can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/iridescent">Iridescent RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![](assets/page_aboutus_8.jpeg)

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
            <span>Iridescent Theme, LLC</span><br />
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
