---
title: Ricochet: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Ricochet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ricochet:Ricochet

---

Feature Section
-----

![Feature](assets/demo_3.jpeg)

Here is the widget breakdown for the Feature section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-box2 rt-center">
                    <ul class="rt-tags">
                        <li>Facebook</li>
                        <li>Twitter</li>
                    </ul>                   
                    <h2 class="title">Configurable Social Media Buttons</h2>
                    <ul class="rt-tags">
                        <li><a href="#">#Social Media</a></li>
                    </ul>                       
                </div>
            </div>
        </div>  
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-box3 rt-center">
                    <ul class="rt-tags">
                        <li>Offine</li>
                        <li>Counter</li>
                    </ul>                       
                    <h2 class="title">Custom Offline &amp; Coming Soon Pages</h2>
                    <ul class="rt-tags">
                        <li><a href="#">#Maintenance</a></li>
                    </ul>                       
                </div>
            </div>
        </div>  
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-box1 rt-center">
                    <ul class="rt-tags">
                        <li>Responsive</li>
                        <li>Fixed</li>
                    </ul>                       
                    <h2 class="title">Responsive, 960 &amp; 1200 Layouts</h2>
                    <ul class="rt-tags">
                        <li><a href="#">#Layout</a></li>
                    </ul>                       
                </div>
            </div>
        </div>          
    </div>      
</div>

<div class="clear"></div>

<h6>One of the Gantry Framework's most notable features is its custom administrative interface. The theme settings page provides a user friendly and intuitive console to configure many aspects of the theme, from gizmos, styling, to layout controls.</h6>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Upcoming Events` in the **Title** field.
* Enter `fp-expandedtop title5` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
