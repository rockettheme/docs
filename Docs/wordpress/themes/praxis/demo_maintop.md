---
title: Praxis: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Main Top Section
-----

![][demo]

Here is the widget breakdown for the Main Top section:

* RokSprocket

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket]. In this particular instance, we elected to use the **Simple** content provider as it allows us to create custom items that do not require associated posts and/or pages.

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Tabs Position   | Top            |
| Display Limit   | ∞              |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | 0              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

**Simple Item Setup**

In this instance, we did not do a whole lot to customize the simple items. We did, however, add a custom description for each item. This description sets the images found in the strips. Below, you will find the text used in one of these items.

~~~ .html
<div class="gantry-width-40 gantry-width-block">
    <div class="gantry-width-spacer nomarginleft">
        <div class="sprocket-tabs-image"><img alt="image" src=
        "http://demo.rockettheme.com/wordpress-themes/wp_praxis/wp-content/rockettheme/rt_praxis_wp/frontpage/roksprocket-tabs/img1.jpg"></div>
    </div>
</div>
<div class="gantry-width-60 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="promo2 smallmarginbottom">Praxis</p>
        <p>Praxis is an elegant nexus of content enriching visual elements and
        powerful, underlying interactive and configurable features, to maximize
        the versatility and engagement of your site.</p>
        <div class="visible-large">
            <p>The Gantry Framework is the foundation of the template,
            providing the base for all major features and functions, such as
            the intuitive administrative interface.</p>
        </div><a class="readon largemargintop" href=
        "http://demo.rockettheme.com/wordpress-themes/wp_praxis/features/">Read
        More</a>
    </div>
</div>
<div class="clear"></div>
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-roksprocket-tabs fp-sidenav-spacing` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/
