---
title: Acacia: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Acacia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/acacia:Acacia

---

Footer Section
-----

![][demo]

:   1. **Text** [15%, 6%, se]
    2. **Gantry Login Form** [15%, 52%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Gantry Login Form

#### Text

You will need to enter the following in the main text field.

~~~ .html
<p class="rt-intro-text">All demo content is for sample purpose only, intended to show a live site. Use the <a href="#">Acacia RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
<p>Acacia is only available as part of the Club Subscription.</p>

<div class="gantry-width-40">
    <div class="gantry-width-spacer">
        <span id="rt-footer-logo"></span>
    </div>
</div>

<div class="gantry-width-60">
    <div class="gantry-width-spacer">
        <span class="rt-intro-text">+1(123)456-5555-555</span><br />
        <span>Acacia Theme, LLC</span><br />
        <span>123 WordPress Boulevard</span><br />
        <span>Seattle, WA 00000, USA</span><br />
        <span><a href="#">noreply/@domain.com</a></span>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting                         | 
| :---------------- | :------------------------------ | 
| Title             | Blank                           | 
| User Greeting     | Hi,                             | 
| Pre-text          | Blank                           | 
| Post-text         | Blank                           | 
| Custom Variations | `rt-footer-login`               |  

[demo]: assets/demo_8.jpeg