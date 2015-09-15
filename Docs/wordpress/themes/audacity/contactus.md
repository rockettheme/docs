---
title: Audacity: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Audacity Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/audacity:Audacity

---

Introduction
-----

The **Contact Us** example page demonstrates how you can create a beautiful contact page with the Audacity template. Here is some information to help you replicate this page as it appears in the demo.

Mainbody
-----

![Mainbody](page_contactus_3.jpeg)

The contact page's content is blank. The contact form is loaded as the result of setting the **Template** in the **Page Attributes** section of the sidebar to **Contact Form**. This form is loaded from the `template-contact.php` file located in the theme's directory.

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Widgets](page_contactus.jpeg)

:   1. **Showcase - Text** [9%, 45%, se]
    2. **Breadcrumbs** [14%, 10%, se]
    3. **Mainbody** [18%, 10%, se]
    4. **Sidebar - Text** [18%, 66%, se]
    5. **Extension - Text** [66%, 35%, se]
    6. **Footer - Text** [76%, 10%, se]
    7. **Footer - Text** [76%, 50%, se]

1. [Showcase - Text](#showcase-section)
2. [Breadcrumbs](#breadcrumbs-section)
3. [Mainbody](#sidebar-section)
4. [Sidebar - Text](#sidebar-section)
5. [Sidebar - Gantry Login Form](#sidebar-section)
6. [Extension - Text](#extension_section)
7. [Footer - Text](#footer-section)

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

![Sidebar](assets/page_contactus_4.jpeg)

Here is the widget breakdown for the Breadcrumbs section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><span class="rt-image"><img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/pages/contact-us/img-01.jpg" alt="image" /></span></p>

<p>Audacity is only available as part of the Club Subscription.<span class="hidden-tablet"> Please use the RocketLauncher to install an equivalent of the demo onto your site.</span></p>

<h4>Address</h4>
<p>
    <span>Audacity Theme, LLC</span><br />
    <span>123 WordPress Boulevard</span><br />
    <span>Seattle, WA 00000, USA</span>
</p>

<h4>Email</h4>
<p>
    <span>noreply@audacity-theme.com</span><br />
    <span>noperson@audacity-theme.com</span>
</p>

<h4>Phone</h4>
<p>
    <span>+1(123)456-5555-555</span><br />
    <span>+1(123)456-6666-666</span>
</p>

<h4>Online Support</h4>
<p>
    <span>Skype ID: audacity.theme</span><br />
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

![Extension](assets/page_contactus_5.jpeg)

Here is a breakdown of the widgets in the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Email Us for Questions Involving Payments, Billing, and Membership.</p>

<p><a href="http://www.rockettheme.com/forum/wordpress-theme-audacity" class="readon">Send Email</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                               |
| :---------------- | :--------------------                 |
| Title             | `Got Billing and Payments Questions?` |
| Widget Variations | RT-Center                             |

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
<p class="hidden-phone">These examples are intended to show how Audacity can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/audacity">Audacity RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |      Setting      |
| :---------------- | :---------------- |
| Title             | `Audacity Demo` |
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
            <img src="http://(Your Site URL)/wp-content/rockettheme/rt_audacity_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Audacity Theme, LLC</span><br />
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