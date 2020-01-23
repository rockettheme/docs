---
title: Vermilion: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Vermilion Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Introduction
-----

The **Contact Us** example page demonstrates how you can create a beautiful contact page with the Vermilion theme. Here is some information to help you replicate this page as it appears in the demo.

Mainbody
-----

![Mainbody](page_contactus_2.png)

The **Contact Us** page is a common WordPress page. The page's content is blank. The contact form is loaded as the result of setting the **Template** in the **Page Attributes** section of the sidebar to **Contact Form**. This form is loaded from the `theme-contact.php` file located in the theme's directory.

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Widgets](page_contactus.png)

:   1. **Showcase - Text** [9%, 25%, se]
    2. **Mainbody** [18%, 5%, se]
    3. **Sidebar - Text** [18%, 66%, se]
    4. **Extension - Text** [68%, 35%, se]

1. [Showcase - Text](#showcase-section)
2. [Mainbody](#sidebar-section)
3. [Sidebar - Text](#sidebar-section)
4. [Extension - Text](#extension_section)

Showcase Section
-----

![Showcase](page_contactus_1.png)

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

Sidebar Section
-----

![Sidebar](assets/page_contactus_4.png)

Here is the widget breakdown for the Breadcrumbs section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><span class="rt-image"><img src="http://(your site url)/wp-content/rockettheme/rt_vermilion_wp/pages/contact-us/img-01.jpg" alt="image" /></span></p>

<p>Vermilion is only available as part of the Club Subscription.<span class="hidden-tablet"> Please use the RocketLauncher to install an equivalent of the demo onto your site.</span></p>

<h4>Address</h4>
<p>
    <span>Vermilion Theme, LLC</span><br />
    <span>123 WordPress Boulevard</span><br />
    <span>Seattle, WA 00000, USA</span>
</p>

<h4>Email</h4>
<p>
    <span>noreply@vermilion-theme.com</span><br />
    <span>noperson@vermilion-theme.com</span>
</p>

<h4>Phone</h4>
<p>
    <span>+1(123)456-5555-555</span><br />
    <span>+1(123)456-6666-666</span>
</p>

<h4>Online Support</h4>
<p>
    <span>Skype ID: vermilion.theme</span><br />
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

![Extension](assets/page_contactus_5.png)

Here is a breakdown of the widgets in the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Email Us for Questions Involving Payments, Billing, and Membership.</p>

<p><a href="http://www.rockettheme.com/forum/wordpress-theme-vermilion" class="readon">Send Email</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                               |
| :---------------- | :--------------------                 |
| Title             | `Got Billing and Payments Questions?` |
| Widget Variations | RT-Center                             |

Leaving everything else at its default setting, select **Save**.