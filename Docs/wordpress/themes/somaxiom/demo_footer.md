---
title: Somaxiom: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

Footer Section
-----

![][demo1]

:   1. **Text 1** [20%, 6%, se]
    2. **Text 2** [20%, 35%, se]
    3. **Text 3** [20%, 65%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text


#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for demo <strong>purposes</strong> only, to show an
example of a <strong>live site</strong>. All images are the copyright of their
respective owners.</p>

<p><a class="readon" href="#"><span>More Information</span></a></p>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Information`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>This demo contains a series of important and useful <strong>guides</strong> on how to use the basic aspects of the theme, such as <strong>how to install</strong>.</p>
<p><a class="readon" href="#"><span>starting instructions</span></a></p><div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Tutorials and Guides`.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Many features aid the overall <strong>performance</strong>, through <strong>optimized</strong> code such as compressed CSS, to Gantry side <strong>caching</strong>.</p>
<p><a class="readon" href="#"><span>Refined Coding</span></a></p><div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Site Optimization`.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_9.jpeg
[rokgallery]: ../../plugins/rokgallery
