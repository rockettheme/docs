---
title: Myriad: Recreating the Demo - The Team Page
description: Your Guide to Recreating Elements of the Myriad Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Introduction
-----

The **The Team** example page demonstrates how you can create a beautiful page with the Myriad theme. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![Override](page_theteam_menu.jpeg)

The **The Team** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-the-team` in the **Page Suffix** field in the **Gizmos** page inside the **Myriad** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Myriad > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation](http://docs.gantry.org/gantry4/configure).

Mainbody
-----

![Mainbody](page_theteam_5.jpeg)

The page's content body is set in the **The Team** post. You will find the content used in the post below.

~~~ .html
<h3>Our Passion for Design</h3>

<p>Interactively procrastinate high-payoff content without backward-compatible data. Quickly cultivate optimal processes and tactical architectures. Completely iterate covalent strategic theme areas via accurate e-markets.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/myriad" class="readon">Learn More</a></p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Page](page_theteam.jpeg)

:   1. **Showcase - Text** [10%, 45%, se]
    2. **Breadcrumbs** [12%, 15%, se]
    3. **Main Top - Text** [26%, 15%, se]
    4. **Expanded Top - Text** [50%, 15%, se]
    5. **Mainbody** [15%, 15%, se]
    6. **Main Bottom - Text** [63%, 15%, se]
    7. **Extension - Text** [75%, 35%, se]
    8. **Bottom - Text** [82%, 15%, se]
    9. **Bottom - Text** [82%, 52%, se]

1. [Showcase - Text](theteam.md#showcase-section)
2. [Breadcrumbs](theteam.md#breadcrumbs-section)
3. [Main Top - Text](theteam.md#main-top-section)
4. [Expanded Top - Text](theteam.md#expanded-top-section)
5. [Mainbody](theteam.md#mainbody)
6. [Main Bottom - Text](theteam.md#main-bottom-section)
7. [Extension - Text](theteam.md#extension-section)
8. [Bottom - Text](theteam.md#bottom-section)
9. [Bottom - Text](theteam.md#bottom-section)

Showcase Section
-----

![Showcase](page_theteam_1.jpeg)

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `The Team[span class="rt-title-tag"]Meet the People Behind Myriad[/span]`.
* Switch the **Widget Variations** option to **RT-Center, No Margin All**.
* Enter `rt-title-large rt-nomodulecontent rt-top-large-padding` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![Breadcrumbs](assets/page_theteam_2.jpeg)

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Main Top Section
-----

![Main Top](page_theteam_3.jpeg)

Here is a breakdown for the **Main Top** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-04.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">by JohnONolan</a></span>
            </span>
            <h3 class="nomarginbottom">Enrik Prifti</h3>
            <h6 class="nomargintop">Programmer</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-05.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">by Thomas Leuthard</a></span>
            </span>
            <h3 class="nomarginbottom">Laura Richards</h3>
            <h6 class="nomargintop">Designer</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-06.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">by Daniele Zedda</a></span>
            </span>
            <h3 class="nomarginbottom">Alex Ward</h3>
            <h6 class="nomargintop">Technical Lead</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-07.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/mr-h/4217144639/sizes/l/">by AllansBrain</a></span>
            </span>
            <h3 class="nomarginbottom">Nora Mirone</h3>
            <h6 class="nomargintop">QA Lead</h6>
        </div>
    </div>
</div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Core Developers`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Expanded Top Section
-----

![Expanded Top](page_theteam_4.jpeg)

Here is a breakdown for the **Expanded Top** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-01.jpg" alt="image" /></span>
            </div>
        </div>
        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Robert Smith</h3>
                <h6 class="nomargintop">CEO of Myriad</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/astragony/8260117875/sizes/l/">AMaze by Daniele Zedda.</a></p>
            </div>
        </div>
    </div>
</div>
<div class="clear"></div><br />
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-03.jpg" alt="image" /></span>
            </div>
        </div>
        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Tayla Parker</h3>
                <h6 class="nomargintop">Accountant</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/johnonolan/5729506059/sizes/l/">Stare by JohnONolan.</a></p>
            </div>
        </div>
    </div>
</div>
<div class="clear"></div><br />
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-02.jpg" alt="image" /></span>
            </div>
        </div>
        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Paul Valdez</h3>
                <h6 class="nomargintop">Administrator</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/astragony/4728211246/sizes/l/">Bamboo by Daniele Zedda.</a></p>
            </div>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Management Team`.
* Set the **Widget Variations** to **Box 2, No Margin Top, No Margin Bottom**.
* Enter `rt-title-center rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Main Bottom
-----

![Main Bottom](page_theteam_6.jpeg)

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-08.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">John Jensen</h3>
            <h6 class="nomargintop">Email</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-09.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Tessa Page</h3>
            <h6 class="nomargintop">Ticket</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-10.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Eric Timofti</h3>
            <h6 class="nomargintop">Chat</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-11.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Lydia Back</h3>
            <h6 class="nomargintop">Facebook</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/the-team/img-12.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5327739397/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Luca Coyle</h3>
            <h6 class="nomargintop">Twitter</h6>
        </div>
    </div>
</div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Support Assistants`.
* Set the **Widget Variations** option to **Box 3, RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![Showcase](page_theteam_7.jpeg)

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Join Our Awesome Team with a Great Work Environment</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/myriad" class="readon">Join Myriad</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `We are Hiring`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Bottom Section
-----

![Bottom](assets/page_aboutus_7.jpeg)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Myriad can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/myriad">Myriad RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Myriad Demo`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Myriad Theme, LLC</span><br />
            <span>123 WordPress Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Sample Contact Info`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
