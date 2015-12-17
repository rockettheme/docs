---
title: Cygnet: Recreating the Demo - Pricing Tables Page
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

Introduction
-----

The **Pricing Tables** example page demonstrates how you can create a beautiful page with the Cygnet template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![](assets/page_pricing.jpeg)

:   1. **Custom HTML - Pricing** [12%, 45%, se]
    2. **Breadcrumbs** [18%, 12%, se]
    3. **Custom HTML - Try it Out for 10 Days Free** [21%, 12%, se]
    4. **Article Content** [52%, 12%, se]
    5. **Custom HTML - No Hidden Fee** [67%, 40%, se]
    6. **Custom HTML - Cygnet Demo** [76%, 12%, se]
    7. **Custom HTML - Sample Contact Info** [76%, 52%, se]


1. [Custom HTML - Pricing](pricing.md#custom-html---pricing)
2. [Breadcrumbs](pricing.md#breadcrumbs)
3. [Custom HTML - Try it Out for 10 Days Free](pricing.md#custom-html---try-it-out-for-10-days-free)
4. [Article Content](pricing.md#mainbody)
5. [Custom HTML - No Hidden Fee](pricing.md#custom-html---no-hidden-fee)
6. [Custom HTML - Cygnet Demo](pricing.md#custom-html---cygnet-demo)
7. [Custom HTML - Sample Contact Info](pricing.md#custom-html---sample-contact-info)

### Custom HTML - Pricing

![](assets/page_pricing_1.jpeg)

#### Module

|   Option   |                               Setting                                |
| :--------- | :------------------------------------------------------------------- |
| Title      | `Pricing[span class="rt-title-tag"]Pick a Plan that Fits You[/span]` |
| Show Title | Show                                                                 |
| Position   | showcase-a                                                           |
| Status     | Published                                                            |
| Access     | Public                                                               |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Content

~~~ .html
&nbsp;
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |                                    Setting                                     |
| :------------------ | :----------------------------------------------------------------------------- |
| Module Class Suffix | `rt-top-large-padding nomarginall rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![](assets/page_pricing_2.jpeg)

#### Module

|        Option       |    Setting    |
| :------------------ | :------------ |
| Title               | `Breadcrumbs` |
| Show You Are Here   | No            |
| Show Home           | Yes           |
| Text for Home Entry |               |
| Show Last           | Yes           |
| Text Separator      |               |
| Show Title          | Hide          |
| Position            | breadcrumb    |
| Status              | Published     |
| Access              | Public        |

##### Advanced

|        Option       |    Setting     |
| :------------------ | :------------- |
| Module Class Suffix | `hidden-phone` |

### Custom HTML - Try it Out for 10 Days Free

![](assets/page_pricing_3.jpeg)

#### Module

|   Option   |            Setting            |
| :--------- | :---------------------------- |
| Title      | `Try it Out for 10 Days Free` |
| Show Title | Show                          |
| Position   | feature-a                     |
| Status     | Published                     |
| Access     | Public                        |

#### Content

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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/cygnet">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/cygnet">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/cygnet">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/cygnet">Sign Up</a></li>
        </ul>
    </div>
</div>

<div class="clear"></div>

<div class="gantry-width-spacer">
    <p>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/joomla/templates/cygnet">View Professional Plan</a>.</p>
</div>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |   Setting   |
| :------------------ | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - No Hidden Fee

![](assets/page_pricing_5.jpeg)

#### Module

|   Option   |     Setting     |
| :--------- | :-------------- |
| Title      | `No Hidden Fee` |
| Show Title | Hide            |
| Position   | extension-a     |
| Status     | Published       |
| Access     | Public          |

#### Content

~~~ .html
<p>No Credit Card Required and No Long-Term Contracts</p>
<p><a href="http://www.rockettheme.com/joomla/templates/cygnet" class="readon largemargintop">Sign Up</a></p>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

| Option              | Setting                        |
| :------------------ | :----------                    |
| Module Class Suffix | `box4, rt-center, nomarginall` |

### Custom HTML - Cygnet Demo

![](assets/page_aboutus_7.jpeg)

#### Module

|   Option   |     Setting     |
| :--------- | :-------------- |
| Title      | `Cygnet Demo` |
| Show Title | Yes             |
| Position   | footer-a        |
| Status     | Published       |
| Access     | Public          |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Cygnet can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/cygnet">Cygnet RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |      Setting      |
| :------------------ | :---------------- |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![](assets/page_aboutus_8.jpeg)

#### Module

|   Option   |        Setting        |
| :--------- | :-------------------- |
| Title      | `Sample Contact Info` |
| Show Title | Yes                   |
| Position   | footer-b              |
| Status     | Published             |
| Access     | Public                |

#### Content

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
	<div class="gantry-width-40">
		<div class="gantry-width-spacer">
			<img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
		</div>
	</div>

	<div class="gantry-width-60">
		<div class="gantry-width-spacer">
			<span class="rt-intro-text">+1(123)456-5555-555</span><br />
			<span>Cygnet Theme, LLC</span><br />
			<span>123 Joomla! Boulevard</span><br />
			<span>Seattle, WA 00000, USA</span><br />
			<span><a href="#">noreply@domain.com</a></span>
		</div>
	</div>
</div>
<div class="clear"></div>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

|        Option       |      Setting      |
| :------------------ | :---------------- |
| Module Class Suffix | `rt-phone-center` |

Mainbody
-----

![](assets/page_pricing_4.jpeg)

The page's content body is set in the **Pricing Tables** article. You will find the content used in the article below.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Simple Plans and Pricing</h3>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
                <p class="hidden-tablet">Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
                <p><a href="http://www.rockettheme.com/joomla/templates/cygnet" class="readon">Sign Up</a></p>
            </div>
        </div>
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Top Cygnet Features</h3>
                <ul>
                    <li>Powered by Gantry Framework</li>
                    <li>CSS Dropdown Menu and Split Menu</li>
                    <li>The Template is Optimized for RokBooster</li>
                </ul>
                <p class="success">Want to use Cygnet for your clients? <a href="http://www.rockettheme.com/joomla/templates/cygnet">Purchase Single Package Now</a>.</p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~
