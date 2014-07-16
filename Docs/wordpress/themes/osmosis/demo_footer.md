---
title: Osmosis: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Osmosis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Footer Section
-----

![][demo]

:   1. **Text** [20%, 7%, se]
    2. **Text** [20%, 38%, se]
    3. **Text** [20%, 68%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for sample purpose only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.<span class="hidden-tablet"> Use the <a href="http://www.rockettheme.com/wordpress/themes/osmosis">RocketLauncher</a> to install the demo equivalent.</span></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Demo Info` in the **Title** field.
* Set the **Widget Variations** to **Box 1**.
* Enter `fp-footer-a rt-text-small` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<p>
    <span>Osmosis Theme, LLC</span><br />
    <span>123 WordPress Boulevard</span><br />
    <span>Seattle, USA</span><br />
    <span class="fa fa-phone"></span> <span>+1(555)555-555</span><br />
    <span class="fa fa-envelope"></span> <span>me@osmosis.com</span>    
</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Contact Us` in the **Title** field.
* Set the **Widget Variations** to **Box 2**.
* Enter `fp-footer-b rt-text-small` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row smallmargintop">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer smallmarginleft">
                <h5 class="medmarginall"><a href="http://(Your Site URL)/features-overview/">Features</a></h5>
                <h5 class="medmarginall"><a href="http://(Your Site URL)/widget-variations/">Widgets</a></h5>
                <h5 class="medmarginall"><a href="http://(Your Site URL)/pages-overview/">Pages</a></h5>
                <h5 class="medmarginall hidden-tablet"><a href="http://(Your Site URL)/typography/">Typography</a></h5>
            </div>
        </div>
        <div class="gantry-width-50">
            <div class="gantry-width-spacer smallmarginleft">
                <h5 class="medmarginall"><a href="http://www.rockettheme.com/docs/wordpress/themes/osmosis">Tutorial</a></h5>
                <h5 class="medmarginall"><a href="http://www.rockettheme.com/forum/wordpress-theme-osmosis">Forum</a></h5>
                <h5 class="medmarginall hidden-tablet"><a href="http://www.rockettheme.com/wordpress/themes/osmosis">Download</a></h5>
                <h5 class="medmarginall"><a href="http://www.rockettheme.com/wordpress/themes/osmosis">Buy</a></h5>
            </div>
        </div>      
    </div>
</div>
<div class="clear smallmarginbottom"></div>
<p class="rt-text-small">&copy; <span class="hidden-tablet">Designed </span>by <a href="http://www.rockettheme.com/">RocketTheme</a>.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Widget Variations** to **Box 3**.
* Enter `fp-footer-c` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_9.jpg
[roksprocket]: ../../plugins/roksprocket/
