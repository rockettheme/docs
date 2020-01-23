---
title: Audacity: Recreating the Demo - Pricing Tables Page
description: Your Guide to Recreating Elements of the Audacity Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/audacity:Audacity

---

Introduction
-----

The **Pricing Tables** example page demonstrates how you can create a beautiful page with the Audacity theme. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![Override](page_pricing_menu.jpeg)

The **Pricing Tables** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-pricing-tables` in the **Page Suffix** field in the **Gizmos** page inside the **Audacity** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Audacity > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation](http://docs.gantry.org/gantry4/configure).

Mainbody
-----

![Mainbody](page_pricing_4.jpeg)

The page's content body is set in the **Pricing Tables** page. You will find the content used in the page below.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Simple Plans and Pricing</h3>
            <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
            <p class="hidden-tablet">Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
            <p><a href="http://www.rockettheme.com/wordpress-themes/audacity" class="readon">Sign Up</a></p>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Top Audacity Features</h3>
            <ul>
                <li>Powered by Gantry Framework</li>
                <li>CSS Dropdown Menu and Split Menu</li>
                <li>Multiple Widget Variations</li>
            </ul>
            <p class="success">Want to use Audacity for your clients? <a href="http://www.rockettheme.com/wordpress-themes/audacity">Purchase Single Package Now</a>.</p>
        </div>
    </div>
</div>
</div>

<div class="clear"></div>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Page](page_pricing.jpeg)

:   1. **Showcase - Text** [10%, 45%, se]
    2. **Breadcrumbs** [14%, 12%, se]
    3. **Feature - Text** [19%, 12%, se]
    4. **Mainbody** [53%, 12%, se]
    5. **Extension - Text** [68%, 35%, se]
    6. **Footer - Text** [76%, 12%, se]
    7. **Footer - Text** [76%, 52%, se]

1. [Showcase - Text](pricing.md#showcase-section)
2. [Breadcrumbs](pricing.md#breadcrumbs-section)
3. [Mainbody](pricing.md#mainbody)
4. [Feature - Text](pricing.md#feature-section)
5. [Extension - Text](pricing.md#extension-section)
6. [Footer - Text](pricing.md#footer-section)
7. [Footer - Text](pricing.md#footer-section)

Showcase Section
-----

![Showcase](page_pricing_1.jpeg)

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                              Setting                              |
| :---------------- | :---------------------------------------------------------------- |
| Title             | `Pricing[span class="rt-title-tag"]Pick a Plan that Fits You[/span]` |
| Widget Variations | RT-Center, No Margin All                                          |
| Custom Variations | `rt-title-large rt-nomodulecontent rt-top-large-padding`          |

Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![Breadcrumbs](assets/page_pricing_2.jpeg)

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Feature Section
-----

![Feature](page_pricing_3.jpeg)

Here is a breakdown for the **Feature** section:

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
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/audacity">Sign Up</a></li>
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
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/audacity">Sign Up</a></li>
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
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/audacity">Sign Up</a></li>
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
        <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/audacity">Sign Up</a></li>
    </ul>
</div>
</div>

<div class="clear"></div>

<div class="gantry-width-spacer">
    <p>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/wordpress-themes/audacity">View Professional Plan</a>.</p>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                         |
| :---------------- | :------------------------------ |
| Title             | `Try it Out for 10 Days Free`   |
| Widget Variations | RT-Center, No Margin All        |

Leaving everything else at its default setting, select **Save**.

Extension Section
-----

![Extension](page_pricing_5.jpeg)

Here is a breakdown for the **Extension** section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>No Credit Card Required and No Long-Term Contracts</p>

<p><a href="http://www.rockettheme.com/wordpress-themes/audacity" class="readon">Sign Up</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                         Setting                          |
| :---------------- | :------------------------------------------------------- |
| Title             | `No Hidden Fee`                                          |
| Widget Variations | RT-Center                                                |

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

| Option            | Setting           |
| :---------------- | :---------------- |
| Title             | `Audacity Demo`   |
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