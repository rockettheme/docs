---
title: Cygnet: Recreating the Demo - Slideshow
description: Your Guide to Recreating Elements of the Cygnet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Slideshow Section
-----

![Slideshow](assets/demo_2.jpeg)

Here is the widget breakdown for the Slideshow section:

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate posts or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option | Setting                                             |
| :----- | :-----                                              |
| Title  | `Cygnet bridges the gap between corporate and hip!` |
| Image  | Custom                                              |
| Link   | Custom                                              |

**Description**

~~~ .html
<p><span>The theme features contemporary design elements <span class=
"hidden-tablet">and structures, whilst maintaining a subtle, corporate-esque
overall appearance to maximize professionalism and visual
intrigue</span>.</span></p><a class="readon" href=
"http://demo.rockettheme.com/live/wordpress/cygnet/features-overview/">Learn
More</a><a class="readon2" href="#"><i class="fa fa-fw fa-play"></i> Watch
Presentation</a>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting   |
| :--------------- | :-------- |
| Display Limit    | ∞         |
| Theme            | Showcase  |
| Article Titles   | Show      |
| Article Text     | Show      |
| Preview Length   | ∞         |
| Strip HTML Tags  | No        |
| Arrow Navigation | Hide      |
| Pagination       | Show      |
| Animation        | Crossfade |
| Autoplay         | Disable   |
| Autoplay Delay   | 5         |
| Image Resize     | Disable   |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

| Option            | Setting                                          |
| :-----            | :-----                                           |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Custom Variations | `fp-roksprocket-slideshow`                       |

Leaving everything else at its default setting, select **Save**.
