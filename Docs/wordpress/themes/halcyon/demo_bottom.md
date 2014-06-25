---
title: Halcyon: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Halcyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/halcyon:Halcyon

---

Bottom Section
-----

![][demo1]

:   1. **Text 1** [22%, 6%, se]
    2. **Text 2** [22%, 67%, se]

Here is the widget breakdown for the Bottom section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="custom">
    <div class="floatleft">
    <div class="smallmarginbottom"><em class="bold nobold">Products</em></div>
    <ul class="dots nomarginbottom">
        <li><a href="#"><em class="nobold normal">Laptops</em></a></li>
        <li><a href="#"><em class="nobold normal">Desktop PC</em></a></li>
        <li><a href="#"><em class="nobold normal">Printers</em></a></li>
        <li class="nomarginbottom"><a href="#"><em class="nobold normal">Tablets</em></a></li>
    </ul>
</div>
<div class="floatleft largemarginleft">
    <div class="smallmarginbottom">&nbsp;</div>
    <ul class="dots nomarginbottom">
        <li><a href="#"><em class="nobold normal">Monitors</em></a></li>
        <li><a href="#"><em class="nobold normal">Keyboards</em></a></li>
        <li><a href="#"><em class="nobold normal">Speakers</em></a></li>
        <li class="nomarginbottom"><a href="#"><em class="nobold normal">Cameras</em></a></li>
    </ul>
</div>
<div class="floatleft largemarginleft">
    <div class="smallmarginbottom">&nbsp;</div>
    <ul class="dots nomarginbottom">
        <li><a href="#"><em class="nobold normal">Storage</em></a></li>
        <li><a href="#"><em class="nobold normal">Phones</em></a></li>
        <li><a href="#"><em class="nobold normal">Accessories</em></a></li>
        <li class="nomarginbottom"><a href="#"><em class="nobold normal">Seasonal</em></a></li>
    </ul>
</div>
<div class="floatleft nomarginright largemarginleft">
    <div class="smallmarginbottom">&nbsp;</div>
    <ul class="dots nomarginbottom">
        <li><a href="#"><em class="nobold normal">Delivery</em></a></li>
        <li><a href="#"><em class="nobold normal">Refunds</em></a></li>
        <li><a href="#"><em class="nobold normal">Careers</em></a></li>
        <li class="nomarginbottom"><a href="#"><em class="nobold normal">Sitemap</em></a></li>
    </ul>
</div></div>
~~~

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="custom">
    <div class="floatleft">
    <div class="smallmarginbottom"><em class="bold nobold">Demo Information</em></div>
    <a class="nobold">All demo content is for <strong>sample</strong> purposes only, intended to represent a live site. All images are the copyright of their respective owners. Please download the <strong>RocketLauncher</strong> pack to install a copy of the demo.</a>
</div></div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_10.jpeg
