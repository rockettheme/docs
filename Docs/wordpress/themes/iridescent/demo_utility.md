---
title: Iridescent: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Iridescent Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/iridescent:Iridescent

---

Utility Section
-----

![Utility](assets/demo_6.jpeg)

:   1. **Text 1** [8%, 5%, se]
    2. **Text 2** [8%, 50%, se]

Here is the widget breakdown for the Utility section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-effect-border">
    <img src="http://(Your Site URL)/wp-content/rockettheme/rt_iridescent_wp/home/fp-utility/img-01.jpg" alt="image"/>
    <div class="rt-effect-content">
        <h2><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url"><span>RocketLauncher</span></a></h2>
        <p class="visible-desktop"><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url">Install Iridescent demo on your website or localhost<span class="visible-large"></span></a></p>
    </div>          
</div>
<div class="gantry-width-container">
    <div class="gantry-width-33">
        <a href="https://www.facebook.com/RocketTheme">
            <div class="rt-icon-1">
                <i class="fa fa-facebook fa-3x"></i>
            </div>
        </a>
    </div>
    <div class="gantry-width-33">
        <a href="https://twitter.com/rockettheme">
            <div class="rt-icon-2">
                <i class="fa fa-twitter fa-3x"></i>
            </div>
        </a>
    </div>
    <div class="gantry-width-33">
        <a href="https://plus.google.com/+rockettheme/posts">
            <div class="rt-icon-3">
                <i class="fa fa-google-plus fa-3x"></i>
            </div>
        </a>
    </div>      
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |    Setting     |
| :---------------- | :------------- |
| Custom Variations | `fp-utility-a` |

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_iridescent_wp/home/fp-utility/img-02.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url">Responsive<br /> Design</a></h2>
                <p><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url">Adapts to any device</a></p>
            </div>          
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_iridescent_wp/home/fp-utility/img-03.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url">Presets</a></h2>
                <p><a href="http://(Your Site URL)/features-overview/" class="fp-demo-url">Six elegant styles</a></p>
            </div>          
        </div>
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_iridescent_wp/home/fp-utility/img-04.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="http://(Your Site URL)/typography/" class="fp-demo-url">Typography</a></h2>
                <p><a href="http://(Your Site URL)/typography/" class="fp-demo-url">Individualize <span class="hidden-tablet">your</span> content</a></p>
            </div>          
        </div>      
    </div>      
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |    Setting     |
| :---------------- | :------------- |
| Custom Variations | `fp-utility-b` |

Leaving everything else at its default setting, select **Save**.
