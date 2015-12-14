---
title: Corvus: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Footer Section
-----

![][demo]

:   1. **Text 1** [15%, 6%, se]
    2. **Text 2** [15%, 40%, se]
    3. **Text 3** [15%, 74%, se]
    4. **Text 4** [74%, 74%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text
* Text

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-footer-logo-block">
    <span class="rt-footer-logo"></span>
</div>

<p class="rt-uppercase"><span>All demo content is for <strong>sample</strong> purposes only<span class="visible-large">, intended to show a live site</span>. <span class="hidden-tablet">Use the <a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/installation/"><strong>RocketLauncher</strong></a> for demo replication.</span> All images are copyrighted to their respective owners.</span></p>

<p class="rt-copyright-text nomarginbottom">Designed by <a href="http://www.rockettheme.com/" target="_blank">RocketTheme</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-footer-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<div class="largemargintop largepaddingtop largemarginbottom largepaddingbottom">
    <div class="gantry-width-50 gantry-width-block">
        <ul class="fp-footer-menu rt-uppercase">
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/features/">Features</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/widget-positions/">Positions</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/widget-variations/">Variations</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/typography/">Typography</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/menu-options/">Menu<span class="hidden-tablet"> Options</span></a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/plugins/">Plugins</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/tutorials/">Tutorials</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/installation/">Installation</a></li>       
        </ul>
    </div>
    <div class="gantry-width-50 gantry-width-block">
        <ul class="fp-footer-menu rt-uppercase">
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/logo-editing/">Logo <span class="hidden-tablet">Editing</span></a></li>
            <li><a href="http://www.rockettheme.com/forum/index.php?f=844&amp;rb_v=viewforum"><span class="hidden-tablet">Forum</span> Guides</a></li>
            <li><a href="http://docs.gantry.org/">Gantry</a></li>                     
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/preset-styles/">Preset Styles</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/sed-imperdiet-ligula-nisi/">Sample Post</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/sample-page-2/"><span class="hidden-tablet">Dummy</span> Page</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/?m=2013">Archive</a></li>
            <li><a href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/?s=varius">Search</a></li>
        </ul>
    </div>
    <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Inside Corvus` in the **Title** field.
* Set the **Box Variation** option to **Box 6**.
* Enter `fp-footer-b hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

You will need to enter the following in the main text field.

~~~ .html
<div class="largemargintop largepaddingtop">
    <div class="gantry-width-10 gantry-width-block hidden-phone">
        <span class="icon-phone"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <strong><span>+1 (555) 555-555-5555</span></strong><br />
        <span>+1 (555) 555-555-5556</span>
    </div>
    <div class="clear largemarginbottom"></div>
    <div class="gantry-width-10 gantry-width-block hidden-phone">
        <span class="icon-home"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <strong><span>Corvus Theme, LLC</span></strong><br />
        <span>123 WordPress Boulevard</span><br />
        <span>Seattle, WA 00000, USA</span> 
    </div>
    <div class="clear largemarginbottom"></div>
    <div class="gantry-width-10 gantry-width-block hidden-phone">
        <span class="icon-envelope-alt"></span>
    </div>
    <div class="gantry-width-90 gantry-width-block">
        <strong><span><a href="#">noreply/@domain.com</a></span></strong>
    </div>
    <div class="clear largemarginbottom"></div> 
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Contact Us` in the **Title** field.
* Set the **Box Variation** option to **Box 6**.
* Enter `fp-footer-c  hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 4

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-social-buttons">
  <a href="http://www.facebook.com/RocketTheme" class="social-button rt-social-button-1">
    <span class="icon-facebook"></span>
    <span class="social-button-text">Facebook</span>
  </a>
  <a href="https://twitter.com/rockettheme" class="social-button rt-social-button-2">
    <span class="icon-twitter"></span>
    <span class="social-button-text">Twitter</span>
  </a>
  <a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-social-button-3">
    <span class="icon-google-plus"></span>
    <span class="social-button-text">gPlus</span>
  </a>
  <a href="http://www.rockettheme.com/blog?format=feed&amp;type=rss" class="social-button rt-social-button-4">
    <span class="icon-rss"></span>
    <span class="social-button-text">rss</span>
  </a>
  <a href="http://www.linkedin.com/in/rockettheme" class="social-button rt-social-button-5">
    <span class="icon-linkedin"></span>
    <span class="social-button-text">LinkedIn</span>
  </a>
  <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-footer-social-buttons` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_8.jpeg