---
title: Omnicron: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Omnicron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/omnicron:Omnicron

---

Bottom Section
-----

![][demo]

:   1. **Text 1** [15%, 6%, se]
    2. **Text 2** [15%, 36%, se]
    3. **Text 3** [15%, 67%, se]

Here is the widget breakdown for the Bottom section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-block rt-demo-typo-block">
<strong>OFFLINE:</strong> <em>31.08.10 @ 12:31 EST</em>. Sharing hosting servers are currently disabled due to a backup error. <a href="#">http://bit.ly/bWZUiKq</a>
</div>
<div class="rt-block rt-demo-typo-block">
<strong>RESTORED:</strong> <em>29.08.10 @ 18:53 EST</em>. Email has been restored. All received messages are now synced. <a href="#">http://bit.ly/cWXUiFt</a>
</div>
<div class="rt-block rt-demo-typo-block">
<strong>OFFLINE:</strong> <em>28.08.10 @ 23:14 EST</em>. Our email system is down. Backup servers are trapping all sent emails. <a href="#">http://bit.ly/wQDSpKl</a>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Service Updates` in the **Title** field.
* Set the **Box Variation** option to **Box 4**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<img width="270" height="207" class="png" alt="Sponsors" src="http://demo.rockettheme.com/live/wordpress/omnicron/wp-content/rockettheme/rt_omnicron_wp/frontpage/sponsors.png" />
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Our Partners` in the **Title** field.
* Set the **Box Variation** option to **Box 4**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="bullet-latest">
    <li>
        <span class="list-time">
            <span class="list-date">05</span>
            <span class="list-month">Sep</span>
            <span class="list-year">2010</span>
        </span>
        <a href="#">MAINTENANCE: We will be performing a scheduled maintenance of all our servers on 14 Sep 2010 at 00.00 EST.</a>
    </li>
    <li>
        <span class="list-time">
            <span class="list-date">31</span>
            <span class="list-month">Aug</span>
            <span class="list-year">2010</span>
        </span>
        <a href="#">BLOG: Net Neutrality is a popular political topic at present, and we stand by its main aims, to ensure freedom is maintained.</a>
    </li>
    <li>
        <span class="list-time">
            <span class="list-date">27</span>
            <span class="list-month">Aug</span>
            <span class="list-year">2010</span>
        </span>
        <a href="#">PRODUCT: We are pleased to offer a new spam protection system for all our clients, with a 30% off introductory offer.</a>
    </li>
</ul>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Product Blog` in the **Title** field.
* Set the **Box Variation** option to **Box 4**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
