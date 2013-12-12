---
title: Metropolis: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Metropolis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/metropolis:Metropolis

---

Footer Section
-----
![][demo6]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

### Text
The first Text widget in the section is made a lot like the others. You will need to enter the following in the main text field.

~~~
<p>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site only.</p>

<p class="rt-image hidden-tablet">
    <img class="rt-noborder" src="http://www.yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/footer/logo-footer.png" alt="Logo" />
</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Info`.
* Leaving everything else at its default setting, select **Save**.

### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Text

The second Text widget in the section is made a lot like the others. You will need to enter the following in the main text field.

~~~
<ul class="rt-demo-footer-menu">
  <li><a href="http://www.yoursite.com/features/">Features</a></li>
  <li><a href="http://www.yoursite.com/widget-positions/">Widget Positions</a></li>
  <li><a href="http://www.yoursite.com/widget-variations/">Widget Variations</a></li>
  <li class="hidden-tablet"><a href="http://www.yoursite.com/plugins/">Plugins</a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Inside Metropolis`.
* Set the **Custom Varations** to `hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

### Text

The third Text widget in the section is made a lot like the others. You will need to enter the following in the main text field.

~~~
<div class="gantry-width-10 gantry-width-block medmarginright">
    <span class="icon-phone medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold nobold">+1 (555) 555-555-5555</em></a><br />
    <span><em class="bold nobold">+1 (555) 555-555-5556</em></span>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block medmarginright">
    <span class="icon-home medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold nobold">Metropolis theme LLC</em></a><br />
    <em class="bold nobold">
      123 WordPress Boulevard<br />
      Seattle, WA 00000, USA 
    </em>
</div>

<div class="clear medmarginbottom hidden-tablet">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block medmarginright hidden-tablet">
	<span class="icon-envelope-alt medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block hidden-tablet">
	<p><em class="bold nobold">noreply\@domain.com</em></p>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Contact Us`.
* Set the **Custom Varations** to `hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

[demo6]: assets/wp_metropolis_demo_6.jpeg
