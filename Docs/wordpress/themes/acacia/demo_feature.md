---
title: Acacia: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Acacia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/acacia:Acacia

---

Feature Section
-----

![][demo]

Here is the widget breakdown for the Feature section:

* Text

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="gantry-width-33">
    <div class="gantry-width-spacer">
        <div class="rt-center">
            <div class="canvas-graph" data-canvas-graph='{"icon":"icon-eye-open","iconSize":80,"radius":110,"size":15,"start":70}'><div class="longshadow"></div></div>
            <h3 class="title">HTML5 Charts</h3>
        </div>      
        <p>Chart.js and HTML5 canvas to display beautiful graphs and exquisite typography. This only works on <strong><a href="http://www.w3schools.com/html/html5_canvas.asp" target="_blank">modern browsers</a> and IE9+</strong>.</p>
        <div class="rt-center">
            <a href="http://demo.rockettheme.com/live/wordpress/acacia/pages/" class="readon">Read More</a>
        </div>
    </div>
</div>

<div class="gantry-width-33">
    <div class="gantry-width-spacer">
        <div class="rt-center">
            <div class="canvas-graph" data-canvas-graph='{"icon":"icon-inbox","iconSize":80,"radius":110,"size":15,"start":50}'><div class="longshadow"></div></div>
            <h3 class="title">Coming Soon</h3>
        </div>      
        <p>The theme also supports a simple coming soon or offline style page with a time counter. It has been specifically styled to match Acacia.</p>
        <div class="rt-center">
            <a href="http://demo.rockettheme.com/live/wordpress/acacia/?tmpl=comingsoon" class="readon">Read More</a>
        </div>
    </div>
</div>

<div class="gantry-width-33">
    <div class="gantry-width-spacer">
        <div class="rt-center">
            <div class="canvas-graph" data-canvas-graph='{"icon":"icon-camera","iconSize":80,"radius":110,"size":15,"start":35}'><div class="longshadow"></div></div>
            <h3 class="title">Flexible Layouts</h3>
        </div>      
        <p>The frontpage is just one example of how Acacia can be configured. See many different simple and complex examples on the link below.</p>
        <div class="rt-center">
            <a href="http://demo.rockettheme.com/live/wordpress/acacia/pages/" class="readon">Read More</a>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Page Options [span class="rt-title-tag"]Multiple Layouts & Possibilities[/span]` in the **Title** field.
* Enter `dashed-title` in the **Custom Variations** field.
* Set the **Title Variation** to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/