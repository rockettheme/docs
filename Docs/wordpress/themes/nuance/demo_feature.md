---
title: Nuance: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Feature Section
-----

![][demo]

:   1. **RokSprocket (Headlines)** [40%, 6%, se]
    2. **Text** [40%, 74%, se]

Here is the widget breakdown for the Feature section:

* RokSprocket (Headlines)
* Gantry Divider
* Text

#### RokSprocket (Headlines)

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Headlines** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting                                                                  |
| :---------- | :----------                                                              |
| Image       | None                                                                     |
| Link        | None                                                                     |

**Description**

~~~ .html
<span><i class="fa fa-cogs fa-fw"></i> Powered by LESS CSS to improve <span class="hidden-tablet">code </span>quality and <span class="hidden-tablet">development </span>efficiency<span class="visible-large"> via advanced functions</span></span>
~~~

Here is a look at the **Headlines Layout Options** for this widget.

| Option           | Setting     |
| :----------      | :---------- |
| Theme            | Default     |
| Display Limit    | ∞           |
| Label Text       |             |
| Preview Length   | 22          |
| Strip HTML Tags  | No          |
| Arrow Navigation | Show        |
| Animation        | Fade        |
| Autoplay         | Disable     |
| Autoplay Delay   | 5           |
| Image Resize     | Disable     |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Enter `fp-roksprocket-headlines` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<span class="rt-icon-left fa fa-file-text-o hidden-tablet"></span>
<span>
    <small>Made for</small><br />
    <a href="#">WordPress</a>
</span> 
<span class="rt-floatright"><i class="fa fa-signal"></i></span>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-feature-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[faq]: faq.md
