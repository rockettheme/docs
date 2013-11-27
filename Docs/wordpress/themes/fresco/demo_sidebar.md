---
title: Ximenia: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ximenia:Ximenia

---

Sidebar Section
-----
The Sidebar section in our demo points out some of the more compelling features that went into our theme. It includes two text widgets sand a single RokSprocket Tabs widget.

Here's the widget breakdown for the Sidebar section:

* Text
* Text
* RokSprocket
* Text

#### Text

![][demo1]

The first text widget in this section is titled **Style Control** and has the following in the main text field.

~~~
<p>There are 3 background levels: low, med &amp; high; so you can flip between a rich or subtle style.</p>

<a class="readon" href="http://demo.rockettheme.com/wordpress/wp_fresco/preset-styles/"><span>See More</span></a>
~~~

* Set the **Title** to `Style Control`.
* Set the **Custom Variations** option to `bg2 mediumheader`.
* Leaving everything else at its default setting, select **Save**.

#### Text

![][demo2]

The next text widget in this section is titled **Top Features** and has the following in the main text field.

~~~
<div>
  <h4 class="nomarginbottom">Beautifully Styled</h4>
  <p class="nomarginbottom">Ten stunning preset styles and a selection of elegant, stylistic widget variations.</p>
</div>

<div>
  <h4 class="nomarginbottom medmargintop">Fusion</h4>
  <p>A Mootools-enhanced CSS dropdown menu system, with multi-column support.</p>
</div>

<a href="http://demo.rockettheme.com/wordpress/wp_fresco/theme-features/" class="readon"><span>See More</span></a>
~~~

* Set the **Title** to `Top Features`.
* Set the **Custom Variations** option to `bg3 mediumheader`.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket

![][demo3]

The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview |  Enable |  
| Display Limit       |       ∞ |  
| Preview Length      |      15 |  
| Strip HTML Tags     |      No |  
| Previews Per Page   |       3 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            | Disable |  
| Autoplay Delay      |       5 |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Gantry Extras`
* Set the **Custom Variations** to `bg4`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text

![][demo4]

The last text widget in this section has no title and has the following in the main text field.

~~~
<strong>RocketLauncher</strong> is a custom WordPress package that will <a href="http://demo.rockettheme.com/wordpress/wp_fresco/tutorials/installation/">install</a> the <strong>demo</strong> onto your site. Demo images are replaced with <strong>sample images</strong> to avoid any copyright issue.
~~~

* Set the **Margin Variation** to **No Margin Bottom**.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_7.jpeg
[demo2]: assets/demo_8.jpeg
[demo3]: assets/demo_9.jpeg
[demo4]: assets/demo_12.jpeg
[roksprocket]: ../../plugins/roksprocket