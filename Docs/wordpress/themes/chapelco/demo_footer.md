---
title: Chapelco: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Chapelco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chapelco:Chapelco

---

Footer Section
-----
![][demo]

:   1. **Text** [20%, 5%, se]
    2. **Text** [20%, 36%, se]
    3. **Text** [20%, 67%, se]

Here's the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

### Text
You'll need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~
<p><strong><a href="#">NOTE:</a></strong> <span class="hidden-tablet">All demo content is for <strong>sample</strong> purposes only, intended to show a live site. </span>All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site only.</p>

<div class="rt-social-buttons largemargintop largepaddingtop">
  <span class="largepaddingright hidden-tablet hidden-phone">Follow Us</span>
  <a class="social-button rt-facebook-btn" href="http://www.facebook.com/RocketTheme"><span class="icon-facebook"></span></a>
  <a class="social-button rt-twitter-btn" href="https://twitter.com/rockettheme"><span class="icon-twitter"></span></a>
  <a class="social-button rt-google-btn" href="https://plus.google.com/114430407008695950828/posts"><span class="icon-google-plus"></span></a>
  <a class="social-button rt-rss-btn" href="http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span class="icon-rss"></span></a>
</div>  
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Enter `Demo Info[span class=\"hidden-tablet\"]rmation[/span].` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Text
The second Text widget in the section is made a lot like the other. You'll need to enter the following in the main text field.

~~~
<div class="gantry-width-10 gantry-width-block">
    <span class="icon-phone"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <strong><span>+1 (555) 555-555-5555</span></strong><br />
    <small>+1 (555) 555-555-5556</small>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block">
    <span class="icon-home"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <strong><span>Chapelco Theme, LLC</span></strong><br />
    <span>123 WordPress Boulevard</span><br />
    <small>Seattle, WA 00000, USA</small> 
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block">
    <span class="icon-envelope-alt"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>noreply/@domain.com</span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Contact Us`.
* Set the **Custom Varations** to `hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

### Text
You'll need to enter the following in the main text field to create this text widget as it appears in our demo. The title is left blank.

~~~
<div class="rt-image">
    <img src="http://demo.rockettheme.com/wordpress/wp_chapelco/wp-content/rockettheme/rt_chapelco_wp/frontpage/footer/img1.jpg" alt="Image" />
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Enter `Location` in the **Title** field.
* Enter `hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_9.jpeg