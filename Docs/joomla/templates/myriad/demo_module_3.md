
---
title: Myriad: Recreating the Demo - FP RokSprocket Slideshow - FirstFullWidth
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

FP RokSprocket Slideshow - FirstFullWidth
-----

![][demo]

The **RokSprocket Features** module used here is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider, allowing us to create custom content independent of full articles. The **Title**, **Description**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** fields which will likely not work on your local copy as the links will be different.

>> NOTE: If you are using the the RocketLauncher, there are some special instructions concerning the handling of the preset images for this module. If you notice your images aren't changing as expected, or if you would like more information on how this was set up, you can find it [here](demo.md#roksprocket-and-rocketlauncher-settings).

### Details

![][demo2]

|      Option      |                   Setting                   |
| :--------------- | :------------------------------------------ |
| Title            | `FP RokSprocket Slideshow - FirstFullWidth` |
| Show Title       | Hide                                        |
| Access           | Public                                      |
| Position         | firstfullwidth                              |
| Status           | Published                                   |
| Content Provider | Simple                                      |
| Type             | Features                                    |

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<span class="wow fadeInDown">RokSprocket</span>
~~~

**Description**

~~~ .html
<span class="wow fadeInUp">A powerful, content switchblade extension with multiple default layout modes and various theme variants, alongside its custom administrative interface. RokSprocket therefore, provides a quick and easy solution in delivering sophisticated content structures, with efficiency and style.</span>
~~~

#### Article 2

**Title**

~~~
RokBooster
~~~

**Description**

~~~ .html
RokBooster is an advanced performance plugin, that will compress and collate your CSS and JavaScript files; alongside data URL conversion for Fonts as well as inline or background images, which converts files to inline data; reducing HTTP calls data load size, increasing site speed.
~~~

#### Article 3

**Title**

~~~ .html
RokAjaxSearch
~~~

**Description**

~~~ .html
RokAjaxSearch displays search results live via AJAX. The results automatically appear as you type your search inquiry. The results dropdown includes multi-page navigation as well as extensive configuration options. RokAjaxSearch is shown on the demo's Blog page.
~~~

### Layout Options

![][demo3]

|         Option        |        Setting        |
| :-------------------- | :-------------------- |
| Display Limit         | ∞                     |
| Theme                 | Slideshow Style 3     |
| Article Titles        | Show                  |
| Article Text          | Show                  |
| Preview Length        | ∞                     |
| Strip HTML Tags       | No                    |
| Arrow Navigation      | Hide                  |
| Pagination            | Show                  |
| Animation             | Bottom to Top         |
| Autoplay              | Disable               |
| Autoplay Delay        | 5                     |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

### Advanced

![][demo4]

|        Option       |                                 Setting                                 |
| :------------------ | :---------------------------------------------------------------------- |
| Module Class Suffix | `fp-roksprocket-slideshow-firstfullwidth hidden-phone fp-preset-images` |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
