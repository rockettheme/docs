---
title: Praxis: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

* RokSprocket

### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/). In this particular instance, we elected to use the **Simple** content provider as it allows us to create custom items that do not require associated posts and/or pages.

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |  
| :---------------- | :----------- |  
| Display Limit     | ∞            |  
| Theme             | Default      |  
| Preview Length    | 20           |  
| Strip HTML Tags   | No           |  
| Previews Per Page | 8            |  
| Items Per Row     | 4            |  
| Arrow Navigation  | Show         |  
| Pagination        | Hide         |  
| Animation         | Fade Delayed |  
| Autoplay          | Disable      |  
| Autoplay Delay    | 5            |  
| Image Resize      | Disable      |  
| Default Title     | None         |  
| Default Link      | None         |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

**Simple Item Setup**

In this instance, we did not do a whole lot to customize the simple items. We did, however, add a custom description for each item. This description sets the images found in the strips. Below, you will find the text used in one of these items.

~~~ .html
<span class="sprocket-strips-image">	<span class="strips-image-shadow"></span>	<img src="http://demo.rockettheme.com/wordpress/wp_praxis/wp-content/rockettheme/rt_praxis_wp/frontpage/roksprocket-strips/img8.jpg" alt="image" /></span>
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Strips widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/
