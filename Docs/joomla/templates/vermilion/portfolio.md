---
title: Vermilion: Recreating the Demo - Portfolio Page
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

Introduction
-----

The **Portfolio** example page demonstrates how you can create a clean, functional portfolio with the Vermilion template. Here is some information to help you replicate this page as it appears in the demo.

Page Display Options
-----

![][portfoliopage2]

The **Portfolio** page is a **Single Contact** menu item type. To recreate the layout the way it appears in our demo, enter `portfolio` in the **Alias** field in the menu item settings menu. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][portfoliopage10]

The page's content body is set in the **Portfolio** article. You will find the content used in the article below.

~~~ .html
<h3>Our Awesome Project</h3>
<p>Efficiently unleash cross-media information without cross-media value.
Quickly maximize timely deliverables for real-time schemas. Dramatically
maintain clicks-and-mortar solutions without functional solutions.</p>
<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <span class="rt-image"><img alt="image" src=
            "images/rocketlauncher/pages/portfolio/img-17.jpg"></span>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h3>Project Description</h3>
            <p>Efficiently unleash cross-media information without cross-media
            value. <span class="hidden-tablet">Quickly maximize timely
            deliverables for real-time schemas. Dramatically maintain
            clicks-and-mortar solutions without functional
            solutions.</span></p>
            <h3>Project Details</h3>
            <div class="gantry-row">
                <div class="gantry-width-30">
                    <div class="gantry-width-spacer">
                        <p class="smallmarginbottom">Customer:</p>
                        <p class="smallmarginbottom">Live Demo:</p>
                        <p class="smallmarginbottom">Published <span class=
                        "hidden-tablet">Date</span>:</p>
                    </div>
                </div>
                <div class="gantry-width-70">
                    <div class="gantry-width-spacer">
                        <p class="smallmarginbottom">RocketTheme</p>
                        <p class="smallmarginbottom">
                        http://www.rockettheme.com</p>
                        <p class="smallmarginbottom">08 March, 2014</p>
                    </div>
                </div>
            </div>
            <div class="clear">
                &nbsp;
            </div>
            <p class="largemargintop"><a class="readon" href=
            "http://www.rockettheme.com/joomla/templates/vermilion">Learn
            More</a></p>
        </div>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][portfoliopage]

:   1. **Custom HTML - Portfolio** [10%, 45%, se]
    2. **Breadcrumbs** [15%, 18%, se]
    3. **RokSprocket Mosaic** [18%, 18%, se]
    4. **RokSprocket Strips - What Our Clients Say** [46%, 18%, se]
    5. **Custom HTML - Our Satisfied Clients** [72%, 18%, se]
    6. **Custom HTML - Vermilion Demo** [82%, 18%, se]
    7. **Custom HTML - Sample Contact Info** [82%, 52%, se]
    8. **Article Content** [56%, 18%, se]

1. [Custom HTML - Portfolio](portfolio.md#custom-html---portfolio)
2. [Breadcrumbs](portfolio.md#breadcrumbs)
3. [RokSprocket Mosaic](portfolio.md#roksprocket-mosaic)
4. [RokSprocket Strips - What Our Clients Say](portfolio.md#what-our-clients-say)
5. [Custom HTML - Our Satisfied Clients](portfolio.md#custom-html---our-satisfied-clients)
6. [Custom HTML - Vermilion Demo](portfolio.md#custom-html---vermilion-demo)
7. [Custom HTML - Sample Contact Info](portfolio.md#custom-html---sample-contact-info)
8. [Article Content](portfolio.md#mainbody)

### Custom HTML - Portfolio

![][portfoliopage3]

#### Module 

| Option      | Setting                                                                      |
| :---------- | :-----------                                                                 |
| Title       | `Portfolio[span class="rt-title-tag"]What We Have Already Done[/span]` |
| Show Title  | Yes                                                                          |
| Position    | top-a                                                                        |
| Status      | Published                                                                    |
| Access      | Public                                                                       |

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

![][portfoliopage4]

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

### RokSprocket Mosaic

![][portfoliopage5]

#### Module 

| Option      | Setting                         |
| :---------- | :-----------                    |
| Title       | `Portfolio: RokSprocket Mosaic` |
| Show Title  | Hide                            |
| Position    | feature-a                       |
| Layout Type | Mosaic Layout                   |
| Provider    | Simple Provider                 |
| Status      | Published                       |
| Access      | Public                          |

#### Article List Item Example

| Option      | Setting                                                |
| :---------- | :-----------                                           |
| Title       | `Spectral`                                             |
| Description | `Objectively innovate empowered manufactured products` |
| Image       | Custom                                                 |
| Link        | Custom                                                 |
| Tags        | Logo, Web                                              |

#### Options

| Option          | Setting                      |
| :----------     | :----------                  |
| Theme           | Default                      |
| Display Limit   | ∞                            |
| Columns         | 4                            |
| Preview Length  | ∞                            |
| Only Show Tags  |                              |
| Strip HTML Tags | No                           |
| Blocks Per View | 8                            |
| Article Details | Hide author and date         |
| Block Animation | Fade, Scale, Rotate          |
| Ordering        | Default, Title, Date, Random |
| Image Size      | Disable, 0, 0                |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### What Our Clients Say

![][portfoliopage6]

#### Module 

| Option      | Setting                |
| :---------- | :-----------           |
| Title       | `What Our Clients Say` |
| Show Title  | Show                   |
| Position    | maintop-a              |
| Layout Type | Strips Layout          |
| Provider    | Simple Provider        |
| Status      | Published              |
| Access      | Public                 |

#### Article List Item Example

| Option      | Setting      |
| :---------- | :----------- |
| Title       | None         |
| Image       | None         |
| Link        | None         |

**Description**

~~~ .html
<p class="promo2">RokAjaxSearch is a configurable search module that uses AJAX to load results in real time via a styled popup. It can be set to local or Google search, inclusive of Web, image, video and blog. Results are paged and can be accessed via buttons or keyboard commands.</p>
~~~

#### Options

| Option            | Setting       |
| :----------       | :----------   |
| Theme             | Default       |
| Display Limit     | ∞             |
| Preview Length    | ∞             |
| Strip HTML Tags   | No            |
| Previews Per Page | 1             |
| Items Per Row     | 1             |
| Arrow Navigation  | Show          |
| Pagination        | Show          |
| Animation         | Fade Delayed  |
| Autoplay          | Disable       |
| Autoplay Delay    | 5             |
| Image Resize      | Disable, 0, 0 |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Our Satisfied Clients

![][portfoliopage7]

#### Module 

| Option      | Setting                 |
| :---------- | :-----------            |
| Title       | `Our Satisfied Clients` |
| Show Title  | Yes                     |
| Position    | extension-a             |
| Status      | Published               |
| Access      | Public                  |

#### Content

~~~ .html
<p>Will You be the Next to Join Our Happy Clients?</p>
<p> </p>
<div class="gantry-row">
<div class="gantry-width-20">
<div class="gantry-width-spacer"><a href="http://www.rockettheme.com/joomla/templates/hadron"><img class="rt-transparent-image" src="images/rocketlauncher/pages/portfolio/img-18.png" alt="image" /></a></div>
</div>
<div class="gantry-width-20">
<div class="gantry-width-spacer"><a href="http://www.rockettheme.com/joomla/templates/acacia"><img class="rt-transparent-image" src="images/rocketlauncher/pages/portfolio/img-19.png" alt="image" /></a></div>
</div>
<div class="gantry-width-20">
<div class="gantry-width-spacer"><a href="http://www.rockettheme.com/joomla/templates/corvus"><img class="rt-transparent-image" src="images/rocketlauncher/pages/portfolio/img-20.png" alt="image" /></a></div>
</div>
<div class="gantry-width-20">
<div class="gantry-width-spacer"><a href="http://www.rockettheme.com/joomla/templates/spectral"><img class="rt-transparent-image" src="images/rocketlauncher/pages/portfolio/img-21.png" alt="image" /></a></div>
</div>
<div class="gantry-width-20">
<div class="gantry-width-spacer"><a href="http://www.rockettheme.com/joomla/templates/stratos"><img class="rt-transparent-image" src="images/rocketlauncher/pages/portfolio/img-22.png" alt="image" /></a></div>
</div>
</div>
<div class="clear"> </div>
<p><br /><br /></p>
<p><a class="readon" href="http://www.rockettheme.com/joomla/templates/vermilion">Join Now</a></p>
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

### Custom HTML - Vermilion Demo

![][portfoliopage8]

#### Module 

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Vermilion Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Vermilion can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/vermilion">Vermilion RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
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

![][portfoliopage9]

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
<div class="gantry-width-spacer"><img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" /></div>
</div>
<div class="gantry-width-60">
<div class="gantry-width-spacer"><span class="rt-intro-text">+1(123)456-5555-555</span><br /> Vermilion Theme, LLC<br /> 123 Joomla! Boulevard<br /> Seattle, WA 00000, USA<br /> <a href="#">noreply@domain.com</a></div>
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

[portfoliopage]: assets/page_portfolio.jpeg
[portfoliopage2]: assets/page_portfolio_2.jpeg
[portfoliopage3]: assets/page_portfolio_3.jpeg
[portfoliopage4]: assets/page_portfolio_4.jpeg
[portfoliopage5]: assets/page_portfolio_5.jpeg
[portfoliopage6]: assets/page_portfolio_6.jpeg
[portfoliopage7]: assets/page_portfolio_7.jpeg
[portfoliopage8]: assets/page_portfolio_8.jpeg
[portfoliopage9]: assets/page_portfolio_9.jpeg
[portfoliopage10]: assets/page_portfolio_10.jpeg
