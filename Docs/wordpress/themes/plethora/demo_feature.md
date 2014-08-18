---
title: Plethora: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Feature Section
-----

![][demo]

:   1. **Text** [13%, 6%, se]
    2. **Text** [13%, 50%, se]
    3. **Text** [13%, 68%, se]

Here is the widget breakdown for the Feature section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-feature-a/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Free Plugin</span>
        </div>
        <div class="rt-image-content">
            <div class="rt-image-title">
                <span>RokSprocket<span class="hidden-tablet"> is a powerful, switchblade content plugin</span>.</span>
            </div>      
            <div class="rt-image-desc">
                <p>RokSprocket is a multi-purposes content plugin, with a custom, advanced and intuitive user interface<span class="hidden-tablet">, as well as several layout modes with numerous themes</span>.</p>
                <a href="#">Read the whole story <i class="fa fa-angle-double-right"></i></a>
            </div>              
        </div>  
    </div>  
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-feature-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-feature-b/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Speed</span>
        </div>
        <div class="rt-image-content">
            <p class="smallmarginbottom">Improve site speed<span class="hidden-tablet"> performance</span></p>
            <span class="rt-text-small"><em>LESS</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-feature-b/img-02.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Search</span>
        </div>      
        <div class="rt-image-content">
            <p class="smallmarginbottom">Ajax <span class="hidden-tablet">powered </span>site and Google search</p> 
            <span class="rt-text-small"><em>RokAjaxSearch</em></span>
        </div>      
    </div>      
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-feature-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-feature-c/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Layouts</span>
        </div>
        <div class="rt-image-content">
            <div class="rt-image-title">
                <span class="hidden-tablet">Multiple RokSprocket layout and theme options.</span>
                <span class="visible-tablet">Layouts and themes.</span>
            </div>      
            <div class="rt-image-desc">
                <p>Several content display options to <span class="hidden-tablet">choose and </span>configure.</p>
                <a href="#">Read the whole story <i class="fa fa-angle-double-right"></i></a>
            </div>              
        </div>  
    </div>  
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-feature-c` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[faq]: faq.md
