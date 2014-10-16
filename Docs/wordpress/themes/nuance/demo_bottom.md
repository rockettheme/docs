---
title: Nuance: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Bottom Section
-----

![][demo]

:   1. **Text 1** [15%, 5%, se]
    2. **Text 2** [15%, 36%, se]
    3. **Text 3** [15%, 65%, se]

Here is the widget breakdown for the Bottom section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<hr />

<div>
    <a href=
    "http://demo.rockettheme.com/live/wordpress/nuance/features-overview/">Basic
    support for third party plugins BuddyPress and BBPress</a>
</div>

<div>
    <small><i class="fa fa-file-text-o"></i> Gantry core enabled</small>
</div>
<hr>

<div>
    <a href=
    "http://demo.rockettheme.com/live/wordpress/nuance/features-overview/">Disable
    the Mainbody or Component areas on a per override basis</a>
</div>

<div>
    <small><i class="fa fa-file-text-o"></i> Theme settings toggles</small>
</div>
<hr>

<div>
    <a href=
    "http://demo.rockettheme.com/live/wordpress/nuance/features-overview/">A
    separate, togglable LESS file for demo frontpage specific CSS</a>
</div>

<div>
    <small><i class="fa fa-file-text-o"></i> Optimize page load size</small>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About Nuance`.
* Enter `fp-bottom-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<hr />

<div>
    Advanced dropdown menu system with responsive mobile support
</div><small><a href=
"http://demo.rockettheme.com/live/wordpress/nuance/menu-options/"><i class=
"fa fa-angle-double-right"></i> Learn More</a></small>
<hr>

<div>
    CSS selectors available for Internet Explorer 8 with the Selectivizr script
</div><small><a href=
"http://demo.rockettheme.com/live/wordpress/nuance/features-overview/"><i class="fa fa-angle-double-right"></i>
Learn More</a></small>
<hr>

<div>
    Custom page suffixes for specific stylistic modifications
</div><small><a href=
"http://demo.rockettheme.com/live/wordpress/nuance/features-overview/"><i class="fa fa-angle-double-right"></i>
Learn More</a></small>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Top Features`.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<hr />

<div>
    Illustration
</div>

<div class="progress">
    <div class="progress-bar progress-bar-success" style="width: 40%">
        <span class="sr-only">40%</span>
    </div>
</div>

<div>
    Programming
</div>

<div class="progress">
    <div class="progress-bar progress-bar-info" style="width: 20%">
        <span class="sr-only">20%</span>
    </div>
</div>

<div>
    Photography
</div>

<div class="progress">
    <div class="progress-bar progress-bar-warning" style="width: 60%">
        <span class="sr-only">60%</span>
    </div>
</div>

<div>
    Web Design
</div>

<div class="progress">
    <div class="progress-bar progress-bar-danger" style="width: 80%">
        <span class="sr-only">80%</span>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `My Skills`.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/
