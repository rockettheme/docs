---
title: Ricochet: Recreating the Demo - FullWidth
description: Your Guide to Recreating Elements of the Ricochet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ricochet:Ricochet

---

FullWidth Section
-----

![FullWidth](assets/demo_7.jpeg)

Here is the widget breakdown for the FullWidth section:

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option |                                                            Setting                                                            |
| :----- | :---------------------------------------------------------------------------------------------------------------------------- |
| Title  | `<div class="wow bounceInDown">  <span>"Sleek Design and Easy Customization Made this the Perfect Theme for Me"</span></div>` |
| Image  | Custom                                                                                                                        |
| Link   | None                                                                                                                          |

**Description**

~~~ .html
<div class="rt-slideshow2-content wow zoomIn">
    <p>I struggled for a long time to find the right design and functionality
    for my portfolio site. Ricochet was exactly what I was looking for to get my
    site up and running quickly and easily. I love it!</p>
</div>

<div class="rt-slideshow2-author wow bounceInUp" data-wow-delay="1s">
    <img alt="image" src=
    "http://demo.rockettheme.com/live/wordpress/ricochet/wp-content/rockettheme/rt_ricochet_wp/home/fp-fullwidth/img-author-01.jpg">
    <span>Martin McDouglas</span>
</div>
~~~

Here is a look at the **Features Layout Options** for this widget.

|      Option      |      Setting      |
| :--------------- | :---------------- |
| Display Limit    | ∞                 |
| Theme            | Slideshow Style 2 |
| Article Titles   | Show              |
| Article Text     | Show              |
| Preview Length   | ∞                 |
| Strip HTML Tags  | No                |
| Arrow Navigation | Show              |
| Pagination       | Hide              |
| Animation        | Crossfade         |
| Autoplay         | Disable           |
| Autoplay Delay   | 5                 |
| Image Resize     | Disable           |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-roksprocket-slideshow fp-preset-images` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.
