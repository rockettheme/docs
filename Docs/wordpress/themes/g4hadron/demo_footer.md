---
title: Hadron: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Hadron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hadron:Hadron

---

Footer Section
-----

![][demo]

Here is the widget breakdown for the Footer section:

#### Text

You will need to enter the following in the main text field.

~~~ .html
<p class="rt-small-text">Hadron is available as part of the Club
Subscription</p>

<form action="http://feedburner.google.com/fb/a/mailverify" class=
"fp-newsletter-form" method="post" onsubmit=
"window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true"
target="popupwindow">
    <input class="inputbox" name="email" placeholder=
    "Your email address here ..." type="text"> <input name="uri" type="hidden"
    value="rocketthemeblog"> <input name="loc" type="hidden" value="en_US">
    <input class="readon" name="Submit" type="submit" value="Subscribe">
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Align Variation** option to **RT-Center**.
* Enter `fp-newsletter` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_8.jpeg