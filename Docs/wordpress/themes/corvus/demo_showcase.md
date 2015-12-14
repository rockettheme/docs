---
title: Corvus: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Showcase Section
-----

![][demo]

:   1. **RokSprocket** [10%, 5%, se]
    2. **Text** [69%, 5%, se]

Here is the widget breakdown for the Showcase section:

* RokSprocket
* Text

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/). In this particular instance, we elected to use the **WordPress** content provider.

Here is a look at the **Strips Layout Options** for this widget.

| Option                   | Setting        |  
| :----------------------- | :------------- |  
| Display Limit            | ∞              |  
| Theme                    | Default        |  
| Preview Length           | 20             |  
| Strip HTML Tags          | No             |  
| Article Details          | Show Only Date |  
| Previews Per Page        | 3              |  
| Article Details Position | Outside        |  
| Items Per Row            | 3              |  
| Arrow Navigation         | Hide           |  
| Pagination               | Hide           |  
| Animation                | Randomize      |  
| Autoplay                 | Disable        |  
| Autoplay Delay           | 5              |  
| Image Resize             | Disable        |  
| Default Title            | None           |  
| Default Link             | None           |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

**Item Setup**

In this instance, we did not do a whole lot to customize the simple items. We did, however, add a custom description for each item. This description sets the images found in the strips. Below, you will find the text used in one of these items.

~~~ .html
<span class="hidden-tablet">Powered by </span>RokSprocket
~~~

Additionally, we used icons to add a visual element to each item on mouseover. In the **Multiple Layouts** item, for example, we used `icon-film` in the **Icon** field.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Strips widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p>A feature of Corvus is the <strong>expanded</strong> widget. Any widget that has the <strong>expanded</strong> widget custom variation applied to it, will expand and contract based on window <strong>scroll</strong>. The feature is best applied in the <strong>showcase</strong> position, with a full width widget, as demoed currently. The <strong>overlap</strong> effect below, is via CSS and can be customized through the <a href="http://docs.gantry.org/wordpress/tutorials/custom_stylesheet.md">custom stylesheet process</a>, depending on your content needs.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Scroll Triggered Expanded Widget`.
* Switch the **Align Variation** option to **RT-Center**.
* Enter `expanded` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/
