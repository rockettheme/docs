---
title: Ximenia: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ximenia:Ximenia

---

Sidebar Section
-----
The Sidebar section in our demo points out some of the more compelling features that went into our theme. It includes two text widgets and a single RokSprocket Tabs widget.

Here is the widget breakdown for the Sidebar section:

* Text
* RokSprocket
* Text

#### Text
![][demo1]

The first text widget in this section is titled **More Features** and has the following in the main text field.

~~~
<ul class="menu">
<li class="item-180"><span class="separator">Multiple Styles</span>
</li><li class="item-181"><span class="separator">Versatile Layout</span>
</li><li class="item-182"><span class="separator">Widget Variants</span>
</li><li class="item-183"><span class="separator">Powerful Menu</span>
</li><li class="item-184"><span class="separator">Beautiful Content</span>
</li><li class="item-186"><span class="separator">RokSprocket Styled</span>
</li><li class="item-187"><span class="separator">Logo Picker</span>
</li><li class="item-188"><span class="separator">WordPress Styled</span>
</li></ul>
~~~

* Set the **Title** to `More Features`.
* Set the **Title Variation** option to **Title 2**.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket
![][demo2]

The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Tabs widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

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

* Set the **Title** to `Ximenia Guide`
* Set the **Title Variation** option to **Title 2**.
* Set the **Custom Variations** to `titletabs`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text
![][demo3]

The second text widget in this section is titled **Advertisement** and has the following in the main text field.

~~~
<a href="http://www.rockettheme.com/" target="_blank">
  <span class="rt-image rt-floatleft smallmargintop">
    <img width="190" height="150" alt="RocketTheme" src="http://demo.rockettheme.com/wordpress-themes/wp_ximenia/wp-content/rockettheme/rt_ximenia_wp/frontpage/general/rockettheme.jpg" />
  </span>
</a>
~~~

* Set the **Title** to `Advertisement`.
* Set the **Title Variation** option to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_widget_7.jpeg
[demo2]: assets/demo_widget_8.jpeg
[demo3]: assets/demo_widget_9.jpeg
[roksprocket]: ../../plugins/roksprocket
