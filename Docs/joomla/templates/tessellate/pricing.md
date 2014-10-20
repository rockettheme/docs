---
title: Tessellate: Recreating the Demo - Pricing Tables Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

The **Pricing Tables** example page demonstrates how you can create a beautiful page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][pricingpage2]

The **Pricing Tables** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `pricing-tables` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][pricingpage6]

The page's content body is set in the **Pricing Tables** article. You will find the content used in the article below.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Simple Plans and Pricing</h3>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
                <p class="hidden-tablet">Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
                <p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon">Sign Up</a></p>
            </div>
        </div>
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Top Tessellate Features</h3>
                <ul>
                    <li>Powered by Gantry Framework</li>
                    <li>CSS Dropdown Menu and Split Menu</li>
                    <li>The Template is Optimized for RokBooster</li>
                </ul>
                <p class="success">Want to use Tessellate for your clients? <a href="http://www.rockettheme.com/joomla/templates/tessellate">Purchase Single Package Now</a>.</p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][pricingpage]

:   1. **RokAjaxSearch** [5%, 25%, se]
    2. **Custom HTML - Pricing** [14%, 45%, se]
    3. **Breadcrumbs** [21%, 12%, se]
    4. **Article Content** [24%, 12%, se]
    5. **Custom HTML - Try it Out for 10 Days Free** [38%, 12%, se]
    6. **Custom HTML - No Hidden Fee** [68%, 12%, se]
    7. **Custom HTML - Tessellate Demo** [77%, 12%, se]
    8. **Custom HTML - Sample Contact Info** [77%, 52%, se]
    9. **Menu - Copyright Menu** [92%, 72%, se]

1. [RokAjaxSearch](pricing.md#rokajaxsearch)
2. [Custom HTML - Pricing](pricing.md#custom-html---pricing)
3. [Breadcrumbs](pricing.md#breadcrumbs)
4. [Article Content](pricing.md#custom-html---about-us:-introduction)
5. [Custom HTML - Try it Out for 10 Days Free](pricing.md#mainbody)
6. [Custom HTML - No Hidden Fee](pricing.md#custom-html---about-us:-our-mission---our-values---our-solution)
7. [Custom HTML - Tessellate Demo](pricing.md#custom-html---tessellate-demo)
8. [Custom HTML - Sample Contact Info](pricing.md#custom-html---sample-contact-info)
9. [Menu - Copyright Menu](pricing.md#menu---copyright-menu)

### RokAjaxSearch

![][pricingpage3]

#### Details

| Option      | Setting            |
| :---------- | :----------        |
| Title       | `FP RokAjaxSearch` |
| Show Title  | Hide               |
| Position    | header-b           |
| Status      | Published          |
| Access      | Public             |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Module

| Option                            | Setting                                                  |
| :----------                       | :----------                                              |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

### Custom HTML - Pricing

![][pricingpage4]

#### Module

| Option      | Setting                                                              |
| :---------- | :-----------                                                         |
| Title       | `Pricing[span class="rt-title-tag"]Pick a Plan that Fits You[/span]` |
| Show Title  | Show                                                                 |
| Position    | top-a                                                                |
| Status      | Published                                                            |
| Access      | Public                                                               |

#### Content

~~~ .html
&nbsp;
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option                    | Setting                                       |
| :----------               | :----------                                   |
| Module Class Suffix       | `rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![][pricingpage5]

#### Module

| Option              | Setting       |
| :----------         | :-----------  |
| Title               | `Breadcrumbs` |
| Show You Are Here   | No            |
| Show Home           | Yes           |
| Text for Home Entry |               |
| Show Last           | Yes           |
| Text Separator      |               |
| Show Title          | Hide          |
| Status              | Published     |
| Access              | Public        |

##### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### Custom HTML - Try it Out for 10 Days Free

![][pricingpage7]

#### Module

| Option      | Setting                       |
| :---------- | :-----------                  |
| Title       | `Try it Out for 10 Days Free` |
| Show Title  | Hide                          |
| Position    | expandedbottom-a              |
| Status      | Published                     |
| Access      | Public                        |

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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/tessellate">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/tessellate">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/tessellate">Sign Up</a></li>
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
            <li class="rt-table-cta-button"><a class="readon" href="http://www.rockettheme.com/joomla/templates/tessellate">Sign Up</a></li>
        </ul>
    </div>
</div>

<div class="clear"></div>

<div class="gantry-width-spacer">
    <p>Free <strong>10 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="http://www.rockettheme.com/joomla/templates/tessellate">View Professional Plan</a>.</p>
</div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                  |
| :----------         | :----------                              |
| Module Class Suffix | `rt-center nopaddingleft nopaddingright` |

### Custom HTML - No Hidden Fee

![][pricingpage8]

#### Module

| Option      | Setting         |
| :---------- | :-----------    |
| Title       | `No Hidden Fee` |
| Show Title  | Hide            |
| Position    | extension-a     |
| Status      | Published       |
| Access      | Public          |

#### Content

~~~ .html
<p>No Credit Card Required and No Long-Term Contracts</p>
<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon largemargintop">Sign Up</a></p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Tessellate Demo

![][pricingpage9]

#### Module

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Tessellate Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Tessellate can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/tessellate">Tessellate RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![][pricingpage10]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Sample Contact Info` |
| Show Title  | Yes                   |
| Position    | footer-b              |
| Status      | Published             |
| Access      | Public                |

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
			<span>Tessellate Theme, LLC</span><br />
			<span>123 Joomla! Boulevard</span><br />
			<span>Seattle, WA 00000, USA</span><br />
			<span><a href="#">noreply@domain.com</a></span>
		</div>
	</div>
</div>
<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Menu - Copyright Menu

![][pricingpage11]

### Details

| Option      | Setting             |
| :---------- | :----------         |
| Title       | `FP Copyright Memu` |
| Show Title  | Hide                |
| Position    | copyright-b         |
| Status      | Published           |
| Access      | Public              |

### Basic Options

| Option              | Setting        |
| :----------         | :----------    |
| Select Menu         | Copyright Menu |
| Base Item           | Current        |
| Start Level         | 1              |
| End Level           | All            |
| Show Sub-menu Items | Yes            |

### Advanced Options

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `rt-horizmenu` |

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
