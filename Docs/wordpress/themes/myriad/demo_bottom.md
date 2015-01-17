---
title: Myriad: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Myriad Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Bottom Section
-----

![Bottom](assets/demo_12.jpeg)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 37%, se]
    3. **Text 3** [20%, 68%, se]

Here is the widget breakdown for the Bottom section:

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for sample purposes only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.</p>
<p><span class="hidden-tablet"> Use the <a href="http://www.rockettheme.com/wordpress/themes/myriad">RocketLauncher</a> to install a demo equivalent onto your site.</span></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Info`.
* Enter `fp-bottom-a rt-modtitle-uppercase wow fadeInDown` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/blog">Read the Latest Blog Post</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/the-team">View our Global Team</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/promotions">Enjoy a Promotion</a></p>
<p class="smallmarginbottom"><a href="http://www.shareasale.com/shareasale.cfm?merchantID=30300">Become an Affiliate</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About RocketTheme`.
* Enter `fp-bottom-b rt-modtitle-uppercase hidden-phone wow fadeInDown` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
  <div class="gantry-width-container">
    <div class="gantry-width-50">
      <div class="gantry-width-spacer">
        <a href="https://www.facebook.com/RocketTheme"><i class="fa fa-facebook fa-fw"></i> <span>Facebook</span></a>
      </div>
    </div>
    <div class="gantry-width-50">
      <div class="gantry-width-spacer">
        <a href="https://twitter.com/rockettheme"><i class="fa fa-twitter fa-fw"></i> <span>Twitter</span></a>
      </div>
    </div>    
  </div>
</div>

<div class="clear"></div>

<div class="gantry-row">
  <div class="gantry-width-container">
    <div class="gantry-width-50">
      <div class="gantry-width-spacer">
        <a href="https://plus.google.com/+rockettheme"><i class="fa fa-google-plus fa-fw"></i> <span>Google+</span></a>
      </div>
    </div>
    <div class="gantry-width-50">
      <div class="gantry-width-spacer">
        <a href="http://www.rockettheme.com/product-updates?rss"><i class="fa fa-rss fa-fw"></i> <span>RSS</span></a>
      </div>
    </div>    
  </div>
</div>

<div class="clear"></div>

<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
  <input type="text" name="email" class="inputbox" placeholder="Your Email" />
  <input type="hidden" name="uri" value="rocketthemeblog" />
  <input type="hidden" value="en_US" name="loc" />
  <input type="submit" value="Join" class="readon" name="Submit" />
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Stay Connected`.
* Enter `fp-bottom-c rt-modtitle-uppercase hidden-phone wow fadeInDown` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
