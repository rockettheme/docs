---
title: Nuance: Recreating the Demo - Contact Us Page
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

Introduction
-----

The **Contact Us** example page demonstrates how you can create a clean, functional contact page with the Nuance template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][contactusmenu]

The **Contact Us** page is a **Single Contact** menu item type. To recreate the layout the way it appears in our demo, enter `contact-us` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][contactuspage]

:   1. **Custom HTML - Contact Us** [13%, 45%, se]
    2. **Custom HTML - Contact Info** [21%, 64%, se]
    3. **Custom HTML - Got Billing and Payments Questions?** [64%, 35%, se]
    4. **Custom HTML - Nuance Demo** [73%, 12%, se]
    5. **Custom HTML - Sample Contact Info** [73%, 52%, se]

1. [Custom HTML - Contact Us](contactus.md#custom-html---contact-us)
2. [Custom HTML - Contact Info](contactus.md#custom-html---contact-info)
3. [Custom HTML - Got Billing and Payments Questions?](contactus.md#custom-html---got-billing-and-payments-questions?)
4. [Custom HTML - Nuance Demo](contactus.md#custom-html---nuance-demo)
5. [Custom HTML - Sample Contact Info](contactus.md#contactus.md#custom-html---sample-contact-info)

### Custom HTML - Contact Us

![][contactuspage2]

#### Module

| Option      | Setting                                                                      |
| :---------- | :-----------                                                                 |
| Title       | `Contact Us[span class="rt-title-tag"]We Would Love to Hear From You[/span]` |
| Show Title  | Yes                                                                          |
| Position    | showcase-a                                                                   |
| Status      | Published                                                                    |
| Access      | Public                                                                       |

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                                                        |
| :----------         | :----------                                                                    |
| Module Class Suffix | `rt-top-large-padding nomarginall rt-center rt-title-large rt-nomodulecontent` |

### Custom HTML - Contact Info

![][contactuspage3]

#### Module

| Option      | Setting        |
| :---------- | :-----------   |
| Title       | `Contact Info` |
| Show Title  | Yes            |
| Position    | sidebar-a      |
| Status      | Published      |
| Access      | Public         |

#### Content

~~~ .html
<p><span class="rt-image"><img src="images/rocketlauncher/pages/contact-us/img-01.jpg" alt="image" /></span></p>

<p>Nuance is only available as part of the Club Subscription.<span class="hidden-tablet"> Please use the RocketLauncher to install an equivalent of the demo onto your site.</span></p>

<h4>Address</h4>
<p>
    <span>Nuance Theme, LLC</span><br />
    <span>123 Joomla! Boulevard</span><br />
    <span>Seattle, WA 00000, USA</span>
</p>

<h4>Email</h4>
<p>
    <span>noreply@nuance-theme.com</span><br />
    <span>noperson@nuance-theme.com</span>
</p>

<h4>Phone</h4>
<p>
    <span>+1(123)456-5555-555</span><br />
    <span>+1(123)456-6666-666</span>
</p>

<h4>Online Support</h4>
<p>
    <span>Skype ID: nuance.theme</span><br />
    <span>BBM PIN: 12ABC345</span>
</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                    |
| :----------         | :----------                                |
| Module Class Suffix | `box1 title4 medmarginbottom medmargintop` |

### Custom HTML - Got Billing and Payments Questions?

![][contactuspage4]

#### Module

| Option      | Setting                               |
| :---------- | :-----------                          |
| Title       | `Got Billing and Payments Questions?` |
| Show Title  | Yes                                   |
| Position    | extension-a                           |
| Status      | Published                             |
| Access      | Public                                |

#### Content

~~~ .html
<p>Email Us for Questions Involving Payments, Billing, and Membership.</p>

<p><a href="http://www.rockettheme.com/forum/joomla-template-nuance" class="readon largemargintop">Send Email</a></p>
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

### Custom HTML - Nuance Demo

![][contactuspage5]

#### Module

| Option      | Setting           |
| :---------- | :-----------      |
| Title       | `Nuance Demo` |
| Show Title  | Yes               |
| Position    | footer-a          |
| Status      | Published         |
| Access      | Public            |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Nuance can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/nuance">Nuance RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][contactuspage6]

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
			<span>Nuance Theme, LLC</span><br />
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

[contactuspage]: assets/page_contactus.jpeg
[contactusmenu]: assets/page_contactus_menu.jpeg
[contactuspage2]: assets/page_contactus_2.jpeg
[contactuspage3]: assets/page_contactus_3.jpeg
[contactuspage4]: assets/page_contactus_4.jpeg
[contactuspage5]: assets/page_contactus_5.jpeg
[contactuspage6]: assets/page_contactus_6.jpeg
[contactuspage7]: assets/page_contactus_7.jpeg
[contactuspage8]: assets/page_contactus_8.jpeg
[contactuspage9]: assets/page_contactus_9.jpeg
[contactuspage10]: assets/demo_21.jpeg
