---
title: Chimera: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Chimera Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Bottom Section
-----

![Bottom](assets/demo_9.jpeg)

Here is the widget breakdown for the Bottom section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container">
  <div class="gantry-width-75 wow fadeInLeft">
    <div class="rt-float-left largemarginright">
      <div class="gantry-width-75">
        <p>Get more information about this incredible theme, its features, and discover all the ways that it can help you with your future projects.</p>
      </div>
    </div>
  </div>
  <div class="gantry-width-25 wow fadeInRight" data-wow-delay="1s">
    <div class="rt-floatright">
      <a href="http://demo.rockettheme.com/live/wordpress/chimera/features-overview/" class="readon wow pulse" data-wow-delay="2s">Learn More</a>
    </div>
  </div>  
  <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Learn More About Chimera`.
* Set the **Widget Variations** setting to **Increase Top (15px), Increase Bottom (15px)**.
* Enter `fp-bottom wow fadeIn` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
