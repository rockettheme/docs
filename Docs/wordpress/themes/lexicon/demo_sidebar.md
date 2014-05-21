---
title: Lexicon: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Lexicon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/lexicon:Lexicon

---

Sidebar Section
-----

![][demo]

:   1. **Text 1** [6%, 16%, se]
    2. **Text 2** [37%, 16%, se]

Here is the widget breakdown for the Sidebar section:

* Text
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<ul class="menu">
    <li><a href="http://demo.rockettheme.com/live/wordpress/lexicon/features-overview/">Gantry<span class="hidden-tablet"> Framework</span></a></li>
    <li><a href="http://demo.rockettheme.com/live/wordpress/lexicon/menu-options/">Dropdown<span class="hidden-tablet"> Menu</span></a></li>
    <li><a href="http://demo.rockettheme.com/live/wordpress/lexicon/widget-variations/"><span class="hidden-tablet">Widget </span>Variations</a></li>
    <li><a href="http://demo.rockettheme.com/live/wordpress/lexicon/widget-positions/"><span class="hidden-tablet">Widget </span>Positions</a></li>
    <li><a href="http://demo.rockettheme.com/live/wordpress/lexicon/typography/"><span class="hidden-tablet">Custom </span>Typography</a></li>
    <li><a href="#"><span class="hidden-tablet">Multiple </span>Presets</a></li>
</ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Inside Lexicon`.
* Set the **Widget Variations** to **Box 1, Title 1**.
* Enter `fp-sidebar-01` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<span>Google Chrome</span>
<span class="rt-text-small"><em>Webkit-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span>

<hr />

<span>Apple Safari</span>
<span class="rt-text-small"><em>Webkit-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-half-empty"></span> <span class="icon-star-empty"></span>

<hr />

<span>Mozilla Firefox</span>
<span class="rt-text-small"><em>Gecko-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span>

<hr />

<span>Microsoft Internet Explorer</span>
<span class="rt-text-small"><em>Trident-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span> <span class="icon-star-empty"></span>

<hr />

<span>Opera</span>
<span class="rt-text-small"><em>Presto-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Browser Survey`.
* Set the **Widget Variations** to **Box 2, Title 2**.
* Enter `fp-sidebar-02` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/