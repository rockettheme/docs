---
title: Nebulae: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Nebulae Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nebulae:Nebulae

---

Footer Section
-----

![][demo]

:   1. **Text 1** [25%, 7%, se]
    2. **Text 2** [25%, 68%, se]
    3. **Text 3** [25%, 30%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-demo-grid-2 rt-demo-grid-omega">
  <a href="#" class="mod-var-link">Home</a><br />
  <a href="#" class="mod-var-link">Features</a><br />
  <a href="#" class="mod-var-link">Extensions</a>
</div>
<div class="floatright">
  <a href="#" class="mod-var-link">Tutorials</a><br />
  <a href="#" class="mod-var-link">Styles</a><br />
  <a href="#" class="mod-var-link">WordPress</a>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Site Map` in the **Title** field.
* Set the **Title Variation** option to **Title 7**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="nomarginbottom rt-justify">All demo content is for sample <strong>purposes</strong> only, intended to represent a <strong>live site</strong>. All sample images are the copyright of <a href="http://fantasticfunmachine.blogspot.com/" target="_blank"><em class="nobold normal">Charles Guan,</em></a> kindly permitted for the Nebulae demo.</p>
~~~

* Enter `Demo Information` in the **Title** field.
* Set the **Title Variation** option to **Title 8**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><img src="http://demo.rockettheme.com/live/wordpress/nebulae/wp-content/rockettheme/rt_nebulae_wp/frontpage/footer-image1.png" alt="image" width="192" height="32" /></p>
All Rights Reserved - <a href="#">RocketTheme 2011</a>
~~~

* Enter `Other Ways to Connect` in the **Title** field.
* Set the **Title Variation** option to **Title 7**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[rokgallery]: ../../plugins/rokgallery
