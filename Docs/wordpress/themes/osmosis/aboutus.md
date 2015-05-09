---
title: Osmosis: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Osmosis Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Templates/osmosis:Osmosis

---

Introduction
-----

The **About Us** example page demonstrates how you can create a beautiful page with the Osmosis template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][aboutuspage2]

The **About Us** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-about-us` in the **Page Suffix** field in the **Gizmos** page inside the **Osmosis** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Osmosis > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs]

Mainbody
-----

![][aboutuspage8]

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Osmosis, the Powerful Theme</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/osmosis" class="readon">Learn More</a></p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page.

![][aboutuspage]

:   1. **Header - Logo** [6%, 8%, se]
    2. **Header - Gantry Menu** [6%, 65%, se]
    3. **Top - Text** [12%, 45%, se]
    4. **Breadcrumbs - Gantry Breadcrumbs** [18%, 9%, se]
    5. **Main Top - Text** [22%, 9%, se]
    6. **MainBody Content** [37%, 9%, se]
    7. **Main Bottom - Text** [50%, 9%, se]
    8. **Extension - Text** [72%, 35%, se]
    9. **Footer - Text** [80%, 9%, se]
    10. **Footer - Text** [80%, 52%, se]

1. [Header - Logo](aboutus.md#header-section)
2. [Header - Gantry Menu](aboutus.md#header-section)
3. [Top - Text](aboutus.md#top-section)
4. [Breadcrumbs - Gantry Breadcrumbs](aboutus.md#breadcrumbs-section)
5. [Main Top - Text](aboutus.md#main-top-section)
6. [MainBody Content](aboutus.md#mainbody)
7. [Main Bottom - Text](aboutus.md#main-bottom-section)
8. [Extension - Text](aboutus.md#extension-section)
9. [Footer - Text](aboutus.md#footer-section)
10. [Footer - Text](aboutus.md#footer-section)

Header Section
-----

![][aboutuspage4]

:   1. **Gantry Logo** [30%, 6%, se]
    2. **Gantry Menu** [30%, 65%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting      |  
| :---------------- | :----------- |  
| Menu              | Main Menu    |  
| Menu Theme        | Dropdown     |  
| SplitMenu Style   | Sidebar Menu |  
| Limit Levels      | No           |  
| Start Level       | 0            |  
| End Level         | 0            |  
| Show All Children | Yes          |  
| Show Empty Menu   | No           |  
| Maximum Depth     | 10           |  
| Custom Chrome     | Menu         |  

Top Section
-----

![][aboutuspage5]

Here is the widget breakdown for the Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About Us[span class="rt-title-tag"]Welcome to Osmosis[/span]`.
* Switch the **Widget Variations** option to **RT-Center**.
* Enter `rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![][aboutuspage6]

Here is the widget breakdown for the Breadcrumbs section:

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Main Top Section
-----

![][aboutuspage7]

Here is the widget breakdown for the Main Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/about-us/img-01.jpg" alt="image" /></span>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Introduction</h3>
            <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</p>
            <div class="hidden-tablet">
                <h3>More About Us</h3>
                <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing. Holistically pontificate installed base portals after maintainable products.</p>
            </div>
        </div>
    </div>
</div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About Us: Introduction - Mission Statement`.
* Enter `rt-title-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Main Bottom Section
-----

![][aboutuspage9]

Here is a breakdown for the **Main Bottom** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-02.jpg" alt="image" /></span>
            <h4>Our Mission</h4>
            <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holisticly predominate extensible testing procedures for reliable supply chains.</p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-03.jpg" alt="image" /></span>
            <h4>Our Values</h4>
            <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration.</p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-04.jpg" alt="image" /></span>
            <h4>Our Solution</h4>
            <p>Engage worldwide methodologies with web-enabled technology. Interactively coordinate proactive e-commerce via process-centric outside the box thinking.</p>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About Us: Our Mission - Our Values - Our Solution`.
* Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![][aboutuspage10]

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Utilized with Versatile and Flexible Features Powered by the Gantry Framework.</p>
<p><a href="http://www.rockettheme.com/joomla/templates/osmosis" class="readon largemargintop">Download Osmosis</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `We Always Try to Create a Difference`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][aboutuspage11]

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Osmosis can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/osmosis">Osmosis RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Osmosis Demo`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Osmosis Theme, LLC</span><br />
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

[aboutuspage]: assets/page_aboutus.jpeg
[aboutuspage2]: assets/page_aboutus_2.jpeg
[aboutuspage3]: assets/page_aboutus_3.jpeg
[aboutuspage4]: assets/demo_1.jpeg
[aboutuspage5]: assets/page_aboutus_5.jpeg
[aboutuspage6]: assets/page_aboutus_6.jpeg
[aboutuspage7]: assets/page_aboutus_7.jpeg
[aboutuspage8]: assets/page_aboutus_8.jpeg
[aboutuspage9]: assets/page_aboutus_9.jpeg
[aboutuspage10]: assets/page_aboutus_10.jpeg
[aboutuspage11]: assets/page_aboutus_11.jpeg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
