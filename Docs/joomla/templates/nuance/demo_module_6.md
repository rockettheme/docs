---
title: Nuance: Recreating the Demo - RokSprocket Grids - Multiple Layouts
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

RokSprocket Grids - Multiple Layouts
-----

![][demo]

This area of the page is a **RokSprocket** module utilizing the **Simple** content provider and the **Grids** layout. 

The settings used in our demo are listed below.

### Details

![][demo2]

| Option           | Setting                                                                  |
| :----------      | :----------                                                              |
| Title            | `RokSprocket[span class="rt-title-tag"]Multiple Layouts & Themes[/span]` |
| Show Title       | Show                                                                     |
| Access           | Public                                                                   |
| Position         | maintop-a                                                                |
| Status           | Published                                                                |
| Content Provider | Simple                                                                   |
| Layout Mode      | Grids                                                                    |

### Simple Content Provider

The **Title** and **Description** fields in each item have been altered. A few examples of these article changes can be found below, excluding the **Image** and **Link** fields which will likely not work on your local copy as the links will be different.

#### Article 1

**Title**

~~~ .html
Grids
~~~

**Description**

~~~ .html
<span class="rt-grids-heading1"><a href="#">A content block layout <span class="hidden-tablet">with dynamic distribution</span>.</a></span><span class="rt-grids-heading2">Present with images, text overlays, content or with all. <span class="visible-large">Grids is configurable up to 10 columns and has one built-in theme.</span></span><span class="rt-grids-heading3"><a class="largemarginright" href="#"><i class="fa fa-quote-right fa-fw"></i> Read More</a> <a href="#"><i class="fa fa-cloud-download fa-fw"></i> Download</a></span>
~~~

#### Article 2

**Title**

~~~
Features
~~~

**Description**

~~~ .html
<span class="rt-grids-heading1"><a href="#"><span class="hidden-tablet">A layout for showcasing f</span><span class="visible-tablet">F</span>eatured content.</a></span><span class="rt-grids-heading2"><span>A slideshow layout, with various configurable themes<span class="visible-large"> for showcasing feature images with or without content</span>.</span></span><span class="rt-grids-heading3"><a href="#" class="largemarginright"><i class="fa fa-quote-right fa-fw"></i> Read More</a> <a href="#"><i class="fa fa-cloud-download fa-fw"></i> Download</a></span>
~~~

#### Article 3

The third item has a custom image in the **Image** field. This enables the grid item to show up as an image with the **Description** appearing as you move your mouse cursor over it.

**Title**

~~~ .html
Headlines
~~~

**Description**

~~~ .html
<span class="rt-grids-heading1"><a href="#">A content snippet or newsticker layout.</a></span><span class="rt-grids-heading2"><span class="hidden-tablet">Headlines is outfitted with a word counter to auto snippet text.</span></span><span class="rt-grids-heading3"><a href="#" class="largemarginright"><i class="fa fa-quote-right fa-fw"></i> Read More</a> <a href="#"><i class="fa fa-cloud-download fa-fw"></i> Download</a></span>
~~~

### Layout Options

![][demo3]

| Option                | Setting               |
| :----------           | :----------           |
| Theme                 | Basic                 |
| Display Limit         | ∞                     |
| Columns               | 3                     |
| Preview Length        | ∞                     |
| Strip HTML Tags       | No                    |
| Block Animation       | Fade, Scale, Rotate   |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

### Advanced

![][demo4]

| Option              | Setting                                                       |
| :----------         | :----------                                                   |
| Module Class Suffix | `fp-roksprocket-grids-maintop rt-title-center rt-large-title` |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
