---
title: Iridescent: Recreating the Demo - FP RokSprocket Features - Showcase
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

FP RokSprocket Features - Showcase
-----

![][demo]

The **RokSprocket Features** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider, allowing us to create custom content independent of full articles. The **Title**, **Description**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** and **Link** fields which will likely not work on your local copy as the links will be different.

### Details

![][demo2]

|      Option      |               Setting                |
| :--------------- | :----------------------------------- |
| Title            | `FP RokSprocket Features - Showcase` |
| Show Title       | Hide                                 |
| Access           | Public                               |
| Position         | showcase-a                           |
| Status           | Published                            |
| Content Provider | Simple                               |
| Type             | Features                             |

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<span class="wow fadeInDown">RokSprocket</span>
~~~

**Description**

~~~ .html
<span class="wow fadeInUp" data-wow-delay="0.5s"><span class=
"rt-lead">RokSprocket is designed to give you an incredible level of control
over how you present your content.</span><br>
<span>One of RokSprocket's greatest assets is its custom administrator, which
provides unprecedented control with extensive configuration options.</span><br>
<span class="visible-desktop">The module is an expandable content display
platform, with a diverse selection of prebuilt layout modes, that offer
different structural and functional types to choose from.</span> <span class=
"visible-large"><br>
The extension supports several providers, such as Joomla and its very own
Simple provider, which allows for content to be created and controlled entirely
within RokSprocket.</span></span>
~~~

#### Article 2

**Title**

~~~ .txt
RokBooster
~~~

**Description**

~~~ .html
<span class="rt-lead">RokBooster is an advanced performance plugin, that will
compress and collate CSS and JavaScript.</span><br>
<span>RokBooster also provides data URL conversion for Fonts as well as inline
or background images, which converts files to inline data.</span><br>
<span class="visible-desktop">It reduces the HTTP calls count as well as the
data load size, dramatically increasing site speed.</span> <span class=
"visible-large"><br>
RokBooster provides an extensive array of control options, to set all the
compression variables through one interface, providing individual enabling and
configuration.</span>
~~~

#### Article 3

**Title**

~~~ .txt
RokBox
~~~

**Description**

~~~ .html
<span class="rt-lead">RokBox is a fully responsive, multi-media modal input
"pop-up" plug-in for the Joomla CMS.</span><br>
<span>The essence of RokBox is data-sets placed in hyperlinks. Inside the
hyperlink, data-sets generate JavaScript which produce a stunning modal canvas
<span class="rt-displayinline"><span class="hidden-phone rt-displayinline">for
a variety of media</span></span>.</span><br>
<span class="visible-desktop">RokBox has a number of different data-sets, each
with a specific meaning and all optional with the exception of "data-rokbox"
which is used to activate the RokBox plugin.</span><span class=
"visible-large"><br>
RokBox also has a built-in editor button that generates RokBox snippets for
your Joomla Content, whether HTML or WYSIWYG. Available for Articles and Custom
HTML Modules.</span>
~~~

### Layout Options

![][demo3]

|         Option        |        Setting        |
| :-------------------- | :-------------------- |
| Display Limit         | 3                     |
| Theme                 | Showcase              |
| Article Titles        | Show                  |
| Article Text          | Show                  |
| Preview Length        | ∞                     |
| Strip HTML Tags       | No                    |
| Arrow Navigation      | Show                  |
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

|        Option       |              Setting               |
| :------------------ | :--------------------------------- |
| Module Class Suffix | `fp-roksprocket-features-showcase` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
