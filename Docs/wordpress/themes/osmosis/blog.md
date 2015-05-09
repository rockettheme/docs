---
title: Osmosis: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Osmosis Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Introduction
-----

The **Blog** example page demonstrates how you can create a beautiful page with the Osmosis template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][blogpage14]

The **Blog** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-blog` in the **Page Suffix** field in the **Gizmos** page inside the **Osmosis** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Osmosis > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs]

Mainbody
-----

![][blogpage4]

The page's content body is set to display posts in the **Blog** category. The first post is the **Powered by Gantry Framework** article. You will find the content used in the post below.

~~~ .html
<p><span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/osmosis/wp-content/rockettheme/rt_osmosis_wp/pages/blog/img-01.jpg" alt="image" /></span></p>

<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page.

![][blogpage]

:   1. **Header - Logo** [6%, 15%, se]
    2. **Header - Gantry Menu** [6%, 65%, se]
    3. **Top - Text** [9%, 45%, se]
    4. **Breadcrumbs - Gantry Breadcrumbs** [12%, 15%, se]
    5. **Sidebar - RokAjaxSearch** [15%, 13%, se]
    6. **Sidebar - Gantry Menu** [19%, 13%, se]
    7. **Sidebar - Gantry Login Form** [55%, 13%, se]
    8. **Extension - Text** [81%, 44%, se]
    9. **Footer - Text** [87%, 15%, se]
    10. **Footer - Text** [87%, 50%, se]
    11. **Blog** [15%, 55%, sw]

1. [Header - Logo](blog.md#header-section)
2. [Header - Gantry Menu](blog.md#header-section)
3. [Top - Text](blog.md#top-section)
4. [Breadcrumbs - Gantry Breadcrumbs](blog.md#breadcrumbs-section)
5. [Sidebar - RokAjaxSearch](blog.md#sidebar-section)
6. [Sidebar - Gantry Menu](blog.md#sidebar-section)
7. [Sidebar - Gantry Login Form](blog.md#sidebar-section)
8. [Extension - Text](blog.md#extension-section)
9. [Footer - Text](blog.md#footer-section)
10. [Footer - Text](blog.md#footer-section)
11. [Blog](blog.md#mainbody)

Header Section
-----

![][blogpage2]

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

![][blogpage3]

Here is the widget breakdown for the Header section:


#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Blog[span class="rt-title-tag"]Read the Latest News[/span]`.
* Enter `rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![][blogpage13]

Here is the widget breakdown for the Breadcrumbs section:

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Sidebar Section
-----

![][blogpage12]

:   1. **RokAjaxSearch** [6%, 18%, se]
    2. **Gantry Menu** [15%, 18%, se]
    3. **Gantry Login Form** [83%, 18%, se]

Here is the widget breakdown for the Breadcrumbs section:

* RokAjaxSearch
* Gantry Menu
* Gantry Login Form

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `Search the Blog` in the **Title** field.
* Set the **Widget Variations** to **Box 2, Title 2**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting        |
| :----------       | :----------    |
| Title             | `Site Menu`    |
| Menu              | Main Menu      |
| Menu Theme        | Split-Menu     |
| SplitMenu Style   | Sidebar Menu   |
| Limit Levels      | Yes            |
| Start Level       | 0              |
| End Level         | 1              |
| Show All Children | Yes            |
| Show Empty Menu   | No             |
| Maximum Depth     | 10             |
| Widget Variations | Box 3, Title 3 |

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting        |
| :----------       | :----------    |
| Title             | `Login Form`   |
| User Greeting     | `Hi,`          |
| Pre-text          | Blank          |
| Post-text         | Blank          |
| Widget Variations | Box 4, Title 4 |

Extension Section
-----

![][blogpage8]

Here is the widget breakdown for the Breadcrumbs section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-60 gantry-block-center">
        <div class="gantry-width-spacer">
            <p><span>Get Updates, Upcoming Themes Info, and Our Great Deals!</span></p>
            <form class="rt-blog-form largemargintop largepaddingtop" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
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

* Set the **Title** to `Join Our Newsletter`.
* Switch the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][blogpage9]

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

[blogpage]: assets/page_blog.jpeg
[blogpage2]: assets/page_blog_2.jpeg
[blogpage3]: assets/page_blog_3.jpeg
[blogpage4]: assets/page_blog_4.jpeg
[blogpage5]: assets/page_blog_5.jpeg
[blogpage6]: assets/page_blog_6.jpeg
[blogpage7]: assets/page_blog_7.jpeg
[blogpage8]: assets/page_blog_8.jpeg
[blogpage9]: assets/page_blog_9.jpeg
[blogpage10]: assets/page_blog_10.jpeg
[blogpage11]: assets/page_blog_11.jpeg
[blogpage12]: assets/page_blog_12.jpeg
[blogpage13]: assets/page_blog_13.jpeg
[blogpage14]: assets/page_blog_14.jpg
[gantrydocs]: http://docs.gantry.org/gantry4/configure
