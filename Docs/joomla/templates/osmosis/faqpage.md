---
title: Osmosis: Recreating the Demo - FAQ Page
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

Introduction
-----

The **FAQ** example page demonstrates how you can create a beautiful page with the Osmosis template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][faqpage10]

The **FAQ** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `faq` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][faqpage5]

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Common Queries and Questions</h3>
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
<ul>
    <li>Versatile, Flexible Features Powered by the Gantry Framework.</li>
    <li>Gantry is a free framework for both Joomla and WordPress.</li>
    <li>A selection of configurable preset style variations are available.</li>
</ul>
<p><a href="http://www.rockettheme.com/docs/joomla/templates/osmosis" class="readon">Help &amp; Knowledge</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][faqpage]

:   1. **Custom HTML - FAQ** [12%, 45%, se]
    2. **Breadcrumbs** [19%, 16%, se]
    3. **Custom HTML - Forum Support** [23%, 16%, se]
    4. **Article Content** [39%, 16%, se]
    5. **RokSprocket Lists** [52%, 16%, se]
    6. **Custom HTML - FAQ Didn't Solve Your Problem?** [68%, 35%, se]
    7. **Custom HTML - Osmosis Demo** [77%, 16%, se]
    8. **Custom HTML - Sample Contact Info** [77%, 52%, se]

1. [Custom HTML - FAQ](faq.md#custom-html---faq)
2. [Breadcrumbs](faq.md#breadcrumbs)
3. [Custom HTML - Forum Support](faqpage.md#custom-html---forum-support)
4. [Article Content](faq.md#mainbody)
5. [RokSprocket Lists](faqpage.md#roksprocket-lists)
6. [Custom HTML - FAQ Didn't Solve Your Problem?](faqpage.md#custom-html---faq-didn't-solve-your-problem?)
7. [Custom HTML - Osmosis Demo](faq.md#custom-html---osmosis-demo)
8. [Custom HTML - Sample Contact Info](faq.md#custom-html---sample-contact-info)

### Custom HTML - FAQ

![][faqpage2]

#### Module

| Option      | Setting                                                      |
| :---------- | :-----------                                                 |
| Title       | `FAQ[span class="rt-title-tag"]Questions and Answers[/span]` |
| Show Title  | Yes                                                          |
| Position    | top-a                                                        |
| Status      | Published                                                    |
| Access      | Public                                                       |

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

![][faqpage3]

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

### Custom HTML - Forum Support

![][faqpage4]

#### Module

| Option      | Setting                                         |
| :---------- | :-----------                                    |
| Title       | `FAQ: Forum Support - Ticket Email - Live Chat` |
| Show Title  | Hide                                            |
| Position    | feature-a                                       |
| Status      | Published                                       |
| Access      | Public                                          |

#### Content

~~~ .html
<div class="gantry-width-33">
    <img src="images/rocketlauncher/pages/faq/img-01.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Forum Support</h4>
        <p>Objectively innovate empowered manufactured products with parallel platforms.</p>
        <p><a href="http://www.rockettheme.com/forum/joomla-template-Osmosis">Ask Community</a></p>
    </div>
</div>
<div class="gantry-width-33">
        <img src="images/rocketlauncher/pages/faq/img-02.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Ticket &amp; Email</h4>
        <p>Proactively envisioned multimedia based expertise and effective cross-media strategies.</p>
        <p><a href="http://www.rockettheme.com/forum/joomla-template-Osmosis">Send Email</a></p>
    </div>
</div>
<div class="gantry-width-33">
    <img src="images/rocketlauncher/pages/faq/img-03.jpg" alt="image" />
    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Live Chat</h4>
        <p>Interactively coordinate proactive e-commerce via process-centric outside the box.</p>
        <p><a href="http://www.rockettheme.com/forum/joomla-template-Osmosis">Contact Us</a></p>
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

| Option              | Setting                  |
| :----------         | :----------              |
| Module Class Suffix | `nopaddingall rt-center` |

### RokSprocket Lists

![][faqpage6]

#### Module

| Option      | Setting                  |
| :---------- | :-----------             |
| Title       | `FAQ: RokSprocket Lists` |
| Show Title  | Hide                     |
| Position    | mainbottom-a             |
| Status      | Published                |
| Access      | Public                   |
| Provider    | Simple                   |
| Layout      | Lists Layout             |

#### Filtered Article List Item Sample

| Option     | Setting                         |
| :--------- | :----------                     |
| Title      | `What prices are our services?` |
| Image      | None                            |
| Link       | None                            |

**Description**

~~~ .html
Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.
~~~

#### Options

| Option              | Setting     |
| :----------         | :---------- |
| Theme               | Default     |
| Display Limit       | ∞           |
| Collapsible Preview | Enable      |
| Preview Length      | ∞           |
| Strip HTML Tags     | No          |
| Previews per Page   | 3           |
| Arrow Navigation    | Show        |
| Pagination          | Show        |
| Autoplay            | Disable     |
| Autoplay Delay      | 5           |
| Image Resize        | Disable     |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### Custom HTML - FAQ Didn't Solve Your Problem?

![][faqpage7]

#### Module

| Option      | Setting                          |
| :---------- | :-----------                     |
| Title       | `FAQ Didn't Solve Your Problem?` |
| Show Title  | Show                             |
| Position    | extension-a                      |
| Status      | Published                        |
| Access      | Public                           |

#### Content

~~~ .html
<p>Get Direct Access to the Team Via Phone, Email or Live Chat.</p>
<p><a href="http://www.rockettheme.com/forum/joomla-template-Osmosis" class="readon largemargintop">Contact Us</a></p>
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

### Custom HTML - Osmosis Demo

![][faqpage8]

#### Module

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Osmosis Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Osmosis can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/osmosis">Osmosis RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][faqpage9]

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
<div class="gantry-width-40">
	<div class="gantry-width-spacer">
		<img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
	</div>
</div>
<div class="gantry-width-60">
	<div class="gantry-width-spacer">
		<span class="rt-intro-text">+1(123)456-5555-555</span><br />
		<span>Osmosis Theme, LLC</span><br />
		<span>123 Joomla! Boulevard</span><br />
		<span>Seattle, WA 00000, USA</span><br />
		<span><a href="#">noreply@domain.com</a></span>
	</div>
</div>
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

[faqpage]: assets/page_faq.jpeg
[faqpage2]: assets/page_faq_2.jpeg
[faqpage3]: assets/page_faq_3.jpeg
[faqpage4]: assets/page_faq_4.jpeg
[faqpage5]: assets/page_faq_5.jpeg
[faqpage6]: assets/page_faq_6.jpeg
[faqpage7]: assets/page_faq_7.jpeg
[faqpage8]: assets/page_faq_8.jpeg
[faqpage9]: assets/page_faq_9.jpeg
[faqpage10]: assets/page_faq_10.jpg
[faqpage11]: assets/page_faq_11.jpeg
