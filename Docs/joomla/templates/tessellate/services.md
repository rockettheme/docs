---
title: Tessellate: Recreating the Demo - Services Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

The **Services** example page demonstrates how you can create a content rich page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][servicespage2]

The **Services** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `services` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][servicespage8]

The page's content body is set in the **Services** article. You will find the content used in the article below.

~~~ .html
<h3>Why Should You Choose Us?</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][servicespage]

:   1. **RokAjaxSearch** [5%, 25%, se]
    2. **Custom HTML - Services** [12%, 45%, se]
    3. **Breadcrumbs** [17%, 13%, se]
    4. **Custom HTML - Services: Chart JS** [20%, 13%, se]
    5. **Custom HTML - Our Core Service** [40%, 11%, se]
    6. **Article Content** [52%, 11%, se]
    7. **Custom HTML - Grid System** [61%, 11%, se]
    8. **Custom HTML - Save Your Time and Effort** [74%, 33%, se]
    9. **Custom HTML - Tessellate Demo** [81%, 11%, se]
    10. **Custom HTML - Sample Contact Info** [81%, 52%, se]
    11. **Menu - Copyright Menu** [92%, 75%, se]

1. [RokAjaxSearch](services.md#rokajaxsearch)
2. [Custom HTML - Services](services.md#custom-html---services)
3. [Breadcrumbs](services.md#breadcrumbs)
4. [Custom HTML - Services: Chart JS](services.md#custom-html---services:-chart-js)
5. [Custom HTML - Our Core Service](services.md#custom-html---our-core-service)
6. [Article Content](services.md#mainbody)
7. [Custom HTML - Grid System](services.md#custom-html---grid-system)
8. [Custom HTML - Save Your Time and Effort](services.md#custom-html---save-your-time-and-effort)
9. [Custom HTML - Tessellate Demo](services.md#custom-html---tessellate-demo)
10. [Custom HTML - Sample Contact Info](services.md#custom-html---sample-contact-info)
11. [Menu - Copyright Menu](services.md#menu---copyright-menu)

### RokAjaxSearch

![][servicespage3]

#### Details

| Option      | Setting            |
| :---------- | :----------        |
| Title       | `FP RokAjaxSearch` |
| Show Title  | Hide               |
| Position    | header-b           |
| Status      | Published          |
| Access      | Public             |

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
                        scaleFontColor : "#383838",

                        //String - Colour of the scale line
                        scaleLineColor : "#383838",

                        //String - Colour of the grid lines
                        scaleGridLineColor : "#383838",

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
                        scaleFontColor : "#383838",

                        //String - Colour of the scale line
                        scaleLineColor : "#383838",

                        //String - Colour of the grid lines
                        scaleGridLineColor : "#383838"
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

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-title-center` |

### Custom HTML - Grid System

![][servicespage9]

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

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `nopaddingall` |

### Custom HTML - Save Your Time and Effort

![][servicespage10]

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
<p>We Always Create the Real Value and Work with All Passion</p>

<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon largemargintop">Purchase Tessellate</a></p>
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

### Custom HTML - Tessellate Demo

![][servicespage11]

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

![][servicespage12]

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

![][servicespage13]

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
[servicespage12]: assets/page_services_12.jpeg
[servicespage13]: assets/demo_21.jpeg
