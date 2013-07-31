---
title: Diametric: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Diametric Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/diametric:Diametric

---

Feature Section
-----
![][demo3]

Here's the widget breakdown for the Feature section:

* Text
* Gantry Divider
* RokSprocket

#### Text
The Text widget is a simple text widget with HTML script written into the body. You'll need to enter the following in the main text field.

~~~
<p class="paneltitle nomarginbottom">Diametric</p>
<p class="panelsubtitle nomarginbottom">Beautifully Styled</p>

<p class="largemargintop"><strong>Diametric</strong>, the November 2012 theme release, is a beautifully layered theme, with a distinct panel-based design, using the powerful <strong>ColorChooser</strong> system; with comprehensive RokPlugins styling.</p>

<img class="rt-floatright largepaddingleft" src="http://demo.rockettheme.com/wordpress/wp_diametric/wp-content/rockettheme/rt_diametric_wp/frontpage/fp-feature1.png" alt="Feature" width="270" height="247" />

<ul class="list-icon checkbox">
  <li><strong>ColorChooser: Ultimate Style Control</strong><br />
 <span>A comprehensive administrative interface, providing you with intuitive and versatile style control.</span>
  </li>
 <li><strong>RokSprocket: Flexible Content</strong><br />
  <span>A multi-purpose widget that supports tabbed, showcase, ticker and list content functionality.</span>
  </li>
</ul>

<a href="http://demo.rockettheme.com/wordpress/wp_diametric/theme-features/" class="readon"><span>More Information</span></a>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Custom Variations** option to `nomarginbottom nopaddingbottom nomargintop nopaddingtop`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### RokSprocket
The tabs content display located just under the main feature showcase is a RokSprocket widget. You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option | Setting |
|:-------|------:|
| Theme | Default |
| Tabs Position | Top |
| Display Limit | ∞ |
| Animation | Slide and Fade |
| Autoplay | Disable |
| Autoplay Delay | 5 |
| Image Resize | Disable |
| Preview Length | 0 |
| Strip HTML Tags | No |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Enter **Technical Support** in the **Title** field.
* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Enter `nomargintop nopaddingtop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo3]: assets/demo_4.jpeg