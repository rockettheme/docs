---
title: Osmosis: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Osmosis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Content Top Section
-----

![][demo]

:   1. **Text 1** [8%, 7%, se]
    2. **Text 2** [65%, 7%, se]

Here is the widget breakdown for the Content Top section:

* Text
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="fp-content-top-animate">
    <div class="gantry-width-container">
        <div class="gantry-width-66">
            <div class="fp-content-top-image-block">
                <img class="fp-content-top-image-01" src="http://(Your Site URL)/wp-content/rockettheme/rt_osmosis_wp/home/fp-content-top/img-01.jpg" alt="image" />
                <div class="rt-top-content"><span class="readon">Alignment Options</span></div>
                <div class="rt-desc-overlay">
                    <div class="rt-bottom-content">
                        <h3 class="smallmarginbottom visible-desktop"><a href="#">Alignment Options</a></h3>
                        <p class="rt-text-small"><span>Osmosis benefits from a fluid alignment option<span class="visible-desktop">, focussing in the left hand side bar, as well as a centered/more fixed responsive option</span></span>.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <p class="rt-text-small largepaddingtop nomarginbottom">Sidepanel Position</p>
                <h2 class="title">Dynamically revealed<span class="hidden-tablet"> widgetized content</span></h2>
                <p class="hidden-tablet"><strong><span>Scroll to unveil the widgets in the sidepanel position<span class="visible-large">, situated to the side of the mainbody area</span></span>.</strong></p>
                <p class="rt-text-small"><span>Several sidepanel extra widgets are also available<span class="visible-large">, such as a logo and a horizontal dropdown menu</span></span>.</p>
                <a href="#" class="readon4">Read More</a>
            </div>
        </div>
    </div>
    <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-content-top-a1` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="gantry-width-container">
    <div class="gantry-width-25 box1">
        <div class="gantry-width-spacer">
            <p class="rt-text-small largepaddingtop medmarginbottom">Menu Systems</p>
            <h4 class="rt-text-white nomargintop">Dropdown Menu or SplitMenu</h4>
            <p class="rt-text-small">Choose between two configurable menus.</p>
        </div>
    </div>
    <div class="gantry-width-25 box2">
        <div class="gantry-width-spacer">
            <p class="rt-text-small largepaddingtop medmarginbottom">Integration</p>
            <h4 class="rt-text-white nomargintop">Selection of Styled Extensions</h4>
            <p class="rt-text-small">Styling for RokSprocket, RokAjaxSearch and others.</p>
        </div>
    </div>
    <div class="gantry-width-25 box3">
        <div class="gantry-width-spacer">
            <p class="rt-text-small largepaddingtop medmarginbottom">Gantry</p>
            <h4 class="rt-text-white nomargintop">A Powerful Core Framework</h4>
            <p class="rt-text-small">Standard array of features and capabilities.</p>
        </div>
    </div>
    <div class="gantry-width-25 box4">
        <div class="gantry-width-spacer">
            <p class="rt-text-small largepaddingtop medmarginbottom">Widget Variations</p>
            <h4 class="rt-text-white nomargintop">Individualize Modular Content</h4>
            <p class="rt-text-small">Diverse selection of stylistic widget variations.</p>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-content-top-a2` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/