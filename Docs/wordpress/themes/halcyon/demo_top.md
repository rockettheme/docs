---
title: Halcyon: Recreating the Demo - Top
description: Your Guide to Recreating Elements of the Halcyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/halcyon:Halcyon

---

Top Section
-----
![][demo]

:   1. **Top - Text** [35%, 7%, se]
    2. **Top - Text** [35%, 93%, sw]

Here is the widget breakdown for the Top section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<ul class="menu">
    <li id="item-136"><a href="http://www.rockettheme.com/" target="_blank"><span>RocketTheme</span></a></li>
    <li id="item-137"><a href="http://www.rockettheme.com/forum/" target="_blank"><span>Forum</span></a></li>
    <li id="item-138"><a href="http://www.rockettheme.com/wordpress-themes/halcyon" target="_blank"><span>Download</span></a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Widget Style** to **Flush**.
* Enter `horizmenu` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="custom">
    <div class="cart-badge">
            <div class="cart-badge-inner">
            <div class="cart-count">0</div>
            <div class="cart-title">Shopping Cart</div>
            <div class="cart-desc"><a href="#">Info on Ecwid eCommerce.</a></div>
        </div>
    </div>
</div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_1.jpeg
[menu]: ../../start/menus.md
[faq]: faq.md