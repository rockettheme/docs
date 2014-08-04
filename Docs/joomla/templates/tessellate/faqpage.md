---
title: Tessellate: Recreating the Demo - FAQ Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

The **FAQ** example page demonstrates how you can create a beautiful page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][faqpage2]

The **FAQ** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `faq` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][faqpage7]

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Common Queries and Questions</h3>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
<ul>
    <li>Versatile, Flexible Features Powered by the Gantry Framework.</li>
    <li>Gantry is a free framework for both Joomla and WordPress.</li>
    <li>A selection of configurable preset style variations are available.</li>
</ul>

<p><a href="http://www.rockettheme.com/docs/joomla/templates/tessellate" class="readon">Help &amp; Knowledge</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][faqpage]

:   1. **RokAjaxSearch** [6%, 25%, se]
    2. **Custom HTML - FAQ** [14%, 45%, se]
    3. **Breadcrumbs** [21%, 12%, se]
    4. **Custom HTML - Forum Support** [24%, 12%, se]
    5. **Article Content** [39%, 12%, se]
    6. **RokSprocket Lists** [52%, 12%, se]
    7. **Custom HTML - FAQ Didn't Solve Your Problem?** [68%, 35%, se]
    8. **Custom HTML - Tessellate Demo** [77%, 12%, se]
    9. **Custom HTML - Sample Contact Info** [77%, 52%, se]
    10. **Menu - Copyright Menu** [92%, 72%, se]

1. [RokAjaxSearch](faqpage.md#rokajaxsearch)
2. [Custom HTML - FAQ](faqpage.md#custom-html---faq)
3. [Breadcrumbs](faqpage.md#breadcrumbs)
4. [Custom HTML - Forum Support](faqpage.md#custom-html---forum-support)
5. [Article Content](faqpage.md#mainbody)
6. [RokSprocket Lists](faqpage.md#roksprocket-lists)
7. [Custom HTML - FAQ Didn't Solve Your Problem?](faqpage.md#custom-html---faq-didn't-solve-your-problem?)
8. [Custom HTML - Tessellate Demo](faqpage.md#custom-html---tessellate-demo)
9. [Custom HTML - Sample Contact Info](faqpage.md#custom-html---sample-contact-info)
10. [Menu - Copyright Menu](faqpage.md#menu---copyright-menu)

### RokAjaxSearch

![][faqpage3]

#### Details

| Option      | Setting            |
| :---------- | :----------        |
| Title       | `FP RokAjaxSearch` |
| Show Title  | Hide               |
| Position    | header-b           |
| Status      | Published          |
| Access      | Public             |

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

### Custom HTML - FAQ

![][faqpage4]

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

![][faqpage5]

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

![][faqpage6]

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
<div class="gantry-width-container">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-01.jpg" alt="image" />
            <h4 class="medpaddingtop">Forum Support</h4>
            <p>Objectively innovate empowered manufactured products with parallel platforms.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-tessellate">Ask Community</a></p>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-02.jpg" alt="image" />
            <h4 class="medpaddingtop">Ticket &amp; Email</h4>
            <p>Proactively envisioned multimedia based expertise and effective cross-media strategies.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-tessellate">Send Email</a></p>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer largemargintop largemarginbottom">
            <img src="images/rocketlauncher/pages/faq/img-03.jpg" alt="image" />
            <h4 class="medpaddingtop">Live Chat</h4>
            <p>Interactively coordinate proactive e-commerce via process-centric outside the box.</p>
            <p><a href="http://www.rockettheme.com/forum/joomla-template-tessellate">Contact Us</a></p>
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

| Option              | Setting                  |
| :----------         | :----------              |
| Module Class Suffix | `nopaddingall rt-center` |

### RokSprocket Lists

![][faqpage8]

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

![][faqpage9]

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
<p><a href="http://www.rockettheme.com/forum/joomla-template-Tessellate" class="readon largemargintop">Contact Us</a></p>
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

![][faqpage10]

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

![][faqpage11]

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

![][faqpage12]

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

[faqpage]: assets/page_faq.jpeg
[faqpage2]: assets/page_faq_2.jpeg
[faqpage3]: assets/page_faq_3.jpeg
[faqpage4]: assets/page_faq_4.jpeg
[faqpage5]: assets/page_faq_5.jpeg
[faqpage6]: assets/page_faq_6.jpeg
[faqpage7]: assets/page_faq_7.jpeg
[faqpage8]: assets/page_faq_8.jpeg
[faqpage9]: assets/page_faq_9.jpeg
[faqpage10]: assets/page_faq_10.jpeg
[faqpage11]: assets/page_faq_11.jpeg
[faqpage12]: assets/page_faq_12.jpeg
