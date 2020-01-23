---
title: Spectral: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Copyright Section
-----

![][demo]

:   1. **Gantry Copyright** [30%, 5%, se]
    2. **Text** [30%, 37%, se]
    2. **Gantry To Top** [30%, 87%, se]

Here is the widget breakdown for the Copyright section:

* Gantry Copyright
* Gantry Divider
* Text
* Gantry Divider
* Gantry To Top

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Gantry Copyright

The Gantry Copyright widget places a tiny Copyright notification at the bottom of the page. The only thing you need to change in this widget to match the demo is the text field, which includes: `Designed by RocketTheme`.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

You will need to enter the following in the main text field.

~~~ .html
<div id="rt-image-copyright-block">
    <a href="#" data-rokbox data-rokbox-element="#rt-image-copyright">Image Copyright &amp; Attribution</a>
    <div class="hidden">
        <div id="rt-image-copyright">
            <p>Images used in the theme backgrounds and for the frontpage content have been acquired from Flickr under the Creative Commons license, which requires attribution for use. A list of all the images in use and their respective authors is listed below. In addition, images used on the Pages items are copyrighted to <a href="http://www.shutterstock.com">Shutterstock</a>.</p>
            <ul>
                <li><a href="http://www.flickr.com/photos/leshaines123/8747316385/">http://www.flickr.com/photos/leshaines123/8747316385/</a>
                <br />
                Les Haines</li>
                <li><a href="http://www.flickr.com/photos/31216636@N00/2515936612/">http://www.flickr.com/photos/31216636@N00/2515936612/</a>
                <br />
                David Evers</li>
                <li><a href="http://www.flickr.com/photos/astragony/4530142631/">http://www.flickr.com/photos/astragony/4530142631/</a><br />
                Daniel Zedda</li>
                <li><a href="http://www.flickr.com/photos/fjalarcon/4992051134/">http://www.flickr.com/photos/fjalarcon/4992051134/</a><br />
                &lt;F.J&gt;</li>
                <li><a href="http://www.flickr.com/photos/seyyed_mostafa_zamani/6055551332/">http://www.flickr.com/photos/seyyed_mostafa_zamani/6055551332/</a><br />
                seyed mostafa zamani</li>
                <li><a href="http://www.flickr.com/photos/seyyed_mostafa_zamani/6144187775/">http://www.flickr.com/photos/seyyed_mostafa_zamani/6144187775/</a><br />
                seyed mostafa zamani</li>
                <li><a href="http://www.flickr.com/photos/wili/295189351/">http://www.flickr.com/photos/wili/295189351/</a><br />
                Ville Miettinen</li>
                <li><a href="http://www.flickr.com/photos/10239866@N03/2192445708/">http://www.flickr.com/photos/10239866@N03/2192445708/</a><br />
                Quyen Nguyen</li>
                <li><a href="http://www.flickr.com/photos/eelssej_/394101773/">http://www.flickr.com/photos/eelssej_/394101773/</a><br />
                Jesslee Cuizon</li>
                <li><a href="http://www.flickr.com/photos/eneas/628005096/">http://www.flickr.com/photos/eneas/628005096/</a><br />
                Eneas De Troya</li>
                <li><a href="http://www.flickr.com/photos/seier/2780704352/">http://www.flickr.com/photos/seier/2780704352/</a><br />
                seier+seier</li>
                <li><a href="http://www.flickr.com/photos/dexxus/4103104594/">http://www.flickr.com/photos/dexxus/4103104594/</a><br />
                paul bica</li>
                <li><a href="http://www.flickr.com/photos/31246066@N04/4250392708/">http://www.flickr.com/photos/31246066@N04/4250392708/</a><br />
                Ian Sane</li>
                <li><a href="http://www.flickr.com/photos/d2k6/5047947055/">http://www.flickr.com/photos/d2k6/5047947055/</a><br />
                Luis Hernandez</li>
                <li><a href="http://www.flickr.com/photos/seyyed_mostafa_zamani/5860896468/">http://www.flickr.com/photos/seyyed_mostafa_zamani/5860896468/</a><br />
                seyed mostafa zamani</li>
                <li><a href="http://www.flickr.com/photos/chrismatos/5905483355/">http://www.flickr.com/photos/chrismatos/5905483355/</a><br />
                Chrismatos ♥Too busy, sorry</li>
                <li><a href="http://www.flickr.com/photos/mksystem/6321979595/">http://www.flickr.com/photos/mksystem/6321979595/</a><br />
                Mikhail Koninin</li>
                <li><a href="http://www.flickr.com/photos/terence_s_jones/6684473529/">http://www.flickr.com/photos/terence_s_jones/6684473529/</a><br />
                Terence S. Jones</li>
                <li><a href="http://www.flickr.com/photos/pagedooley/6844006654/">http://www.flickr.com/photos/pagedooley/6844006654/</a><br />
                Kevin Dooley</li>
                <li><a href="http://www.flickr.com/photos/hansel5569/7109176877/">http://www.flickr.com/photos/hansel5569/7109176877/</a><br />
                55Laney69</li>
                <li><a href="http://www.flickr.com/photos/duncanh1/8553010494/">http://www.flickr.com/photos/duncanh1/8553010494/</a><br />
                [Duncan]</li>
                <li><a href="http://www.flickr.com/photos/mikebaird/2985066755/">http://www.flickr.com/photos/mikebaird/2985066755/</a><br />
                Mike Baird</li>
                <li><a href="http://www.flickr.com/photos/thomasleuthard/5226290116/">http://www.flickr.com/photos/thomasleuthard/5226290116/</a><br />
                Thomas Leuthard</li>
                <li><a href="http://www.flickr.com/photos/58842866@N08/5388048563/">http://www.flickr.com/photos/58842866@N08/5388048563/</a><br />
                tommerton2010</li>
                <li><a href="http://www.hdwallpapers.in/walls/chicago_nights-wide.jpg">http://www.hdwallpapers.in/walls/chicago_nights-wide.jpg</a><br />
                <a href="http://www.flickr.com/photos/65315936@N00/">http://www.flickr.com/photos/65315936@N00/</a><br />
                Chris Smith</li>
                <li><a href="http://www.hdwallpapers.in/walls/mclaren_p1_in_forza_motorsport_5-HD.jpg">http://www.hdwallpapers.in/walls/mclaren_p1_in_forza_motorsport_5-HD.jpg</a><br />
                Unknown</li>
            </ul>
            <div class="clear"></div>
        </div>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Leaving everything else at its default setting, select **Save**.

#### Gantry To Top

The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it.

[demo]: assets/copyright.jpg