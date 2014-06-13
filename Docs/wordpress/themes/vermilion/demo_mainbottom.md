---
title: Vermilion: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Main Bottom Section
-----

![][demo]

Here is the widget breakdown for the Main Bottom section:

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom headline text without having to create separate articles or pages to do so. Here are the details of one of the items in the **Featured Article List**.

| Option      | Setting                              |
| :---------- | :----------                          |
| Title       | `<span class="fa fa-trophy"></span>` |
| Image       | Custom                               |
| Link        | #                                    |

**Description**

~~~ .html
<span>RokAjaxSearch is a configurable search widget<span class="hidden-tablet"> that uses AJAX to load results in real time via a styled, paged popup. It can be set to local or Google search, inclusive of Web, image, video and blog</span>.</span>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting     |
| :----------      | :---------- |
| Display Limit    | ∞           |
| Theme            | Slideshow   |
| Article Titles   | Show        |
| Article Text     | Show        |
| Preview Length   | ∞           |
| Strip HTML Tags  | No          |
| Arrow Navigation | Hide        |
| Pagination       | Show        |
| Animation        | Randomize   |
| Autoplay         | Disable     |
| Autoplay Delay   | 5           |
| Image Resize     | Disable     |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `fp-mainbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_8.jpeg
[roksprocket]: ../../plugins/roksprocket/
