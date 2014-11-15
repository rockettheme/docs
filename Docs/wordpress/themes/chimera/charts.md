---
title: Chimera: Charts
description: Your Guide to Using Charts in Chimera
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Introduction
-----

Chimera supports chart creation and management. This gives you the ability to display information in a way that matches your theme and provides extremely high visual appeal without requiring you to upload any images. It's are built on HTML5, and can be changed quickly on the back end of your site.

[Chart.js][chartjs] support is built in that allows you to create rich and infinitely useful charts within a **Text** widget, or injected directly in a post to add a powerful visual element to your written information.

>> NOTE: This feature is not currently supported in IE8. Chart.js elements will not display correctly. Newer versions of IE, as well as updated Chrome, Firefox, Safari, Opera, and other popular standard-compliant browser options should work just fine.

Chart.js Support
-----

Chimera introduces built-in support for [Chart.js][chartjs]. This element allows you to quickly and easily create dynamic graphs that display information in a variety of ways.

You can toggle this feature on and off by navigating to **Administrator -> Chimera Theme -> Gizmos -> Chart** and toggling the option there. If you have a Custom HTML and/or article with the Chart.js code present, and this option is off, nothing will appear in its place and your browser may indicate a JavaScript error.

![][chart_1]

Here is the code block that creates the graphs that appear in the above image. In this case, it was placed within a **Text** widget.

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

You can find extensive documentation listing the different elements found here on the [official website][chartjs].

[chartjs]: http://chartjs.org
[fontawesome]: http://fortawesome.github.io/Font-Awesome/
[chart_1]: assets/page_services_3.jpeg
[chart_2]: assets/demo_3.jpeg
[list]: http://demo.rockettheme.com/wordpress-themes/Chimera/features/typography
