---
title: Myriad: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Myriad Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Feature Section
-----

![Feature](assets/demo_5.jpeg)

:   1. **Text 1** [15%, 5%, se]
    2. **Text 2** [15%, 48%, se]

Here is the widget breakdown for the Feature section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="rt-lead">Myriad centers around photography, providing an elegant space for displaying full width galleries. The structure, whilst focusing on images, maintains a refined and conservative style option.</p>

<p>The theme makes uses of animated effects to add depth and character to content, without compromising on usability and professionalism. A series of bounce and slide effects are built into Myriad, as triggered by scroll events, with an option to disable them.</p>

<p class="visible-large">A responsive layout adapts automatically to the viewing device's width, such as mobile, tablet or desktop, without the need for a separate layout or content. Mobile modes have a unique menu to aid usability. 960px and 1200px fixed layout options are also available.</p>

<a href="http://demo.rockettheme.com/live/wordpress/myriad/features-overview/" class="readon3">Read the Whole Story</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `About Myriad` in the **Title** field.
* Enter `fp-feature-a title5 rt-modtitle-uppercase wow fadeInLeft` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50 wow fadeInDown">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-01.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="http://demo.rockettheme.com/live/wordpress/myriad/features-overview/"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/wordpress/themes/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-01.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>  
            </div>
        </div>
        <div class="gantry-width-50 wow fadeInDown">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-02.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="http://demo.rockettheme.com/live/wordpress/myriad/features-overview/"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/wordpress/themes/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-02.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50 wow fadeInUp">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-03.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="http://demo.rockettheme.com/live/wordpress/myriad/features-overview/"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/wordpress/themes/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-03.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>
        <div class="gantry-width-50 wow fadeInUp">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-04.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="http://demo.rockettheme.com/live/wordpress/myriad/features-overview/"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/wordpress/themes/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/home/fp-feature/img-04.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Photo Gallery` in the **Title** field.
* Enter `fp-feature-b title5 rt-modtitle-uppercase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.