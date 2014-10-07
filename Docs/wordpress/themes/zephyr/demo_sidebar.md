---
title: Zephyr: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Zephyr Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/zephyr:Zephyr

---

Sidebar Section
-----

![][demo]

:   1. **Text** [8%, 12%, se]
    2. **RokTabs** [40%, 12%, se]
    3. **RokNewsPager** [8%, 52%, se]

Here is the widget breakdown for the Sidebar section:

* Text
* RokTabs
* Gantry Divider
* RokNewsPager

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="menu">
    <li><a href="#">New RokTabs Style</a></li>   
    <li><a href="#">RTL Support</a></li>
    <li><a href="#">iPhone Compatible</a></li>
    <li><a href="#">Smart Loading</a></li>  
</ul>
<br/>
<a href="#" class="readon"><span>More Features</span></a>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Popular Features`.
* Switch the **Box Variation** option to **Box 12**.
* Switch the **Title Variation** option to **Title 3**.
* Leaving everything else at its default setting, select **Save**.

#### RokTabs

This area of the demo is a RokTabs widget. RokTabs is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

[demo]: assets/demo_3.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
