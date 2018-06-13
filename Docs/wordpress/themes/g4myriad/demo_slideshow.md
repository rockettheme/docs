---
title: Myriad: Recreating the Demo - Slideshow
description: Your Guide to Recreating Elements of the Myriad Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

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

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option |                   Setting                    |
| :----- | :------------------------------------------- |
| Title  | `<span class="wow fadeInDown">Focus!</span>` |
| Image  | Custom                                       |
| Link   | None                                         |

**Description**

~~~ .html
<span class="wow fadeInUp" data-wow-delay="0.5s">Photo Centric Theme</span>
~~~

Here is a look at the **Features Layout Options** for this widget.

|      Option      |    Setting     |
| :--------------- | :------------- |
| Display Limit    | ∞              |
| Theme            | Full Slideshow |
| Article Titles   | Show           |
| Article Text     | Show           |
| Preview Length   | ∞              |
| Strip HTML Tags  | No             |
| Arrow Navigation | Show           |
| Pagination       | Hide           |
| Animation        | Crossfade      |
| Autoplay         | Disable        |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

>> The **Full Slideshow** theme is unique to Myriad and was created to give the RokSprocket mode a certain set of attributes that enables it to look the way it does in this template. You can find more information about overriding themes [here](../../plugins/roksprocket/layout_modes.md#custom-layout-theme-overrides).

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-slideshow fp-preset-images` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.
