---
title: Enigma: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Enigma Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/enigma:Enigma

---

Sidebar Section
-----

![][demo]

:   1. **Gantry Login Form** [8%, 15%, se]
    2. **Text** [31%, 15%, se]
    3. **Text** [68%, 15%, se]

Here is the widget breakdown for the Sidebar section:

* Gantry Login Form
* Text
* Text

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting                         |
| :---------------- | :------------------------------ |
| Title             | Login Form                      |
| User Greeting     | Hi,                             |
| Title Variation   | Box 4                           |
| Margin Variation  | No Margin Bottom                |

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="customtitle1 nomargintop">
    <p class="smallmarginbottom">Listed are the top theme features for Enigma:</p>
<ul class="menu demo-list medmarginbottom">
    <li>
        <span class="item subtext">
            <span>
                Integrated Plugins
                <em><a href="http://demo.rockettheme.com/live/wordpress/enigma/plugins/">A selection of styled RocketTheme addons.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Versatile &amp; Flexible Layouts
                <em><a href="http://demo.rockettheme.com/live/wordpress/enigma/features/">Over 60 Gantry controlled grid row positions.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Eight Style Variations
                <em><a href="http://demo.rockettheme.com/live/wordpress/enigma/preset-styles/">An array of diverse, rich preset styles.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Two Menu Systems
                <em><a href="http://demo.rockettheme.com/live/wordpress/enigma/features/">Choose between Fusion and Splitmenu.</a></em>
            </span>
        </span>
    </li>
</ul>

<a href="http://demo.rockettheme.com/live/wordpress/enigma/features/" class="readon"><span>View More Features</span></a></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Theme Features`.
* Switch the **Title Variation** option to **Title 1**.
* Switch the **Margin Variation** option to **No Margin Top**.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="custombox3 shadow1">
    <blockquote class="noquotes"><p>The Enigma theme is bundled with a RocketLauncher package, which is a customized WordPress installation package, that will in effect, install the demo onto your site.</p></blockquote>
<a class="readon" href="http://demo.rockettheme.com/live/wordpress/enigma/tutorials/rocketlauncher/"><span>Read More</span></a></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `RocketLauncher Available`.
* Switch the **Box Variation** option to **Box 3**.
* Switch the **Shadow Variation** option to **Shadow 1**.
* Leaving everything else at its default setting, select **Save**.

[Demo]: assets/demo_6.jpeg
