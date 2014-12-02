---
title: Myriad: Recreating the Demo - FAQ Page
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Introduction
-----

The **FAQ** example page demonstrates how you can create a beautiful page with the Myriad template. Here is some information to help you replicate this page as it appears in the demo.

Mainbody
-----

![][faqpage6]

The page's content body is set in the **FAQ** article. You will find the content used in the article below.

~~~ .html
<h3>Common Queries and Questions</h3>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
<ul>
    <li>Versatile, Flexible Features Powered by the Gantry Framework.</li>
    <li>Gantry is a free framework for both Joomla and WordPress.</li>
    <li>A selection of configurable preset style variations are available.</li>
</ul>

<p><a href="http://www.rockettheme.com/docs/joomla/templates/myriad" class="readon">Help &amp; Knowledge</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][faqpage]

:   1. **Custom HTML - FAQ** [10%, 45%, se]
    2. **Breadcrumbs** [14%, 12%, se]
    2. **Custom HTML - Forum Support** [17%, 12%, se]
    3. **Article Content** [50%, 12%, se]
    4. **RokSprocket Lists** [37%, 12%, se]
    5. **Custom HTML - FAQ Didn't Solve Your Problem?** [65%, 35%, se]
    6. **Custom HTML - Myriad Demo** [75%, 12%, se]
    7. **Custom HTML - Sample Contact Info** [75%, 52%, se]

1. [Custom HTML - FAQ](faqpage.md#custom-html---faq)
2. [Breadcrumbs](faqpage.md#breadcrumbs)
2. [Custom HTML - Forum Support](faqpage.md#custom-html---forum-support)
3. [Article Content](faqpage.md#mainbody)
4. [RokSprocket Lists](faqpage.md#roksprocket-lists)
5. [Custom HTML - FAQ Didn't Solve Your Problem?](faqpage.md#custom-html---faq-didn't-solve-your-problem?)
6. [Custom HTML - Myriad Demo](faqpage.md#custom-html---myriad-demo)
7. [Custom HTML - Sample Contact Info](faqpage.md#custom-html---sample-contact-info)

### Custom HTML - FAQ

![][faqpage2]

#### Module

| Option      | Setting                                                      |
| :---------- | :-----------                                                 |
| Title       | `FAQ[span class="rt-title-tag"]Questions and Answers[/span]` |
| Show Title  | Yes                                                          |
| Position    | showcase-a                                                   |
| Status      | Published                                                    |
| Access      | Public                                                       |

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

![][faqpage3]

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

### Custom HTML - Forum Support

![][faqpage4]

#### Module

| Option      | Setting                                         |
| :---------- | :-----------                                    |
| Title       | `FAQ: Forum Support - Ticket Email - Live Chat` |
| Show Title  | Hide                                            |
| Position    | maintop-a                                       |
| Status      | Published                                       |
| Access      | Public                                          |

#### Content

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-01.jpg" alt="image" />
            <h4 class="medpaddingtop">Forum Support</h4>
            <p>Objectively innovate empowered manufactured products with parallel platforms.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-myriad">Ask Community</a></p>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-02.jpg" alt="image" />
            <h4 class="medpaddingtop">Ticket &amp; Email</h4>
            <p>Proactively envisioned multimedia based expertise and effective cross-media strategies.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-myriad">Send Email</a></p>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-03.jpg" alt="image" />
            <h4 class="medpaddingtop">Live Chat</h4>
            <p>Interactively coordinate proactive e-commerce via process-centric outside the box.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-myriad">Contact Us</a></p>
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

|        Option       |     Setting      |
| :------------------ | :--------------- |
| Module Class Suffix | `box3 rt-center` |

### RokSprocket Lists

![][faqpage5]

#### Module

|   Option   |         Setting          |
| :--------- | :----------------------- |
| Title      | `FAQ: RokSprocket Lists` |
| Show Title | Hide                     |
| Position   | maintop-a                |
| Status     | Published                |
| Access     | Public                   |
| Provider   | Simple                   |
| Layout     | Lists Layout             |

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
<p><a href="http://www.rockettheme.com/forum/joomla-template-Myriad" class="readon largemargintop">Contact Us</a></p>
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

### Custom HTML - Myriad Demo

![][faqpage8]

#### Module

| Option      | Setting       |
| :---------- | :-----------  |
| Title       | `Myriad Demo` |
| Show Title  | Yes           |
| Position    | bottom-a      |
| Status      | Published     |
| Access      | Public        |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Myriad can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/myriad">Myriad RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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
| Position    | bottom-b              |
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
			<span>Myriad Theme, LLC</span><br />
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

[faqpage]: assets/page_faq.jpeg
[faqpage2]: assets/page_faq_1.jpeg
[faqpage3]: assets/page_faq_2.jpeg
[faqpage4]: assets/page_faq_3.jpeg
[faqpage5]: assets/page_faq_4.jpeg
[faqpage6]: assets/page_faq_5.jpeg
[faqpage7]: assets/page_faq_6.jpeg
[faqpage8]: assets/page_faq_7.jpeg
[faqpage9]: assets/page_faq_8.jpeg
[faqpage10]: assets/page_faq_9.jpeg
[faqpage11]: assets/page_faq_10.jpeg
[faqpage12]: assets/page_faq_11.jpeg
