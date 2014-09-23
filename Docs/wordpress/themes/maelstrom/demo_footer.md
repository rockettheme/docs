---
title: Maelstrom: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Maelstrom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/maelstrom:Maelstrom

---

Footer Section
-----

![][demo]

:   1. **Text 1** [25%, 7%, se]
    2. **Text 2** [25%, 34%, se]
    3. **Text 3** [25%, 68%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<img width="250" height="120" class="png client-img" alt="Clients" src="http://demo.rockettheme.com/live/wordpress/maelstrom/wp-content/rockettheme/rt_maelstrom_wp/frontpage/blank.png" />
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Icon Variation** option to **Title 7**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<strong>Address:</strong> <br /><span>1789 Cyrian Drive, Houston, TX, 00000, USA</span>
<br />
<strong>Tel No:</strong> (555) 555-55555
<br />
<strong>Email:</strong> <span>info@jan11.rockettheme.com</span>
~~~

* Enter `Our Contact Details` in the **Title** field.
* Set the **Icon Variation** option to **Icon 7**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="nomarginbottom">All demo content is for demonstrative <strong>purposes</strong> only, intended to show a representative example of a <strong>live site</strong>. All images and materials are the copyright of their respective owners.</p>
~~~

* Enter `Demo Information` in the **Title** field.
* Set the **Icon Variation** option to **Icon 8**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg
[rokgallery]: ../../plugins/rokgallery
