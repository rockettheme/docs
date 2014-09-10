---
title: Praxis: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Footer Section
-----

![][demo]

:   1. **Text** [15%, 6%, se]
    2. **Gantry Login Form** [15%, 53%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Gantry Login Form

#### Text

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-footer-logo rt-floatleft largepaddingright largemarginbottom"></div>

<p class="largemarginleft"><span class="hidden-tablet">All demo content is for sample purposes only, intended to show a live site. </span>All images are licensed from <strong><a href="http://www.shutterstock.com">ShutterStock</a></strong> for exclusive use on this demo site. <span class="visible-large">To replicate a near equivalent copy of the demo onto your server, use the RocketLauncher package.</span></p>

<div class="clear"></div><br />

<div class="hidden-phone">
    <p class="promo3">+1 (123) 456-5555-555</p>
  <p class="medmarginbottom">Praxis Theme, LLC</p>
  <p class="medmarginbottom">123 WordPress Boulevard</p>
  <p class="medmarginbottom">Seattle, WA 00000, USA</p>
  <p><a href="#">noreply@domain.com</a></p> 
</div>
~~~

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting        |  
| :---------------- | :------------- |  
| Title             | Blank          |  
| User Greeting     | Hi,            |  
| Pre-text          | Blank          |  
| Post-text         | Blank          |  
| Margin Variation  | No Margin Top  |  
| Padding Variation | No Padding Top |  
| Custom Variations | `hidden-phone` |  

[demo]: assets/demo_11.jpeg