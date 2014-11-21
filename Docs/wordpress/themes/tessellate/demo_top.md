---
title: Tessellate: Recreating the Demo - Top
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Top Section
-----

![][demo]

:   1. **Text** [60%, 16%, se]
    2. **RokSprocket** [13%, 22%, se]

Here is the widget breakdown for the Top section:

* Text
* Gantry Divider
* RokSprocket

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<span class="rt-top-social-icon rt-twitter">
	<span class="rt-icon-triangle-left">
		<a href="https://twitter.com/rockettheme">
			<i class="fa fa-twitter"></i>
		</a>
	</span>
</span>
<span class="rt-top-social-icon rt-facebook">
	<span class="rt-icon-triangle-up">
		<a href="https://www.facebook.com/RocketTheme">
			<i class="fa fa-facebook"></i>
		</a>
	</span>
</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-top` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting                     |
| :---------- | :----------                 |
| Title       | `It's Sharp &amp; Elegant!` |
| Image       | Custom                      |
| Link        | #                           |

**Description**

~~~ .html
A sharp visual design complemented by a subtle animated header.
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting         |
| :----------      | :----------     |
| Display Limit    | ∞               |
| Theme            | Slideshow       |
| Article Titles   | Show            |
| Article Text     | Show            |
| Preview Length   | ∞               |
| Strip HTML Tags  | Yes             |
| Arrow Navigation | Hide            |
| Pagination       | Show            |
| Animation        | Bottom to Top   |
| Autoplay         | Disable         |
| Autoplay Delay   | 5               |
| Image Resize     | Disable         |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Widget Variations** to **No Padding All, No Margin All**.
* Enter `fp-roksprocket-features-top` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_2.jpeg
