---
title: Paradigm: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Paradigm Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/Paradigm:Paradigm

---

Footer Section
-----

![][demo]

:   1. **Text 1** [20%, 6%, se]
    2. **Text 2** [20%, 35%, se]
    3. **Text 3** [20%, 65%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<p><span>Updates, upcoming themes, and <span class="visible-large">great </span>deals!</span></p>
<form class="fp-footer-form" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
    <input type="text" placeholder="Your Email" class="inputbox" name="email">
    <input type="hidden" value="rocketthemeblog" name="uri" />
    <input type="hidden" name="loc" value="en_US" />
    <input type="submit" name="Submit" class="readon" value="Join" />
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `[span class="hidden-tablet hidden-phone"]Join Our [/span]Newsletter` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<p>We are always open for a quick chat!</p>
<h5><span class="icon-phone"></span>&nbsp;&nbsp;678-123-6789</h5>
<h5><span class="icon-envelope"></span>&nbsp;hello@paradigm.com</h5>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Get in Touch` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-block gantry-width-33">
    <div class="gantry-width-spacer">
        <h2 class="title">Info</h2>
        <p class="nomarginbottom"><a href="#">About</a></p>
        <p class="nomarginbottom"><a href="#">Blog</a></p>
        <p class="nomarginbottom"><a href="#">Team</a></p>
    </div>
</div>

<div class="gantry-width-block gantry-width-33">
    <div class="gantry-width-spacer">
        <h2 class="title">Work</h2>
        <p class="nomarginbottom"><a href="#">Portfolio</a></p>
        <p class="nomarginbottom"><a href="#">Services</a></p>
    </div>
</div>

<div class="gantry-width-block gantry-width-33">
    <div class="gantry-width-spacer">
        <h2 class="title">Support</h2>  
        <p class="nomarginbottom"><a href="#">Help</a></p>
        <p class="nomarginbottom"><a href="#">Contact</a></p>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-footer-menu` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_8.jpeg