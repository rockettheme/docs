---
title: Somaxiom: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

Main Bottom Section
-----

![][demo]

:   1. **Text** [18%, 6%, se]
    2. **RokTabs** [18%, 36%, se]

Here is the widget breakdown for the Main Bottom section:

* Text
* Gantry Divider
* RokTabs

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><strong>Somaxiom</strong> is powered by the <strong>Gantry</strong>
Framework, which lay at the heart of the theme offering great
<strong>versatility</strong>, flexibility and simple easy of use, such as the
intuitive administrative <strong>interface</strong>.</p>

<p>It uses the <strong>960 Grid System</strong> for its modular setup, allowing
for up to 6 widgets per position row with fixed dimensions so
<strong>cross-browser</strong> precision. Amongst many <strong>other</strong>
features.</p>

<p><a class="readon" href="#"><span>Read More</span></a></p>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Built with Gantry`.
* Switch the **Widget Variations** option to **Underline**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

[roksprocket]: ../../plugins/roksprocket/
[demo]: assets/demo_7.jpeg
