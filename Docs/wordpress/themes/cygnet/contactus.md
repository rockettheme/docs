---
title: Cygnet: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Cygnet Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Introduction
-----

The **Contact Us** example page demonstrates how you can create a beautiful contact page with the Cygnet template. Here is some information to help you replicate this page as it appears in the demo.

Mainbody
-----

![Mainbody](page_contactus_5.png)

The **Contact Us** page is . The first post is the **Powered by Gantry Framework** article. The page's content is blank. The contact form is loaded as the result of setting the **Template** in the **Page Attributes** section of the sidebar to **Contact Form**. This form is loaded from the `template-contact.php` file located in the theme's directory.

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Widgets](page_contactus.jpeg)

:   1. **Showcase - Text** [11%, 45%, se]
    2. **Breadcrumbs** [19%, 10%, se]
    3. **Mainbody** [23%, 10%, se]
    4. **Sidebar - Text** [23%, 66%, se]
    5. **Extension - Text** [64%, 35%, se]
    6. **Footer - Text** [74%, 10%, se]
    7. **Footer - Text** [74%, 50%, se]

1. [Showcase - Text](blog.md#showcase-section)
2. [Breadcrumbs](blog.md#breadcrumbs-section)
3. [Mainbody](blog.md#sidebar-section)
4. [Sidebar - Text](blog.md#sidebar-section)
5. [Sidebar - Gantry Login Form](blog.md#sidebar-section)
6. [Extension - Text](blog.md#extension_section)
7. [Footer - Text](blog.md#footer-section)

Showcase Section
-----

![Showcase](page_contactus_1.jpeg)

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                                                                      |
| :---------------- | :-----------------------------------------------------------                 |
| Title             | `Contact Us[span class="rt-title-tag"]We Would Love to Hear From You[/span]` |
| Widget Variations | RT-Center, No Margin All                                                     |
| Custom Variations | `rt-title-large rt-nomodulecontent rt-top-large-padding`                     |

Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![Breadcrumbs](assets/page_contactus_2.jpeg)

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Sidebar Section
-----

![Sidebar](assets/page_contactus_3.jpeg)

Here is the widget breakdown for the Breadcrumbs section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><span class="rt-image"><img src="http://(your site url)/wp-content/rockettheme/rt_cygnet_wp/pages/contact-us/img-01.jpg" alt="image" /></span></p>

<p>Cygnet is only available as part of the Club Subscription.<span class="hidden-tablet"> Please use the RocketLauncher to install an equivalent of the demo onto your site.</span></p>

<h4>Address</h4>
<p>
    <span>Cygnet Theme, LLC</span><br />
    <span>123 WordPress Boulevard</span><br />
    <span>Seattle, WA 00000, USA</span>
</p>

<h4>Email</h4>
<p>
    <span>noreply@cygnet-theme.com</span><br />
    <span>noperson@cygnet-theme.com</span>
</p>

<h4>Phone</h4>
<p>
    <span>+1(123)456-5555-555</span><br />
    <span>+1(123)456-6666-666</span>
</p>

<h4>Online Support</h4>
<p>
    <span>Skype ID: cygnet.theme</span><br />
    <span>BBM PIN: 12ABC345</span>
</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting        |
| :---------------- | :---------     |
| Widget Variations | Box 1, Title 3 |

Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![Extension](assets/page_contactus_4.jpeg)

Here is a breakdown of the widgets in the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Email Us for Questions Involving Payments, Billing, and Membership.</p>

<p><a href="http://www.rockettheme.com/forum/wordpress-theme-cygnet" class="readon">Send Email</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                               |
| :---------------- | :--------------------                 |
| Title             | `Got Billing and Payments Questions?` |
| Widget Variations | Box 4, RT-Center, No Margin All       |

Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![Footer](assets/page_aboutus_7.png)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

Here is a breakdown of the widgets in the **Footer** section:

* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Cygnet can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/cygnet">Cygnet RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |      Setting      |
| :---------------- | :---------------- |
| Title             | `Cygnet Demo` |
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
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_cygnet_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Cygnet Theme, LLC</span><br />
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