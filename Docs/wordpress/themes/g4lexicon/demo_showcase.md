---
title: Lexicon: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Lexicon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/lexicon:Lexicon

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the **Link** option is left at default or **None** setting. The **Icon** field contains the URL of an image file. You will find the settings used in one of these items below.

**Tab Label**

~~~ .html
Contemporary
~~~

**Description**

~~~ .html
<img alt="image" class="sprocket-tabs-image" src=
"http://demo.rockettheme.com/live/wordpress/lexicon/wp-content/rockettheme/rt_lexicon_wp/home/fp-roksprocket-tabs-showcase/img-01.jpg">
<span class="sprocket-tabs-desc rt-center"><span class="rt-text-large">Join the
Adventure</span> <span class="rt-title-tag">Buy Lexicon for You and Your
Clients</span> <a class="readon" href=
"http://www.rockettheme.com/wordpress-themes/lexicon">Purchase Now</a></span>
~~~

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting       |
| :-------------- | :------------ |
| Theme           | Default       |
| Display Limit   | ∞             |
| Tabs Position   | Left          |
| Animation       | Fade          |
| Autoplay        | Disable       |
| Autoplay Delay  | 5             |
| Image Resize    | Disable       |
| Preview Length  | ∞             |
| Strip HTML Tags | No            |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-roksprocket-tabs-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_2.jpeg
