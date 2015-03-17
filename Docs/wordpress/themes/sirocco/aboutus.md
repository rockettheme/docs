---
title: Sirocco: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Sirocco Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Templates/sirocco:Sirocco

---

Introduction
-----

The **About Us** example page demonstrates how you can create a beautiful page with the Sirocco template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![Override](page_aboutus_menu.jpeg)

The **About Us** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-about-us` in the **Page Suffix** field in the **Gizmos** page inside the **Sirocco** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Sirocco > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation](http://gantry-framework.org/documentation/wordpress/configure/).

You will also want to assign the override to the **About Us** page via the **Assignments** tab in the **Theme Settings**.

Mainbody
-----

![MainBody](page_aboutus_5.jpeg)

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Sirocco, the Powerful Theme</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/sirocco" class="readon">Learn More</a></p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Page](page_aboutus.jpeg)

:   1. **Showcase - Text** [9%, 45%, se]
    2. **Breadcrumbs** [17%, 13%, se]
    4. **Main Top - Text** [20%, 13%, se] 
    5. **Expanded Bottom - Text** [34%, 13%, se]
    6. **MainBody Content** [52%, 13%, se]
    6. **Extension - Text** [68%, 30%, se]
    7. **Bottom - Text** [76%, 13%, se]
    8. **Bottom - Text** [76%, 52%, se]

1. [Showcase - Text](aboutus.md#showcase-section)
2. [Breadcrumbs](aboutus.md#breadcrumbs-section)
2. [Main Top - Text](aboutus.md#main-top-section)
3. [MainBody Content](aboutus.md#mainbody)
4. [Expanded Bottom - Text](aboutus.md#main-bottom-section)
5. [Extension - Text](aboutus.md#extension-section)
6. [Bottom - Text](aboutus.md#footer-section)
7. [Bottom - Text](aboutus.md#footer-section)

Showcase Section
-----

![Showcase](assets/page_aboutus_1.jpeg)

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                                                           |
| :---------------- | :---------------------------------------------------------------- |
| Title             | `About Us[span class="rt-title-tag"]Welcome to Sirocco[/span]`    |
| Widget Variations | RT-Center, No Margin All                                          |
| Custom Variations | `rt-title-large rt-nomodulecontent rt-top-large-padding`          |

Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![Breadcrumbs](assets/page_aboutus_2.jpeg)

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Main Top Section
-----

![Main Top](assets/page_aboutus_3.jpeg)

Here is the widget breakdown for the Main Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img src="http://(Your Site URL)/wp-content/rockettheme/rt_sirocco_wp/pages/about-us/img-01.jpg" alt="image" /></span>
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

|       Option      |       Setting        |
| :---------------- | :------------------- |
| Widget Variations | Box 2, No Margin All |
| Custom Variations | `rt-title-center`    |

Leaving everything else at its default setting, select **Save**.

Expanded Bottom Section
-----

![Expanded Bottom](assets/page_aboutus_4.jpeg)

Here is a breakdown for the **Expanded Bottom** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://(Your Site URL)/wp-content/rockettheme/rt_sirocco_wp/pages/about-us/img-02.jpg" alt="image" /></span>
                <h4>Our Mission</h4>
                <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holisticly predominate extensible testing procedures for reliable supply chains.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://(Your Site URL)/wp-content/rockettheme/rt_sirocco_wp/pages/about-us/img-03.jpg" alt="image" /></span>
                <h4>Our Values</h4>
                <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="http://(Your Site URL)/wp-content/rockettheme/rt_sirocco_wp/pages/about-us/img-04.jpg" alt="image" /></span>
                <h4>Our Solution</h4>
                <p>Engage worldwide methodologies with web-enabled technology. Interactively coordinate proactive e-commerce via process-centric outside the box thinking.</p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

|       Option      |       Setting        |
| :---------------- | :------------------- |
| Widget Variations | Box 3, No Margin All |

Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![Extension](assets/page_aboutus_6.jpeg)

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Utilized with Versatile and Flexible Features Powered by the Gantry Framework.</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/sirocco" class="readon">Download Sirocco</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                Setting                 |
| :---------------- | :------------------------------------- |
| Title             | `We Always Try to Create a Difference` |
| Widget Variations | RT-Center                              |

Leaving everything else at its default setting, select **Save**.

Bottom Section
-----

![Bottom](assets/page_aboutus_7.jpeg)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

Here is a breakdown of the widgets in the **Bottom** section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Sirocco can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/sirocco">Sirocco RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |      Setting      |
| :---------------- | :---------------- |
| Title             | `Sirocco Demo` |
| Custom Variations | `rt-phone-center` |

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_sirocco_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Sirocco Theme, LLC</span><br />
            <span>123 WordPress Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |        Setting        |
| :---------------- | :-------------------- |
| Title             | `Sample Contact Info` |
| Custom Variations | `rt-phone-center`     |

Leaving everything else at its default setting, select **Save**.
