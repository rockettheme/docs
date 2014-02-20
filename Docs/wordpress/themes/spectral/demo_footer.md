---
title: Spectral: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Footer Section
-----

![][demo]

:   1. **Text** [15%, 6%, se]
    2. **Text** [15%, 70%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text

#### Text

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-footer-logo"></div>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="#">Spectral RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-footer-demo-info` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

You will need to enter the following in the main text field.

~~~ .html
<div class="largemargintop">
    <div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
        <span class="icon-phone"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <span class="rt-intro-text">+1 (555) 555-555-5555</span><br />
    </div>

    <div class="clear largemarginbottom largepaddingbottom"></div>

    <div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
        <span class="icon-home"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <span class="rt-intro-text">Spectral Theme, LLC</span><br />
        <span>123 WordPress Boulevard</span><br />
        <span>Seattle, WA 00000, USA</span> 
    </div>

    <div class="clear largemarginbottom largepaddingbottom"></div>

    <div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
        <span class="icon-envelope-alt"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <span class="rt-intro-text"><a href="#">noreply@domain.com</a></span>
    </div>

    <div class="clear"></div>   
</div>  
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-footer-contact-info hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg