---
title: Plethora: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Footer Section
-----

![][demo]

:   1. **Text** [15%, 5%, se]
    2. **Text** [15%, 36%, se]
    3. **Text** [15%, 66%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">RocketLauncher<span class="hidden-tablet"> Package</span></a></h4>
<p class="rt-text-small nomarginbottom">Quickly demo replication</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">Editable <span class="hidden-tablet">PNG </span>Sources</a></h4>
<p class="rt-text-small nomarginbottom">Adobe&reg; Fireworks PNG Sources</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#"><span class="hidden-tablet">Free </span>Documentation</a></h4>
<p class="rt-text-small nomarginbottom">Online and publicly available</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">Integrated Addons</a></h4>
<p class="rt-text-small nomarginbottom">Free &amp; GPL RokPlugins</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `About Plethora` in the **Title** field.
* Set the **Widget Variations** to **Box 1**.
* Enter `fp-footer-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-container rt-center">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/about-us/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-star"></i></span><br />
                <span>About</span>              
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/the-team/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-users"></i></span><br />
                <span>Team</span>               
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/services/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-briefcase"></i></span><br />
                <span>Service</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/pricing-tables/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-list-alt"></i></span><br />
                <span>Pricing</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/portfolio/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-cogs"></i></span><br />
                <span>Work</span>               
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/category/blog/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-file-text"></i></span><br />
                <span>Blog</span>               
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/faq/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-comments"></i></span><br />
                <span>FAQ</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/contact-us/" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-ticket"></i></span><br />
                <span>Contact</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="http://demo.rockettheme.com/live/wordpress/plethora/?tmpl=404" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-chain-broken"></i></span><br />
                <span>Error</span>              
            </a>
        </div>
    </div>              
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Sample Pages` in the **Title** field.
* Set the **Widget Variations** to **Title 1**.
* Enter `fp-footer-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

You will need to enter the following in the main text field.

~~~ .html
<p>Enter your email address below and subscribe to our newsletter. We hate spam as much as you do.</p>
<form class="rt-form-horizontal" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Your Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>

<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer nomarginleft">
            <div class="module-title largemargintop">
                <h2 class="title"><span>Quick Links</span></h2>
            </div>
            <ul class="rt-footer-menu list-group">
                <li><i class="fa fa-star fa-fw"></i><a href="#"> About</a></li>
                <li><i class="fa fa-edit fa-fw"></i><a href="#"> Docs</a></li>
                <li><i class="fa fa-cog fa-fw"></i><a href="#"> Help</a></li>
                <li><i class="fa fa-comment fa-fw"></i><a href="#"> Contact</a></li>
            </ul>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <div class="module-title largemargintop">
                <h2 class="title"><span>Elsewhere</span></h2>
            </div>
            <ul class="rt-footer-menu list-group">
                <li><i class="fa fa-twitter fa-fw"></i><a href="#"> Twitter</a></li>
                <li><i class="fa fa-facebook fa-fw"></i><a href="#"> Facebook</a></li>
                <li><i class="fa fa-google-plus fa-fw"></i><a href="#"> Google Plus</a></li>
                <li><i class="fa fa-rss fa-fw"></i><a href="#"> RSS</a></li>
            </ul>
        </div>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `More Info` in the **Title** field.
* Set the **Widget Variations** to **Title 1**.
* Enter `fp-footer-c` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/
