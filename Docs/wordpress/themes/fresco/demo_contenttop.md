---
title: Fresco: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Fresco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/fresco:Fresco

---

Content Top Section
-----

Here is the widget breakdown for the Content Top section:

* Text
* Gantry Divider
* RokSprocket

#### Text

![][demo4]

The Text widget in this section is titled **Unique Variations Sophisticated Design** and has the following in the main text field.

~~~
<p><strong>Fresco</strong>, the January 2013 WordPress Theme Club release, is a visually <strong>rich</strong> theme, bringing life to your content through <strong>stunning</strong> and intricate graphics, each customised for specific <strong>themes</strong>.</p>

<a class="readon" href="http://demo.rockettheme.com/wordpress/wp_fresco/preset-styles/"><span>See More</span></a>
~~~

* Set the **Title** to `Unique Variations Sophisticated Design`.
* Set the **Custom Variations** field to `bg1 largeheader`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket

![][demo5]

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option          |        Setting |  
| :-------------- | -------------: |  
| Theme           |        Default |  
| Tabs Position   |            Top |  
| Display Limit   |              ∞ |  
| Animation       | Slide and Fade |  
| Autoplay        |        Disable |  
| Autoplay Delay  |              5 |  
| Image Resize    |        Disable |  
| Preview Length  |              0 |  
| Strip HTML Tags |             No |  
| Default Link    |           None |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Set the **Custom Variations** option to `fp-rstabs`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo4]: assets/demo_4.jpeg
[demo5]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket
