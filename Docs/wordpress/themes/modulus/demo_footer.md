---
title: Modulus: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Modulus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/modulus:Modulus

---

Footer Section
-----

![][demo]

:   1. **Text 1** [20%, 7%, se]
    2. **Text 2** [20%, 68%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="floatright">
  <ul class="list-icon fp-facebook nomarginbottom largemargintop">
    <li><a href="#"><em class="nobold normal">Facebook</em></a></li>
  </ul>
  <ul class="list-icon fp-twitter nomarginbottom">
    <li><a href="#"><em class="nobold normal">Twitter</em></a></li>
  </ul>
  <ul class="list-icon fp-flickr nomarginbottom">
    <li><a href="#"><em class="nobold normal">Flickr</em></a></li>
  </ul>
  <ul class="list-icon fp-vimeo nomarginbottom">
    <li><a href="#"><em class="nobold normal">Vimeo</em></a></li>
  </ul>
</div>

<div class="floatright fp-contact">
  <ul class="list-icon nomarginbottom largemargintop">
    <li><span class="text-icon person">7001 St Thomas Avenue</span></li>
    <li><span class="text-icon">Washington, 00000, USA</span></li>
    <li><span class="text-icon phone">1 (555) 555-555 / 555-556</span></li>  
    <li><span class="text-icon email">contact@modulus.domain</span></li>
  </ul>
</div>

<div class="module-title nomarginbottom"><h3 class="title">Contact Information</h3></div>
<p>Modulus <em>(January 2012)</em> WordPress Club Theme, designed by RocketTheme LLC, available as part of a WordPress Club Subscription.</p>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Widget Style** option to **Flush Bottom**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="attention nomarginbottom">
  <em class="bold">DEMO NOTICE:</em> All demo content is for sample purposes only, intended to represent a live site. Download a launcher pack to copy the demo.
</p>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg
[rokgallery]: ../../plugins/rokgallery
