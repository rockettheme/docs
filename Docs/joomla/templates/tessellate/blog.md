---
title: Tessellate: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

The **Blog** example page demonstrates how you can create a beautiful page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][blogpage2]

The **Blog** page is a **Category Blog** menu item type. To recreate the layout the way it appears in our demo, enter `blog` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][blogpage11]

The page's content body is set to display articles in the **Sample Blog** category. The first article is the **Powered by Gantry Framework** article. You will find the content used in the article below.

~~~ .html
<p><span class="rt-image"><img src="images/rocketlauncher/pages/blog/img-01.jpg" alt="image" /></span></p>

<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][blogpage]

:   1. **RokAjaxSearch** [5%, 27%, se]
    2. **Custom HTML - Blog** [9%, 45%, se]
    3. **Breadcrumbs** [13%, 15%, se]
    4. **RokAjaxSearch - Search the Blog** [15%, 85%, sw]
    5. **Menu Module - Site Menu** [18%, 85%, sw]
    6. **Custom HTML - Template Tutorials** [43%, 85%, sw]
    7. **Login Form - Login Form** [52%, 85%, sw]
    8. **Who's Online - Who's Online** [56%, 85%, sw]
    9. **Custom HTML - Join Our Newsletter** [79%, 44%, se]
    10. **Custom HTML - Tessellate Demo** [85%, 15%, se]
    11. **Custom HTML - Sample Contact Info** [85%, 50%, se]
    12. **Category Blog** [16%, 55%, sw]
    13. **Menu - Copyright Menu** [92%, 72%, se]

1. [RokAjaxSearch](blog.md#rokajaxsearch)
2. [Custom HTML - Blog](blog.md#custom-html---blog)
3. [Breadcrumbs](blog.md#breadcrumbs)
4. [RokAjaxSearch - Search the Blog](blog.md#rokajaxsearch---search-the-blog)
5. [Menu Module - Site Menu](blog.md#menu-module---site-menu)
6. [Custom HTML - Template Tutorials](blog.md#custom-html---template-tutorials)
7. [Login Form - Login Form](blog.md#login---login-form)
8. [Who's Online - Who's Online](blog.md#who's-online---who's-online)
9. [Custom HTML - Join Our Newsletter](blog.md#custom-html---join-our-newsletter)
10. [Custom HTML - Tessellate Demo](blog.md#custom-html---tessellate-demo)
11. [Custom HTML - Sample Contact Info](blog.md#custom-html---sample-contact-info)
12. [Category Blog](blog.md#mainbody)
13. [Menu - Copyright Menu](blog.md#menu---copyright-menu)

### RokAjaxSearch

![][blogpage3]

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

### Custom HTML - Blog

![][blogpage4]

#### Module

| Option      | Setting                                                      |
| :---------- | :-----------                                                 |
| Title       | `Blog[span class="rt-title-tag"]Read the Latest News[/span]` |
| Show Title  | Show                                                         |
| Position    | top-a                                                        |
| Status      | Published                                                    |
| Access      | Public                                                       |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

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

![][blogpage5]

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

### RokAjaxSearch - Search the Blog

![][blogpage6]

#### Module

| Option                            | Setting                                                  |
| :----------                       | :-----------                                             |
| Title                             | `Search the Blog`                                        |
| Show Title                        | Show                                                     |
| Position                          | sidebar-a                                                |
| Status                            | Published                                                |
| Access                            | Public                                                   |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Engine URL        | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any Words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results per page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Google Ajax Search API Key        |                                                          |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimates                    | Yes                                                      |
| Hide div id(s)                    |                                                          |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include Category/Section          | Yes                                                      |
| Show Read More Link               | Yes                                                      |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box2 title2` |

### Menu Module - Site Menu

![][blogpage7]

#### Module

| Option              | Setting      |
| :----------         | :----------- |
| Title               | `Site Menu`  |
| Show Title          | Show         |
| Position            | sidebar-a    |
| Status              | Published    |
| Access              | Public       |
| Select Menu         | Main Menu    |
| Base Item           | Current      |
| Start Level         | 1            |
| End Level           | All          |
| Show Sub-Menu Items | Yes          |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box3 title3` |

### Custom HTML - Template Tutorials

![][blogpage8]

#### Module

| Option      | Setting              |
| :---------- | :-----------         |
| Title       | `Template Tutorials` |
| Show Title  | Show                 |
| Position    | sidebar-a            |
| Status      | Published            |
| Access      | Public               |

#### Content

~~~ .html
<ul>
    <li><a href="http://www.rockettheme.com/docs/joomla/platform/templates.md#how-to-install">How to Install</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_edit_the_logo.md">Change the Default Logo</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_edit_template_text.md">Editing Template Text</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_set_up_a_rokbox_member_login.md"><span class="hidden-tablet">Set Up a </span>RokBox Member Login</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_use_popup_module.md"><span class="hidden-tablet">How to Use the </span>Popup Module</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/responsive_support_classes.md">Responsive Support Classes</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/creating_responsive_content.md"><span class="hidden-tablet">Creating </span>Responsive Content</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/k2_styling_guide.md">K2 Styling Guide</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_create_a_template_override.md"><span class="hidden-tablet">How to Create a </span>Template Override</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/templates/tessellate/demo.md">Recreating the Demo</a></li>
</ul>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box1 title1` |

### Login - Login Form

![][blogpage9]

#### Module

| Option                  | Setting      |
| :----------             | :----------- |
| Title                   | `Login Form` |
| Show Title              | Show         |
| Position                | sidebar-a    |
| Status                  | Published    |
| Access                  | Public       |
| Pre-text                |              |
| Post-test               |              |
| Login Redirection Page  | Default      |
| Logout Redirection Page | Default      |
| Show Greeting           | Yes          |
| Show Name/Username      | Name         |
| Encrypt Login Form      | No           |
| Display Labels          | Icons        |

#### Advanced

| Option              | Setting       |
| :----------         | :-----------  |
| Module Class Suffix | `box4 title4` |

### Who's Online - Who's Online

![][blogpage10]

#### Module

| Option      | Setting             |
| :---------- | :-----------        |
| Title       | `Who's Online`      |
| Show Title  | Show                |
| Position    | sidebar-a           |
| Status      | Published           |
| Access      | Public              |
| Display     | # of Guests / Users |

#### Advanced

| Option              | Setting      |
| :-----------        | :----------- |
| Module Class Suffix | `title1`     |

### Custom HTML - Join Our Newsletter

![][blogpage12]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Join Our Newsletter` |
| Show Title  | Yes                   |
| Position    | extension-a           |
| Status      | Published             |
| Access      | Public                |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-60 gantry-block-center">
        <div class="gantry-width-spacer">
            <p><span>Get Updates, Upcoming Themes Info, and Our Great Deals!</span></p>
            <form class="rt-blog-form largemargintop largepaddingtop" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
                <input type="hidden" value="rocketthemeblog" name="uri" />
                <input type="hidden" name="loc" value="en_US" />
                <input type="submit" name="Submit" class="readon" value="Join" />
            </form>
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

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Tessellate Demo

![][blogpage13]

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

![][blogpage14]

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

![][blogpage15]

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

[blogpage]: assets/page_blog.jpg
[blogpage2]: assets/page_blog_2.jpeg
[blogpage3]: assets/page_blog_3.jpeg
[blogpage4]: assets/page_blog_4.jpeg
[blogpage5]: assets/page_blog_5.jpeg
[blogpage6]: assets/page_blog_6.jpeg
[blogpage7]: assets/page_blog_7.jpeg
[blogpage8]: assets/page_blog_8.jpeg
[blogpage9]: assets/page_blog_9.jpeg
[blogpage10]: assets/page_blog_10.jpeg
[blogpage11]: assets/page_blog_11.jpeg
[blogpage12]: assets/page_blog_12.jpeg
[blogpage13]: assets/page_blog_13.jpeg
[blogpage14]: assets/page_blog_14.jpeg
[blogpage15]: assets/demo_21.jpeg
