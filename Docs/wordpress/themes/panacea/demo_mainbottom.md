---
title: Panacea: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Panacea Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/panacea:Panacea

---

Main Bottom Section
-----

![][demo]

:   1. **RokTabs** [15%, 6%, se]
    2. **Text** [15%, 58%, se]

Here is the widget breakdown for the Main Bottom section:

* RokTabs
* Text

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Theme <strong>performance</strong> is a key part of the development process, to ensure that the theme is as <strong>optimized</strong> as possible.</p>

<div class="rt-grid-2">
    <ul class="bullet-check">
        <li>Valid XHTML</li>
        <li>Valid CSS 3</li>
        <li>Low Image Count</li>
    </ul>
</div>
<div class="rt-grid-2">
    <ul class="bullet-check">
        <li>Compressed CSS</li>
        <li>Optimized Images</li>
        <li>Inbuilt Caching</li>
    </ul>
</div>
<div class="clear"></div>

<a class="readon" href="#"><span>Learn More</span></a>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Theme Optimization` in the **Title** field.
* Switch the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_9.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
