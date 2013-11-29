---
title: Cerulean: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Cerulean Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cerulean:Cerulean

---

Sidebar Section
-----

Here is the widget breakdown for the Utility section:

* RokSprocket
* Text

### RokSprocket

![][demo]

The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | :------ |  
| Theme               | Default |  
| Display Limit       | ∞       |  
| Collapsible Preview | Enable  |  
| Preview Length      | 20      |  
| Strip HTML Tags     | Yes     |  
| Previews Per Page   | 3       |  
| Arrow Navigation    | Show    |  
| Pagination          | Show    |  
| Autoplay            | Disable |  
| Image Resize        | Disable |  
| Default Link        | None    |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Gantry Extras`.
* Select your RokSprocket widget in the **Choose Widget** field.
* Set the **Box Variation** field to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

### Text

![][demo2]

You will need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~ .html
[solid-separator]

[speaker img="http://demo.rockettheme.com/wordpress/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/sidebar/img1.jpg" name="Mary Watson" position="Software Architech" info="Gantry offers powerful under the hood features and extras." link="#"]View Full Bio[/speaker]

[solid-separator]

<div class="hidden-tablet">
[speaker img="http://demo.rockettheme.com/wordpress/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/sidebar/img2.jpg" name="Peter Malkay" position="Design Visionary" info="Beautifully integrated typography to add life to your content." link="#"]View Full Bio[/speaker]

[solid-separator]
</div>

<div class="visible-large">
[speaker img="http://demo.rockettheme.com/wordpress/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/sidebar/img3.jpg" name="Franklin Johnston" position="CEO &amp; Founder" info="Integrated styling for K2 is also provided, but not demoed." link="#"]View Full Bio[/speaker]
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `[span class="hidden-tablet"]Guest [/span]Speakers [small]Speakers Table[/small]` as the **Title** of the widget.
* Set the **Box Variation** option to **Box 2**.
* Enter `fp-sidebar-a2 hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket