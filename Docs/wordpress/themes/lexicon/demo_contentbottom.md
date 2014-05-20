---
title: Lexicon: Recreating the Demo - Content Bottom
description: Your Guide to Recreating Elements of the Lexicon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/lexicon:Lexicon

---

Content Bottom Section
-----

![][demo]

:    1. **RokSprocket (Headlines)** [15%, 8%, se]
     2. **Text** [30%, 8%, se]

Here is the widget breakdown for the Content Bottom section:

* RokSprocket (Headlines)
* Text


#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Headlines** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

Here is a look at the **Headlines Layout Options** for this widget.

| Option           | Setting        |
| :--------------- | :------------- |
| Theme            | Default        |
| Display Limit    | ∞              |
| Label Text       |                |
| Preview Length   | 12             |
| Arrow Navigation | Show           |
| Animation        | Slide and Fade |
| Autoplay         | Disable        |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Set the **Widget Variations** to **Box 4**.
* Enter `fp-roksprocket-headlines` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p class="rt-text-medium"><em>Lexicon is centered around a flat design approach, spruced by professional and engaging color schemes to create presence for site content without distracting from it. <span class="hidden-tablet">Ideal for showcasing product details in a vibrant but elegant fashion.</span></em></p>

<br />

<div class="gantry-row">
  <div class="gantry-width-10 hidden-tablet">
    <div class="gantry-width-spacer">
      <img class="rt-rounded" src="http://demo.rockettheme.com/live/wordpress/lexicon/wp-content/rockettheme/rt_lexicon_wp/home/fp-content-bottom-01/img-01.jpg" alt="image" />
    </div>
  </div>

  <div class="gantry-width-50">
    <div class="gantry-width-spacer">
      <h4 class="smallmarginbottom">Responsive Layout</h4>
      <p><em>Automatic adaptation<span class="hidden-tablet">  to varying devices</span></em></p>
    </div>
  </div>

  <div class="gantry-width-40">
    <div class="gantry-width-spacer gantry-right">
      <p class="medmargintop"><a class="readon" href="http://www.rockettheme.com/wordpress-themes/lexicon">Download<span class="hidden-tablet"> Lexicon</span></a></p>
    </div>
  </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-content-bottom-01` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/
