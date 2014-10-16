---
title: Nuance: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Extension Section
-----

![][demo]

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 29%, se]

Here is the widget breakdown for the Extension section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="fp-extension-menu">
    <li><a href="#">Optimized Code</a></li>
    <li><a href="#">Built-in Features</a></li>
    <li><a href="#">Control Options</a></li>
    <li class="visible-desktop"><a href="#">RocketLauncher</a></li>
    <li class="visible-large"><a href="#">Adobe&reg; Sources</a></li>
</ul>
~~~

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RokBox, a fully responsive modal &quot;pop-up&quot; plugin" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-01.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-01.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RokAjaxSearch, a search widget with AJAX generated results" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-02.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-02.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RokSprocket, a powerful content switchblade plugin" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-03.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-03.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="Gantry, a modern theme framework" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-04.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-04.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RokWeather, an easy to use weather widget" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-05.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-05.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>              
</div>

<div class="clear"></div>

<div class="gantry-row">
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RocketTheme" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-06.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-06.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RocketTheme" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-07.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-07.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RocketTheme" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-08.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-08.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RocketTheme" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-09.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-01.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-overlay">
                <a data-rokbox data-rokbox-album="Nuance Gallery" data-rokbox-caption="RocketTheme" href="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-10.jpg">
                    <img src="http://demo.rockettheme.com/live/wordpress/nuance/wp-content/rockettheme/rt_nuance_wp/home/fp-extension/img-10.jpg" alt="RokBox Image"/>
                    <span class="rt-img-overlay"><span><i class="fa fa-search"></i></span></span>   
                </a>            
            </span>
        </div>
    </div>              
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-extension-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_8.jpeg
[roksprocket]: ../../plugins/roksprocket/
