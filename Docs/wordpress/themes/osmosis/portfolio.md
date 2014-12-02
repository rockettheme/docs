---
title: Osmosis: Recreating the Demo - Portfolio Page
description: Your Guide to Recreating Elements of the Osmosis Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Templates/osmosis:Osmosis

---

Introduction
-----

The **Portfolio** example page demonstrates how you can create a beautiful page with the Osmosis template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][portfoliopage9]

The **Portfolio** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-portfolio` in the **Page Suffix** field in the **Gizmos** page inside the **Osmosis** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Osmosis > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs].

Mainbody
-----

![][portfoliopage6]

The page's content body is set in the **Portfolio** page. You will find the content used in the page below.

~~~ .html
<h3>Our Awesome Project</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <span class="rt-image">
                <img src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-17.jpg" alt="image" />
            </span>
        </div>
    </div>

    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Project Description</h3>
            <p>Efficiently unleash cross-media information without cross-media value.<span class="hidden-tablet"> Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</span></p>
            <h3>Project Details</h3>
            <div class="gantry-row">
                <div class="gantry-width-30">
                    <div class="gantry-width-spacer">
                        <p class="smallmarginbottom">Customer:</p>
                        <p class="smallmarginbottom">Live Demo:</p>
                        <p class="smallmarginbottom">Published<span class="hidden-tablet"> Date</span>:</p>
                    </div>
                </div>
                <div class="gantry-width-70">
                    <div class="gantry-width-spacer">
                        <p class="smallmarginbottom">RocketTheme</p>
                        <p class="smallmarginbottom">http://www.rockettheme.com</p>
                        <p class="smallmarginbottom">08 March, 2014</p>
                    </div>
                </div>
            </div>
            <div class="clear"></div>
            <p class="largemargintop"><a href="http://www.rockettheme.com/wordpress-themes/osmosis" class="readon">Learn More</a></p>
        </div>
    </div>
</div>
</div>

<div class="clear"></div>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page.

![][portfoliopage]

:   1. **Header - Logo** [6%, 12%, se]
    2. **Header - Gantry Menu** [6%, 65%, se]
    3. **Top - Text** [12%, 45%, se]
    4. **Breadcrumbs - Gantry Breadcrumbs** [13%, 12%, se]
    5. **Main Top - RokSprocket** [18%, 12%, se]
    6. **Main Top - RokSprocket** [48%, 12%, se]
    7. **Mainbody** [58%, 12%, se]
    8. **Extension - Text** [75%, 12%, se]
    9. **Footer - Text** [86%, 12%, se]
    10. **Footer - Text** [86%, 52%, se]

1. [Header - Logo](portfolio.md#header-section)
2. [Header - Gantry Menu](portfolio.md#header-section)
3. [Top - Text](portfolio.md#top-section)
4. [Breadcrumbs - Gantry Breadcrumbs](portfolio.md#breadcrumbs-section)
5. [Main Top - RokSprocket](portfolio.md#main-top-section)
6. [Main Top - RokSprocket](portfolio.md#main-top-section)
7. [Mainbody](portfolio.md#mainbody)
8. [Extension - Text](portfolio.md#extension-section)
9. [Footer - Text](portfolio.md#footer-section)
10. [Footer - Text](portfolio.md#footer-section)

Header Section
-----

![][portfoliopage2]

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

![][portfoliopage3]

Here is the widget breakdown for the Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Portfolio[span class="rt-title-tag"]What We Have Already Done[/span]`.
* Switch the **Widget Variations** option to **RT-Center**.
* Enter `rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![][portfoliopage4]

Here is the widget breakdown for the Breadcrumbs section:

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Main Top
-----

![][portfoliopage5]

:   1. **RokSprocket (Mosaic)** [6%, 6%, se]
    2. **RokSprocket** [75%, 6%, se]

Here is a breakdown for the **Main Top** section:

#### RokSprocket (Mosaic)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Title** and **Description** fields of these items are custom, with custom images set, as well. Any tags set appear below the description on the frontend.

| Option      | Setting                                                |
| :---------- | :----------                                            |
| Title       | `Spectral`                                             |
| Description | `Objectively innovate empowered manufactured products` |
| Image       | Custom                                                 |
| Link        | Custom                                                 |
| Tags        | `logo, web`                                            |

Here is a look at the **Mosaic Layout Options** for this widget.

| Option          | Setting                      |
| :-------------- | :--------------------------- |
| Theme           | Default                      |
| Display Limit   | ∞                            |
| Columns         | 4                            |
| Preview Length  | ∞                            |
| Only Show Tags  |                              |
| Strip HTML Tags | No                           |
| Blocks Per View | 8                            |
| Article Details | Hide Author and Date         |
| Block Animation | Fade, Scale, Rotate          |
| Ordering        | Default, Title, Date, Random |
| Image Resize    | Disable                      |

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### RokSprocket (Strips)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | None        |
| Image       | None        |
| Link        | None        |

**Description**

~~~ .html
<p class="promo2">RokAjaxSearch is a configurable search widget that uses AJAX to load results in real time via a styled popup. It can be set to local or Google search, inclusive of Web, image, video and blog. Results are paged and can be accessed via buttons or keyboard commands.</p>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |
| :----------       | :----------  |
| Theme             | Default      |
| Display Limit     | ∞            |
| Preview Length    | ∞            |
| Strip HTML Tags   | No           |
| Previews Per Page | 1            |
| Items Per Row     | 1            |
| Arrow Navigation  | Hide         |
| Pagination        | Show         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Enter `What Our Clients Say` in the **Title** field.
* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Widget Variations** to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

Extension Section
-----

![][portfoliopage7]

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Will You be the Next to Join Our Happy Clients?</p>

<br />

<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <a href="http://www.rockettheme.com/wordpress-themes/hadron"><img class="rt-transparent-image" src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-18.png" alt="image" /></a>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <a href="http://www.rockettheme.com/wordpress-themes/acacia"><img class="rt-transparent-image" src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-19.png" alt="image" /></a>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <a href="http://www.rockettheme.com/wordpress-themes/corvus"><img class="rt-transparent-image" src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-20.png" alt="image" /></a>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <a href="http://www.rockettheme.com/wordpress-themes/spectral"><img class="rt-transparent-image" src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-21.png" alt="image" /></a>
        </div>
    </div>
    <div class="gantry-width-20">
        <div class="gantry-width-spacer">
            <a href="http://www.rockettheme.com/wordpress-themes/stratos"><img class="rt-transparent-image" src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/portfolio/img-22.png" alt="image" /></a>
        </div>
    </div>
</div>
</div>

<div class="clear"></div><br /><br />

<p><a href="http://www.rockettheme.com/wordpress-themes/osmosis" class="readon">Join Now</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Our Satisfied Clients`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][portfoliopage8]

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

[portfoliopage]: assets/page_portfolio.jpeg
[portfoliopage2]: assets/page_portfolio_2.jpeg
[portfoliopage3]: assets/page_portfolio_3.jpeg
[portfoliopage4]: assets/page_portfolio_4.jpeg
[portfoliopage5]: assets/page_portfolio_5.jpeg
[portfoliopage6]: assets/page_portfolio_6.jpeg
[portfoliopage7]: assets/page_portfolio_7.jpeg
[portfoliopage8]: assets/page_portfolio_8.jpeg
[portfoliopage9]: assets/page_portfolio_9.jpeg
[portfoliopage10]: assets/page_portfolio_10.jpeg
[portfoliopage11]: assets/page_portfolio_11.jpeg
[portfoliopage12]: assets/page_portfolio_12.jpeg
[portfoliopage13]: assets/page_portfolio_13.jpeg
[gantrydocs]: http://gantry-framework.org/documentation/wordpress/configure/
[roksprocket]: ../../plugins/roksprocket/
