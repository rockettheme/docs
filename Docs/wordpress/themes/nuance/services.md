---
title: Nuance: Recreating the Demo - Services Page
description: Your Guide to Recreating Elements of the Nuance Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Introduction
-----

The **Services** example page demonstrates how you can create a beautiful page with the Nuance theme. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][servicesmenu]

The **Services** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-services` in the **Page Suffix** field in the **Gizmos** page inside the **Nuance** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Nuance > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs]

Mainbody
-----

![][services5]

The page's content body is set in the **Services** page. You will find the content used in the page below.

~~~ .html
<h3>Why Should You Choose Us?</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/nuance" class="readon">Learn More</a></p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Top**][top], [**Header**][header], and [**Copyright**][copyright] positions are outlined in the main demo replication area of this guide.

![][services]

:   1. **Showcase - Text** [10%, 45%, se]
    2. **Feature - Text** [17%, 13%, se]
    3. **Main Top - Text** [37%, 13%, se]
    4. **Mainbody** [49%, 13%, se]
    5. **Main Bottom - Text** [60%, 13%, se]
    6. **Extension - Text** [71%, 35%, se]
    7. **Footer - Text** [78%, 13%, se]
    8. **Footer - Text** [78%, 52%, se]

1. [Showcase - Text](services.md#showcase-section)
2. [Feature - Text](services.md#feature-section)
3. [Main Top - Text](services.md#main-top-section)
4. [Mainbody](services.md#mainbody)
5. [Main Bottom - Text](services.md#main-bottom-section)
6. [Extension - Text](services.md#extension-section)
7. [Footer - Text](services.md#footer-section)
8. [Footer - Text](services.md#footer-section)

Showcase Section
-----

![][services2]

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Services[span class="rt-title-tag"]What We Can Do[/span]`.
* Switch the **Widget Variations** option to **RT-Center, No Margin All**.
* Enter `rt-title-large rt-nomodulecontent rt-top-large-padding` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Feature Section
-----

![][services3]

Here is the widget breakdown for the Feature section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

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

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Widget Variations** option to **Box 4, No Margin All**.
* Leaving everything else at its default setting, select **Save**.

Main Top Section
-----

![][services4]

Here is a breakdown for the **Main Top** section:

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

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
            <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/services/img-01.jpg" alt="image" /></span>
        </div>
    </div>  
</div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `rt-title-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Main Bottom Section
-----

![][services6]

Here is a breakdown for the **Main Bottom** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-25">
    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/services/img-02.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4>Grid System</h4>
        <p>Objectively innovate empowered manufactured products with parallel platforms.</p>
    </div>
</div>

<div class="gantry-width-25">
        <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/services/img-03.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4>Custom Interface</h4>
        <p>Proactively envisioned multimedia based expertise and effective cross-media strategies.</p>
    </div>
</div>

<div class="gantry-width-25">
    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/services/img-04.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4>Flexible Layouts</h4>
        <p>Interactively coordinate proactive e-commerce via process-centric outside the box.</p>
    </div>
</div>

<div class="gantry-width-25">
    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/services/img-05.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4>Ultimate Control</h4>
        <p>Holistically pontificate installed base portals after maintainable affordable products.</p>
    </div>
</div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Widget Variations** option to **No Padding All**.
* Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![][services7]

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>We Always Create the Real Value and Work with All Passion</p>

<p><a href="www.rockettheme.com/wordpress-themes/nuance" class="readon">Purchase Nuance</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Save Your Time and Effort`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][footer]

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Nuance can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/nuance">Nuance RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Nuance Demo`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Nuance Theme, LLC</span><br />
            <span>123 WordPress Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Sample Contact Info`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[services]: assets/page_services.jpeg
[services2]: assets/page_services_2.jpeg
[services3]: assets/page_services_3.jpeg
[services4]: assets/page_services_4.jpeg
[services5]: assets/page_services_5.jpeg
[services6]: assets/page_services_6.jpeg
[services7]: assets/page_services_7.jpeg
[services8]: assets/page_services_8.jpeg
[services9]: assets/page_services_9.jpg
[services10]: assets/page_services_10.jpeg
[services11]: assets/page_services_11.jpeg
[services12]: assets/page_services_12.jpeg
[services13]: assets/page_services_13.jpeg
[footer]: assets/page_footer_11.jpg
[aboutus8]: assets/page_aboutus_8.jpeg
[servicesmenu]: assets/page_services_menu.jpeg
[header]: demo_header.md
[top]: demo_top.md
[copyright]: demo_copyright.md
[gantrydocs]: http://docs.gantry.org/gantry4/configure
