---
title: Tessellate: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Feature Section
-----

![][demo]

:   1. **Text** [11%, 6%, se]
    2. **Text** [14%, 67%, se]
    3. **Text** [55%, 67%, se]

Here is the widget breakdown for the Feature section:

* Text
* Gantry Divider
* Text
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h3>Multiple layout options: An adapted responsive layout, or fixed layouts at 960px or 1200px wide</h3>

<p class="smallmarginbottom">A responsive layout adapts automatically to the viewing device's width, such as mobile, tablet or desktop, without the need for a separate layout or content. Mobile modes have a unique menu to aid usability. 960px and 1200px fixed layout options are also available.</p>

<a href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/" class="readon4">Read More</a>

<h3 class="largemargintop largepaddingtop">Configure the style options of Tessellate, quickly and easily, in theme settings page</h3>

<p class="smallmarginbottom">Tessellate has an extensive Color Chooser in theme settings page to provide intricate controls for each section, inclusive of overlay type, text color, background color, as well as accent colors. Edit preexisting or create new presets.</p>

<a href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/" class="readon4">Read More</a>

<h3 class="largemargintop largepaddingtop">A web font based solution for adding icons, allowing them to be extensively styled via CSS</h3>

<p class="smallmarginbottom">The theme features an updated library for Font Awesome with version 4+. This offers over 350 icons, which are fully scalable and easy to integrate into the design of the template and/or content, from widget titles to inside content items themselves.</p>

<a href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/typography/" class="readon4">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-feature-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h3>Modify your CSS with speed and efficiency</h3>

<p>LESS brings programmable coding to CSS, such as in PHP. This allows for variables and more complex operations in the stylesheets, making easier to create, update and customize.</p>

<a href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/" class="readon4">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Powered by LESS CSS` in the **Title** field.
* Set the **Widget Variations** option to **Box 3, Title 1**.
* Enter `fp-feature-b1` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h3>Full<span class="hidden-tablet"> WordPress</span> site search, powered by AJAX</h3>

<p>RokAjaxSearch uses AJAX to display WordPress site search results via a popup modal as you type, without the need for refreshing the page or being directed to a separate search page.</p>

<a href="http://ryanmpierson.no-ip.biz/wordpress/tessellate2/features-overview/" class="readon5">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `RokAjaxSearch` in the **Title** field.
* Set the **Widget Variations** option to **Box 4, Title 2**.
* Enter `fp-feature-b2` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[faq]: faq.md
