---
title: Leviathan: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Leviathan Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/leviathan:Leviathan

---

Footer Section
-----
![][footer]

:   1. **Text** [25%, 8%, se]
    2. **Text** [25%, 75%, se]

Here's the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text

### Text
You'll need to enter the following in the main text field to create this text widget as it appears in our demo. The title is left blank.

~~~
<p>
    <img class="rt-noborder" src="http://demo.rockettheme.com/wordpress/wp_leviathan/wp-content/rockettheme/rt_leviathan_wp/frontpage/footer/logo-footer.png" alt="Logo" />
</p>

<span>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site.</span>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Margin Variation** option to **No Margin Bottom**.
* Set the **Padding Variation** option to **No Padding Bottom**.
* Leaving everything else at its default setting, select **Save**.

### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Text
The second Text widget in the section is made a lot like the other. You'll need to enter the following in the main text field.

~~~
<div class="rt-social-buttons">
  <a class="social-button rt-facebook-btn" href="http://www.facebook.com/RocketTheme"><span></span></a>
  <a class="social-button rt-twitter-btn" href="https://twitter.com/rockettheme"><span></span></a>
  <a class="social-button rt-google-btn" href="https://plus.google.com/114430407008695950828/posts"><span></span></a>
  <a class="social-button rt-rss-btn" href="http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span></span></a>
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Follow Us`.
* Set the **Title Variation** option to **Title 1**.
* Set the **Module Variation** option to **No Margin Bottom**.
* Set the **Padding Variation** option to **No Padding Bottom**.
* Set the **Custom Varations** to `hidden-phone`.
* Leaving everything else at its default setting, select **Save**.

[footer]: assets/demo_footer.jpeg