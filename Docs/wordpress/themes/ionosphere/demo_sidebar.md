---
title: Ionosphere: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Ionosphere Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ionosphere:Ionosphere

---

Sidebar Section
-----
The Sidebar section in our demo points out some of the more compelling features that went into our theme. It includes two text widgets sand a single RokSprocket Tabs widget.

Here's the widget breakdown for the Sidebar section:

* RokAjaxSearch
* Text
* RokSprocket

#### RokAjaxSearch
![][demo1]

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you'll want to change to match the demo.

* Set the **Box Variation** option to **Box 2**.
* Enter `Search our Site` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

#### Text
![][demo2]

The text widget in this section is titled **Two Configurable Menus** and has the following in the main text field.

~~~
<p><strong>Fusion with MegaMenu</strong>, is a javsacript enhanced, <strong>CSS</strong> powered dropdown menu, with features such as mutli-columns.</p>

<p><strong>Triple Level SplitMenu</strong> is a static menu that displays its items in three separate <strong>tiers</strong>, horizontal and vertical (Sidebar).</p>
~~~

* Set the **Title** to `Two Configurable Menus`.
* Set the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket
![][demo3]

The tabs located in the sidebar section of the page is a RokSprocket widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget. 

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
| Default Icon    |           None |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Custom Variations** to `nopaddingleft nopaddingright nomarginbottom`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo1]: assets/demo_6.jpeg
[demo2]: assets/demo_7.jpeg
[demo3]: assets/demo_9.jpeg