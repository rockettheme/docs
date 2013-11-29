---
title: Stratos: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Stratos Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/stratos:Stratos

---

Footer Section
-----

![][demo]

:   1. **Text** [18%, 5%, se]
    2. **Text** [18%, 66%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text

#### Text

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-footer-logo"></div>

<p class="promo3">All demo content is for <strong>sample</strong> purposes only, intended to show a live site. Use the Stratos <strong>RocketLauncher</strong> to install an equivalent of the demo onto your site.</p>

<p class="promo3"><strong>Stratos</strong> is only available as part of a Club Subscription.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Box Variation** to **Box 5**.
* Enter `fp-footer-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

The second Text widget in the section is made a lot like the others. You will need to enter the following in the main text field.

~~~ .html
<p class="rt-uppercase promo3 smallmarginbottom"><a href="#">123 WordPress Boulevard</a></p>
<p class="rt-uppercase promo3 nomarginbottom"><a href="#">Seattle, WA 00000, USA</a></p>

<br />

<p><a href="#">noreply@domain.com</a></p>

<div class="rt-social-buttons">
    <a href="http://www.facebook.com/RocketTheme" class="social-button rt-social-button-1">
    <span class="icon-facebook"></span>
  </a>
  <a href="https://twitter.com/rockettheme" class="social-button rt-social-button-2">
    <span class="icon-twitter"></span>
  </a>
  <a href="http://www.rockettheme.com/blog?format=feed&amp;type=rss" class="social-button rt-social-button-3">
    <span class="icon-rss"></span>
  </a>
  <a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-social-button-4">
    <span class="icon-google-plus"></span>
  </a>
  <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Box Variation** option to **Box 5**.
* Enter `fp-footer-b` in the **Custom Varations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg