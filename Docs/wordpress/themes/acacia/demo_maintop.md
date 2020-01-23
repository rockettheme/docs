---
title: Acacia: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Acacia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/acacia:Acacia

---

Main Top Section
-----

![][demo]

Here is the widget breakdown for the Main Top section:

* Text

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p class="rt-intro-text rt-center"><a href="#">Gantry 4</a> rests at the core of the Acacia theme and provides a range of features, such as dynamic module grids, expandable features and an intuitive administrative interface.</p>

<br />

<div class="gantry-width-15">
    <div class="gantry-width-spacer">
        <div class="box1">
            <div class="rt-demo-statistic visible-desktop">
                <div class="rds-title">
                    <strong>Data 2013</strong><br />
                    <small>Jan - July</small>                   
                </div>
                <div class="rds-separator"></div>
                <div class="rds-data">
                    <span class="icon-circle rds-data-1"></span> <strong>Gantry</strong><br />
                    <h2>+2,045</h2>
                </div>
                <div class="rds-separator"></div>
                <div class="rds-data">
                    <span class="icon-circle rds-data-2"></span> <strong>Themes</strong><br />
                    <h2>+1,207</h2>
                </div>              
            </div>
            <div class="rt-demo-statistic visible-tablet">
                <div class="rds-data nomargintop">
                    <span class="icon-circle rds-data-1"></span> <strong>Gantry</strong><br />
                    <h2>+2,045</h2>
                </div>
                <div class="rds-separator"></div>
                <div class="rds-data">
                    <span class="icon-circle rds-data-2"></span> <strong>Themes</strong><br />
                    <h2>+1,207</h2>
                </div>              
            </div>          
        </div>
    </div>
</div>

<div class="gantry-width-85">
    <div class="gantry-width-spacer">
        <canvas id="myChart" height="320" width="977"></canvas>

        <script type="text/javascript">
            var lineChartData = {
                labels : ["January","February","March","April","May","June","July"],
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
                scaleFontColor : "rgba(255,255,255,0.3)",

                //String - Colour of the scale line
                scaleLineColor : "rgba(255,255,255,0.3)",

                //String - Colour of the grid lines
                scaleGridLineColor : "rgba(255,255,255,0.3)",   

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
            var ctx = document.getElementById("myChart").getContext("2d");
            var myNewChart = new Chart(ctx).Line(lineChartData, options);

        </script>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Gantry 4 Framework`.
* Set the **Title Variation** to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/chart.jpeg