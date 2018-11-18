---
title: Chimera: Recreating the Demo - Contact Us Page
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Introduction
-----

The **Contact Us** example page demonstrates how you can create a clean, functional contact page with the Chimera template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][contactusmenu]

The **Contact Us** page is a **Single Contact** menu item type. To recreate the layout the way it appears in our demo, enter `contact-us` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][contactuspage]

:   1. **Custom HTML - Contact Us** [11%, 45%, se]
    2. **Breadcrumbs** [17%, 12%, se]
    2. **Custom HTML - Contact Info** [21%, 64%, se]
    3. **Custom HTML - Got Billing and Payments Questions?** [64%, 35%, se]
    4. **Custom HTML - Chimera Demo** [75%, 12%, se]
    5. **Custom HTML - Sample Contact Info** [75%, 52%, se]

1. [Custom HTML - Contact Us](contactus.md#custom-html---contact-us)
2. [Breadcrumbs](contactus.md#breadcrumbs)
2. [Custom HTML - Contact Info](contactus.md#custom-html---contact-info)
3. [Custom HTML - Got Billing and Payments Questions?](contactus.md#custom-html---got-billing-and-payments-questions?)
4. [Custom HTML - Chimera Demo](contactus.md#custom-html---chimera-demo)
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

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                                                                        |
| :----------         | :----------                                                                    |
| Module Class Suffix | `rt-top-large-padding nomarginall rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![][contactuspage3]

#### Module

| Option              | Setting       |  
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

| Option              | Setting                                                    |  
| :------------------ | :--------------------------------------------------------- |  
| Module Class Suffix | ` hidden-phone nomarginall medpaddingtop medpaddingbottom` |  

### Custom HTML - Contact Info

![][contactuspage4]

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

<p>Chimera is only available as part of the Club Subscription.<span class="hidden-tablet"> Please use the RocketLauncher to install an equivalent of the demo onto your site.</span></p>

<h4>Address</h4>
<p>
    <span>Chimera Theme, LLC</span><br />
    <span>123 Joomla! Boulevard</span><br />
    <span>Seattle, WA 00000, USA</span>
</p>

<h4>Email</h4>
<p>
    <span>noreply@chimera-theme.com</span><br />
    <span>noperson@chimera-theme.com</span>
</p>

<h4>Phone</h4>
<p>
    <span>+1(123)456-5555-555</span><br />
    <span>+1(123)456-6666-666</span>
</p>

<h4>Online Support</h4>
<p>
    <span>Skype ID: chimera.theme</span><br />
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

![][contactuspage5]

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

<p><a href="http://www.rockettheme.com/forum/joomla-template-chimera" class="readon largemargintop">Send Email</a></p>
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

### Custom HTML - Chimera Demo

![][contactuspage6]

#### Module

| Option      | Setting           |
| :---------- | :-----------      |
| Title       | `Chimera Demo` |
| Show Title  | Yes               |
| Position    | footer-a          |
| Status      | Published         |
| Access      | Public            |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Chimera can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/chimera">Chimera RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][contactuspage7]

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
			<span>Chimera Theme, LLC</span><br />
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
[contactuspage6]: assets/page_aboutus_8.jpeg
[contactuspage7]: assets/page_aboutus_9.jpeg
[contactuspage8]: assets/page_contactus_8.jpeg
[contactuspage9]: assets/page_contactus_9.jpeg
[contactuspage10]: assets/demo_21.jpeg
