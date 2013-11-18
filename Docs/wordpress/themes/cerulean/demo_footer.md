---
title: Cerulean: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Cerulean Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cerulean:Cerulean

---

Footer Section
-----
![][footer]

:   1. **Text** [18%, 8%, se]
    2. **Text** [18%, 40%, se]
    3. **Text** [18%, 72%, se]

Here's the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

### Text
The first Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<p>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site.</p>

<p>
    <img class="rt-noborder" src="http://yoursite.com/wordpress/wp_cerulean/wp-content/rockettheme/rt_cerulean_wp/frontpage/footer/logo-footer.png" alt="Logo" />
</p>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Demo Info.  [span class=\"icon-chevron-down rt-teaser\"][/span]`.
* Set the **Custom Variations** to `nomarginbottom nopaddingbottom nomargintop medpaddingtop`.
* Leaving everything else at its default setting, select **Save**.

### Text
The second Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<p class="smallpaddingbottom">
    <span class="hidden-tablet"><strong>RokSprocket</strong> is a multi-purpose content widget with <strong>integrated</strong> template styling.</span>
    <span class="visible-tablet">RokSprocket is a multi-purpose plugin with integrated  styling.</span>
    <br class="hidden-tablet" />
    <small>26 Jun, 2013 17:07</small>
</p>

<p class="rt-dashed-divider"></p>

<p class="smallpaddingtop">    
    <span class="hidden-tablet">The <a href="#">dropdown menu</a> is an advanced CSS driven system with <strong>mobile</strong> support.</span>
  <span class="visible-tablet">The dropdown menu is an advanced CSS driven system.</span>
  <br class="hidden-tablet" />
  <small>23 Jun, 2013 12:46</small>
</p>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Top Features. [span class=\"icon-chevron-down rt-teaser\"][/span]`.
* Set the **Custom Varations** to `nomarginbottom nopaddingbottom nomargintop medpaddingtop hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

### Text
The third Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-phone"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">
    <strong>+1 (555) 555-555-5555</strong><br />
    <small>+1 (555) 555-555-5556</small>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-home"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>123 WordPress Boulevard</span><br />
      <small>Seattle, WA 00000, USA</small> 
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <span class="icon-envelope-alt"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>noreply@domain.com</span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-random"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">

    <div class="rt-social-buttons">
        <a class="social-button rt-facebook-btn" href="http://www.facebook.com/RocketTheme"><span></span></a>
        <a class="social-button rt-twitter-btn" href="https://twitter.com/rockettheme"><span></span></a>
      <a class="social-button rt-google-btn" href="https://plus.google.com/114430407008695950828/posts"><span></span></a>
    <a class="social-button rt-rss-btn" href="http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span></span></a>
  </div>
</div>  

<div class="clear"></div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Contact Us.  [span class=\"icon-chevron-down rt-teaser\"][/span]`.
* Set the **Custom Varations** to `nomarginbottom nopaddingbottom nomargintop medpaddingtop hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

[footer]: assets/footer.jpeg