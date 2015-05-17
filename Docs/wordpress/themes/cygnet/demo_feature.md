---
title: Cygnet: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Cygnet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Feature Section
-----

![Feature](assets/demo_5.jpeg)

Here is the widget breakdown for the Feature section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-history"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Feature Focus</h3>  
                        <p><span>The Features layout, offers Slideshow and Showcase options, for easy to configure content presentation</span></p>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-shopping-cart"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Tabbed Content</h3> 
                        <p><span>RokSprocket features the Tabs layout, with configurable tab positions and titles with icons or text</span></p>
                    </div>
                    <div class="clear"></div>
                </div>              
            </div>
        </div>  
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-institution"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Data Comparison</h3>    
                        <p><span>Utilize the tables layout to present columns of data, such as price comparisons, for your various products</span></p>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-camera-retro"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Photo Integration</h3>  
                        <p><span>In the administrator, there is support for the Media Manager, RokGallery, and custom URL/Path input</span></p>
                    </div>
                    <div class="clear"></div>
                </div>              
            </div>
        </div>                                      
    </div>
</div>

<div class="rt-center rt-feature-promo">
    <p class="rt-text-medium">RokSprocket's custom administrator benefits from compounding filters, intuitive per item controls, and a rich UI to make configuration as user friendly as possible. <a href="http://demo.rockettheme.com/live/wordpress/cygnet/features-overview/" class="readon3">Learn More</a></p>
    <a class="readon" href="http://demo.rockettheme.com/live/wordpress/cygnet/features-overview/">Get Started</a>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                    |
| :---------------- | :---------                 |
| Custom Variations | `fp-feature wow slideInUp` |

Leaving everything else at its default setting, select **Save**.
