---
title: Nuance: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Footer Section
-----

![][demo]

:   1. **Text 1** [15%, 5%, se]
    2. **Text 2** [15%, 36%, se]
    3. **Text 3** [15%, 65%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for sample purpose only. All content images are freely available from <a href="http://unsplash.com">Unsplash</a>.</p>

<p>Use the <a href="http://www.rockettheme.com/wordpress/themes/nuance">RocketLauncher</a> to install a demo equivalent onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Info`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/forum/wordpress-theme-nuance">Post in Forum Community</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/docs/wordpress/themes/nuance">Read Full Documentation</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/forum/wordpress-theme-nuance">Send Support Email</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/docs/wordpress/themes/nuance">Create Premier Ticket</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Support and Help`.
* Enter `hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="https://www.facebook.com/RocketTheme"><span class="icon-facebook-sign"></span> <span>Facebook</span></a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="https://twitter.com/rockettheme"><span class="icon-twitter-sign"></span> <span>Twitter</span></a>
        </div>
    </div>
</div>

<div class="clear smallmarginbottom"></div>

<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.linkedin.com/in/rockettheme"><span class="icon-linkedin-sign"></span> <span>LinkedIn</span></a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.pinterest.com/rockettheme/"><span class="icon-pinterest-sign"></span> <span>Pinterest</span></a>
        </div>
    </div>
</div>

<div class="clear largemarginbottom"></div>

<div class="gantry-row">
    <div class="gantry-width-100">
        <div class="gantry-width-spacer">
            <form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" class="inputbox" name="email">
                <input type="hidden" value="rocketthemeblog" name="uri" />
                <input type="hidden" name="loc" value="en_US" />
                <input type="submit" name="Submit" class="readon" value="Join" />
            </form>
        </div>
    </div>
</div>
<div class="clear"></div>       
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Stay Connected`.
* Enter `fp-footer-c hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_10.jpeg
[roksprocket]: ../../plugins/roksprocket/
