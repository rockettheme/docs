---
title: Audacity: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Audacity Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/g4audacity:Audacity

---

Feature Section
-----

![Feature](assets/demo_3.jpeg)

:   1. **RokSprocket (Features)** [9%, 7%, se]
    2. **Text** [9%, 73%, se]

Here is the widget breakdown for the Feature section:

* [RokSprocket (Features)](#roksprocket-(features))
* [Gantry Divider](#gantry-divider)
* [Text](#text)

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate posts or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option | Setting                                                                                                                                             |
| :----- | :-------------------------------------------                                                                                                        |
| Title  | `<span>A responsive layout that auto-adapts to <span class="hidden-tablet">multiple </span><span class="visible-tablet">most </span>devices</span>` |
| Image  | Custom                                                                                                                                              |
| Link   | Custom                                                                                                                                              |

**Description**

~~~ .html
<p class="rt-title-tag">Flexible Structure</p><p>A responsive structure adapts automatically to the viewing device, whether desktop, tablet or mobile, and adjusts accordingly for a seamless and uniform experience.</p>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting        |
| :--------------- | :------------- |
| Display Limit    | ∞              |
| Theme            | Scroller       |
| Article Titles   | Show           |
| Article Text     | Show           |
| Preview Length   | ∞              |
| Strip HTML Tags  | No             |
| Arrow Navigation | Hide           |
| Pagination       | Show           |
| Animation        | Crossfade      |
| Autoplay         | Disable        |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

>> The **Scroller** theme is unique to Audacity and was created to give the RokSprocket mode a certain set of attributes that enables it to look the way it does in this theme. You can find more information about overriding themes [here](../../plugins/roksprocket/layout_modes.md#custom-layout-theme-overrides).

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

| Option            | Setting                                          |
| :---------------- | :----------------------------------------------- |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Custom Variations | `fp-roksprocket-scroller-feature`                |

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div>
    <img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-feature/img-01.jpg" alt="image" />
    <h2 class="title"><span><span class="hidden-tablet">An e</span><span class="visible-tablet">E</span>xtensive<span class="hidden-tablet"> array of</span> Color Chooser controls</span></h2>
    <p class="rt-title-tag">Customization</p>
    <p class="nomarginbottom"><span>Configure text and background colors<span class="hidden-tablet"> for the various sections</span>.</span></p>
    <a href="http://(your site url)/features-overview/" class="readon3">Read More</a>
</div>

<hr />

<div>
    <img src="http://(your site url)/wp-content/rockettheme/rt_audacity_wp/home/fp-feature/img-02.jpg" alt="image" />
    <h2 class="title"><span>Fresh Content <span class="hidden-tablet">Display </span>Layouts &amp; Themes</span></h2>
    <p class="rt-title-tag">RokSprocket</p>
    <p class="nomarginbottom"><span>New themes for RokSprocket Features<span class="hidden-tablet">: Scroller and Stories</span>.</span></p>
    <a href="http://(your site url)/features-overview/" class="readon3">Read More</a>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting        |
| :---------------- | :---------     |
| Custom Variations | `fp-feature-b` |

Leaving everything else at its default setting, select **Save**.
