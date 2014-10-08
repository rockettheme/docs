---
title: Panacea: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Panacea Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/panacea:Panacea

---

Sidebar Section
-----

![][demo]

:   1. **Gantry Login Form** [9%, 15%, se]
    2. **Text** [43%, 15%, se]

Here is the widget breakdown for the Sidebar section:

* Gantry Login Form
* Text

#### Gantry Login Form

The login form located on the front page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting     |
| :----------       | :---------- |
| Title             | `Login`     |
| User Greeting     | `Hi,`       |
| Pre-text          | Blank       |
| Post-text         | Blank       |
| Widget Variations | Box 2       |

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="content-block">
    <div class="number-image">
        <img alt="image" height="63" src="http://demo.rockettheme.com/live/wordpress/panacea/wp-content/rockettheme/rt_panacea_wp/frontpage/number-image1.jpg" width="91"> <span class="number-image-text">One</span>
    </div><span class="heading1">Amazingly Adaptable</span>

    <p>Featuring the most flexible and configurable layout we've ever created, it has the ability to adapt to scores of layout.</p>
</div>

<div class="content-block">
    <div class="number-image">
        <img alt="image" height="63" src="http://demo.rockettheme.com/live/wordpress/panacea/wp-content/rockettheme/rt_panacea_wp/frontpage/number-image2.jpg" width="91"> <span class="number-image-text">Two</span>
    </div><span class="heading1">Lean and Clean</span>

    <p>A clean and professional design coupled with less overhead, as well as optimized code and images.</p>
</div>

<div class="content-block">
    <div class="number-image">
        <img alt="image" height="63" src="http://demo.rockettheme.com/live/wordpress/panacea/wp-content/rockettheme/rt_panacea_wp/frontpage/number-image3.jpg" width="91"> <span class="number-image-text">Three</span>
    </div><span class="heading1">Easier Customization</span>

    <p>CSS based colors and organized CSS code blocks, along with less images allowing for quicker color.</p>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
