---
title: Plethora: Recreating the Demo - The Team Page
description: Your Guide to Recreating Elements of the Plethora Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Templates/plethora:Plethora

---

Introduction
-----

The **The Team** example page demonstrates how you can create a beautiful page with the Plethora template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][theteampage2]

The **The Team** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-the-team` in the **Page Suffix** field in the **Gizmos** page inside the **Plethora** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Plethora > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs]

Mainbody
-----

![][theteampage4]

The page's content body is set in the **The Team** article. You will find the content used in the article below.

~~~ .html
<h3>Our Passion for Design</h3>

<p>Interactively procrastinate high-payoff content without backward-compatible data. Quickly cultivate optimal processes and tactical architectures. Completely iterate covalent strategic theme areas via accurate e-markets.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/plethora" class="readon">Learn More</a></p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Top**][top], [**Header**][header], and [**Copyright**][copyright] positions are outlined in the main demo replication area of this guide.

![][theteampage]

:   1. **Showcase - Text** [10%, 45%, se]
    2. **Mainbody** [14%, 15%, se]
    3. **Main Bottom - Text** [25%, 15%, se]
    4. **Main Bottom - Text** [51%, 15%, se]
    5. **Main Bottom - Text** [65%, 15%, se]
    6. **Extension - Text** [77%, 35%, se]
    7. **Footer - Text** [82%, 15%, se]
    8. **Footer - Text** [82%, 52%, se]

1. [Showcase - Text](theteam.md#top-section)
2. [Mainbody](theteam.md#mainbody)
3. [Main Bottom - Text](theteam.md#main-bottom-section)
4. [Main Bottom - Text](theteam.md#main-bottom-section)
5. [Main Bottom - Text](theteam.md#main-bottom-section)
6. [Extension - Text](theteam.md#extension-section)
7. [Footer - Text](theteam.md#footer-section)
8. [Footer - Text](theteam.md#footer-section)

Showcase Section
-----

![][theteampage3]

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `The Team[span class="rt-title-tag"]Meet the People Behind Plethora[/span]`.
* Switch the **Widget Variations** option to **Box 3, RT-Center, No Margin All**.
* Enter `rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Main Bottom Section
-----

![][theteampage13]

:   1. **Text 1** [7%, 7%, se]
    2. **Text 2** [50%, 7%, se]
    3. **Text 3** [75%, 7%, se]

Here is a breakdown for the **Main Bottom** section:

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-01.jpg" alt="image" /></span>
            </div>
        </div>
        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Robert Smith</h3>
                <h6 class="nomargintop">CEO of Plethora</h6>
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
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-03.jpg" alt="image" /></span>
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
                <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-02.jpg" alt="image" /></span>
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
* Enter `rt-title-center rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-04.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">by JohnONolan</a></span>
            </span>
            <h3 class="nomarginbottom">Enrik Prifti</h3>
            <h6 class="nomargintop">Programmer</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-05.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">by Thomas Leuthard</a></span>
            </span>
            <h3 class="nomarginbottom">Laura Richards</h3>
            <h6 class="nomargintop">Designer</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-06.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">by Daniele Zedda</a></span>
            </span>
            <h3 class="nomarginbottom">Alex Ward</h3>
            <h6 class="nomargintop">Technical Lead</h6>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-07.jpg" alt="image" />
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
* Set the **Widget Variations** option to **Box 4, RT-Center, No Margin All**.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-08.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">John Jensen</h3>
            <h6 class="nomargintop">Email</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-09.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Tessa Page</h3>
            <h6 class="nomargintop">Ticket</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-10.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Eric Timofti</h3>
            <h6 class="nomargintop">Chat</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-11.jpg" alt="image" />
                <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">by carianoff</a></span>
            </span>
            <h3 class="nomarginbottom">Lydia Back</h3>
            <h6 class="nomargintop">Facebook</h6>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <span class="rt-image with-attribution">
                <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/the-team/img-12.jpg" alt="image" />
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
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![][theteampage9]

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Join Our Awesome Team with a Great Work Environment</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/plethora" class="readon">Join Plethora</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `We are Hiring`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][theteampage10]

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Plethora can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/plethora">Plethora RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Plethora Demo`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Plethora Theme, LLC</span><br />
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

[theteampage]: assets/page_theteam.jpeg
[theteampage2]: assets/page_theteam_2.jpeg
[theteampage3]: assets/page_theteam_3.jpeg
[theteampage4]: assets/page_theteam_4.jpeg
[theteampage5]: assets/page_theteam_5.jpeg
[theteampage6]: assets/page_theteam_6.jpeg
[theteampage7]: assets/page_theteam_7.jpeg
[theteampage8]: assets/page_theteam_8.jpeg
[theteampage9]: assets/page_theteam_9.jpeg
[theteampage10]: assets/page_theteam_10.jpeg
[theteampage11]: assets/page_theteam_11.jpeg
[theteampage12]: assets/page_theteam_12.jpeg
[theteampage13]: assets/page_theteam_13.jpg
[header]: demo_header.md
[top]: demo_top.md
[copyright]: demo_copyright.md
[gantrydocs]: http://gantry-framework.org/documentation/wordpress/configure/
