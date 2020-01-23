---
title: Plethora: Recreating the Demo - Pricing Tables Page
description: Your Guide to Recreating Elements of the Plethora Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Introduction
-----

The **Pricing Tables** example page demonstrates how you can create a beautiful page with the Plethora theme. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![][pricingpage2]

The **Pricing Tables** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-pricing-tables` in the **Page Suffix** field in the **Gizmos** page inside the **Plethora** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Plethora > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation][gantrydocs]

Mainbody
-----

![][pricingpage4]

The page's content body is set in the **Pricing Tables** page. You will find the content used in the page below.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Simple Plans and Pricing</h3>
            <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
            <p class="hidden-tablet">Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
            <p><a href="http://www.rockettheme.com/wordpress-themes/plethora" class="readon">Sign Up</a></p>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Top Plethora Features</h3>
            <ul>
                <li>Powered by Gantry Framework</li>
                <li>CSS Dropdown Menu and Split Menu</li>
                <li>Multiple Widget Variations</li>
            </ul>
            <p class="success">Want to use Plethora for your clients? <a href="http://www.rockettheme.com/wordpress-themes/plethora">Purchase Single Package Now</a>.</p>
        </div>
    </div>
</div>
</div>

<div class="clear"></div>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Top**][top], [**Header**][header], and [**Copyright**][copyright] positions are outlined in the main demo replication area of this guide.

![][pricingpage]

:   1. **Showcase - Text** [12%, 45%, se]
    2. **Mainbody** [20%, 11%, se]
    3. **Expanded Bottom - Text** [35%, 11%, se]
    4. **Extension - Text** [68%, 35%, se]
    5. **Footer - Text** [75%, 11%, se]
    6. **Footer - Text** [75%, 52%, se]

1. [Showcase - Text](pricing.md#showcase-section)
2. [Mainbody](pricing.md#mainbody)
3. [Expanded Bottom - Text](pricing.md#expanded-bottom-section)
4. [Extension - Text](pricing.md#extension-section)
5. [Footer - Text](pricing.md#footer-section)
6. [Footer - Text](pricing.md#footer-section)

Showcase Section
-----

![][pricingpage3]

Here is the widget breakdown for the Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Pricing[span class="rt-title-tag"]Pick a Plan that Fits You[/span]`.
* Switch the **Widget Variations** option to **Box 3, No Margin All, RT-Center**.
* Enter `rt-title-large rt-nomodulecontent` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Expanded Bottom Section
-----

![][pricingpage5]

Here is a breakdown for the **Expanded Bottom** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-width-spacer">
    <p class="nomarginbottom">All plans come with awesome support by email and phone. There is no hidden fee!</p>
</div>

<div class="gantry-width-container">
    <div class="gantry-width-25">
    <ul class="rt-table">
        <li class="rt-table-title">Basic</li>
        <li class="rt-table-price">$28</li>
        <li class="rt-table-description">Globally incubate standards compliant channels</li>
        <li class="rt-table-item">5GB Storage</li>
        <li class="rt-table-item">10 Users</li>
        <li class="rt-table-item">20 Emails</li>
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/plethora">Sign Up</a></li>
    </ul>
</div>

<div class="gantry-width-25">
    <ul class="rt-table">
        <li class="rt-table-title">Standard</li>
        <li class="rt-table-price">$58</li>
        <li class="rt-table-description">Globally incubate standards compliant channels</li>
        <li class="rt-table-item">25GB Storage</li>
        <li class="rt-table-item">20 Users</li>
        <li class="rt-table-item">30 Emails</li>
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/plethora">Sign Up</a></li>
    </ul>
</div>

<div class="gantry-width-25">
    <ul class="rt-table">
        <li class="rt-table-title">Titanium</li>
        <li class="rt-table-price">$88</li>
        <li class="rt-table-description">Globally incubate standards compliant channels</li>
        <li class="rt-table-item">50GB Storage</li>
        <li class="rt-table-item">30 Users</li>
        <li class="rt-table-item">40 Emails</li>
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/plethora">Sign Up</a></li>
    </ul>
</div>

<div class="gantry-width-25">
    <ul class="rt-table rt-table-last-col">
        <li class="rt-table-title">Platinum</li>
        <li class="rt-table-price">$288</li>
        <li class="rt-table-description">Globally incubate standards compliant channels</li>
        <li class="rt-table-item">500GB Storage</li>
        <li class="rt-table-item">100 Users</li>
        <li class="rt-table-item">200 Emails</li>
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/plethora">Sign Up</a></li>
    </ul>
</div>
</div>

<div class="clear"></div>

<div class="gantry-width-spacer">
    <p>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/wordpress-themes/plethora">View Professional Plan</a>.</p>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Try it Out for 10 Days Free` in the **Title** field.
* Select **RT-Center, No Padding Right, No Padding Left, No Margin Right, No Margin Left** in the **Widget Variations** setting.
* Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![][pricingpage6]

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>No Credit Card Required and No Long-Term Contracts</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/plethora" class="readon">Sign Up</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `No Hidden Fee`.
* Set the **Widget Variations** option to **RT-Center**.
* Leaving everything else at its default setting, select **Save**.

Footer Section
-----

![][pricingpage7]

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

[pricingpage]: assets/page_pricing.jpeg
[pricingpage2]: assets/page_pricing_2.jpeg
[pricingpage3]: assets/page_pricing_3.jpeg
[pricingpage4]: assets/page_pricing_4.jpeg
[pricingpage5]: assets/page_pricing_5.jpeg
[pricingpage6]: assets/page_pricing_6.jpeg
[pricingpage7]: assets/page_pricing_7.jpeg
[pricingpage8]: assets/page_pricing_8.jpeg
[pricingpage9]: assets/page_pricing_9.jpeg
[pricingpage10]: assets/page_pricing_10.jpeg
[pricingpage11]: assets/page_pricing_11.jpeg
[pricingpage12]: assets/page_pricing_12.jpeg
[pricingpage13]: assets/page_pricing_13.jpeg
[header]: demo_header.md
[top]: demo_top.md
[copyright]: demo_copyright.md
[gantrydocs]: http://docs.gantry.org/gantry4/configure
