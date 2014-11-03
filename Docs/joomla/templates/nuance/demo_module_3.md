
---
title: Nuance: Recreating the Demo - FP RokSprocket Features Scroller - Showcase
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

FP RokSprocket Features Scroller - Showcase
-----

![][demo]

The **RokSprocket Showcase** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider, allowing us to create custom content independent of full articles. The **Title**, **Description**, **Link**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** and **Link** fields which will likely not work on your local copy as the links will be different.

### Details

![][demo2]

| Option           | Setting                                       |
| :----------      | :----------                                   |
| Title            | `FP RokSprocket Features Scroller - Showcase` |
| Show Title       | Hide                                          |
| Access           | Public                                        |
| Position         | showcase-a                                    |
| Status           | Published                                     |
| Content Provider | Simple                                        |
| Type             | Features                                      |

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<span class="sprocket-scrollbar-title1"><i class="fa fa-map-marker fa-fw"></i> Colorful<span class="hidden-tablet"> Infusion</span></span><span class="sprocket-scrollbar-title2">Transparent<span class="hidden-tablet"> Areas</span></span>
~~~

**Description**

~~~ .html
<span class="sprocket-scroller-content">The <a href="#">transparent</a> nature of the Nuance design allows the background colors to bleed through to the forefront, to <a href="#">complement and embellish</a> your content.</span>
~~~

#### Article 2

**Title**

~~~
<span class="sprocket-scrollbar-title1"><i class="fa fa-map-marker fa-fw"></i> Gantry<span class="hidden-tablet"> Framework</span></span><span class="sprocket-scrollbar-title2"><span class="hidden-tablet">Several </span>Platforms</span>
~~~

**Description**

~~~ .html
<span class="sprocket-scroller-content">A <a href="#">free, GPL</a> and powerful core framework that powers the template with its set of <a href="#">standardized features</a>, functions and <a href="#">control interface</a>.</span>
~~~

#### Article 3

**Title**

~~~ .html
<span class="sprocket-scrollbar-title1"><i class="fa fa-map-marker fa-fw"></i> Responsive<span class="hidden-tablet"> Design</span></span><span class="sprocket-scrollbar-title2">Automatic <span class="hidden-tablet">Adjustment</span></span>
~~~

**Description**

~~~ .html
<span class="sprocket-scroller-content">A layout that adjusts <a href="#">automatically</a> to the viewing device's width to ensure <a href="#">uniformity</a> across all devices visiting your site, including <a href="#">mobile</a>.</span>
~~~

### Layout Options

![][demo3]

| Option                | Setting               |
| :----------           | :----------           |
| Display Limit         | ∞                     |
| Theme                 | Scroller              |
| Article Titles        | Show                  |
| Article Text          | Show                  |
| Preview Length        | ∞                     |
| Strip HTML Tags       | No                    |
| Arrow Navigation      | Show on Hover         |
| Pagination            | Show                  |
| Animation             | Crossfade             |
| Autoplay              | Disable               |
| Autoplay Delay        | 5                     |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

### Advanced

![][demo4]

| Option              | Setting                            |
| :----------         | :----------                        |
| Module Class Suffix | `fp-roksprocket-features-scroller` |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg