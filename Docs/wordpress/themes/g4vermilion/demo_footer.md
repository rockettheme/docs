---
title: Vermilion: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Footer Section
-----

![][demo]

:   1. **Text** [20%, 7%, se]
    2. **Text** [20%, 50%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-icon-badge rt-badge-left"></div>
<h2 class="title"><a href="#">Demo Info</a></h2>
<p>All demo content is for sample purpose only. All content images have been
sourced from <a href="http://unsplash.com/">Unsplash</a> or <a href=
"http://flickr.com">Flickr</a>. <a data-rokbox="" data-rokbox-element=
"#rt-attribution" href="#">Click for Attribution</a>.</p>
<p>Please use the <a href=
"http://www.rockettheme.com/wordpress/themes/vermilion">Vermilion
RocketLauncher</a> to install an equivalent of the demo.</p>
<div class="clear"></div>
<div class="hidden">
    <div id="rt-attribution">
        <h3><a href="http://flickr.com">Flickr</a></h3>
        <p>The following images are used in the demo, available via Creative
        Commons License:</p>
        <ul>
            <li><a href=
            "http://www.flickr.com/photos/47757737@N00/6429375049/">http://www.flickr.com/photos/47757737@N00/6429375049/</a></li>
            <li><a href=
            "http://www.flickr.com/photos/85297901@N00/3523325401/">http://www.flickr.com/photos/85297901@N00/3523325401/</a></li>
            <li><a href=
            "http://www.flickr.com/photos/21314760@N00/655111542/">http://www.flickr.com/photos/21314760@N00/655111542/</a></li>
            <li><a href=
            "http://www.flickr.com/photos/41346951@N05/10057246483/">http://www.flickr.com/photos/41346951@N05/10057246483/</a></li>
        </ul>
        <h3><a href="http://unsplash.com">Unsplash</a></h3>
        <p>The following images are used in the demo and/or distributed with
        the template, and are freely available:</p>
        <ul>
            <li><a href=
            "https://s3.amazonaws.com/ooomf-com-files/wjNV6gWuQkqeuH8txHc9_sylwiabartyzel_unsplash_tatry_03.jpg">
            https://s3.amazonaws.com/ooomf-com-files/wjNV6gWuQkqeuH8txHc9_sylwiabartyzel_unsplash_tatry_03.jpg</a></li>
            <li><a href=
            "http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_5255bf45a4a45_1.JPG">
            http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_5255bf45a4a45_1.JPG</a></li>
            <li><a href=
            "http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_52d5c05422a47_1.JPG">
            http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_52d5c05422a47_1.JPG</a></li>
            <li><a href=
            "https://s3.amazonaws.com/ooomf-com-files/yQPqzfj7SL24wC0RMfXu_DSC_0594.jpg">
            https://s3.amazonaws.com/ooomf-com-files/yQPqzfj7SL24wC0RMfXu_DSC_0594.jpg</a></li>
            <li><a href=
            "https://s3.amazonaws.com/ooomf-com-files/Z3LXxzFMRe65FC3Dmhnp_woody_unsplash_DSC0129.jpg">
            https://s3.amazonaws.com/ooomf-com-files/Z3LXxzFMRe65FC3Dmhnp_woody_unsplash_DSC0129.jpg</a></li>
            <li><a href=
            "https://s3.amazonaws.com/ooomf-com-files/Ta3Z3hRxTTCTHmi1s1B1_Brooklyn_Bridge_by_Anders_Jilden.jpg">
            https://s3.amazonaws.com/ooomf-com-files/Ta3Z3hRxTTCTHmi1s1B1_Brooklyn_Bridge_by_Anders_Jilden.jpg</a></li>
            <li><a href=
            "http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_52b326f55b5f9_1.JPG">
            http://666a658c624a3c03a6b2-25cda059d975d2f318c03e90bcf17c40.r92.cf1.rackcdn.com/unsplash_52b326f55b5f9_1.JPG</a></li>
            <li><a href=
            "http://unsplash.s3.amazonaws.com/batch%207/girl-flowers.jpg">http://unsplash.s3.amazonaws.com/batch%207/girl-flowers.jpg</a></li>
        </ul>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Demo Info` in the **Title** field.
* Enter `fp-footer-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<div class="rt-icon-badge rt-badge-left"><a href="#"><span class="fa fa-copy"></span></a></div>

<h2 class="title"><a href="#">Sample Pages</a></h2>
<p>See a range of example pages and layouts, that are possible with the Vermilion theme.</p>

<div class="clear"></div>

<div class="gantry-row">
    <div class="gantry-width-100">
        <div class="gantry-width-spacer">
            <form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
                <input type="hidden" value="rocketthemeblog" name="uri" />
                <input type="hidden" name="loc" value="en_US" />
                <input type="submit" name="Submit" class="readon" value="Join" />
            </form>
        </div>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Sample Pages` in the **Title** field.
* Enter `fp-footer-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_11.jpeg
[roksprocket]: ../../plugins/roksprocket/
