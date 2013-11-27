---
title: Ximenia: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Ximenia Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/xmenia:Ximenia

---

Main Top Section
-----

Here's the widget breakdown for the Main Top section:

* RokSprocket
* Text
* Gantry Divider
* Gantry Social Buttons
* Text
* RokAjaxSearch

The Main Top section in the Ximenia demo adds a visual display of various theme features that puts images are the forefront of the front page's visual appeal.

#### RokSprocket

![][demo1]

You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

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

You can set the RokSprocket filters to include any category, specific posts, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Block Variation** option to **No Block**.
* Set the **Custom Variations** option to `nopaddingleft nopaddingright nopaddingbottom demo-sprocket-tabs`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text
![][demo5]

The first Text widget is a simple text widget with HTML script written into the body. You'll need to enter the following in the main text field.

~~~
<div class="rt-image rt-floatright">
  <img src="http://demo.rockettheme.com/wordpress/wp_ximenia/wp-content/rockettheme/rt_ximenia_wp/frontpage/general/maintop-a.jpg" width="336" height="212" alt="image" />
</div>

<p><em class="bold nobold."><strong>Ximenia</strong>, the February 2013 theme release, is an elegant, <strong>subtle</strong> and conservative <strong>design</strong>, with <strong>soft</strong> tones and shapes.</em></p>

<p><em class="bold nobold">The theme is perfect for any site that prefers a more <strong>moderate</strong> appearance. An assortment of plugins, such as <strong>RokSprocket</strong> have integrated styling.</em></p>

<a class="readon" href="#"><span>More Information</span></a>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Interview Creative Director`.
* Set the **Title Variation** option to **Title 3**.
* Set the **Block Variation** option to **No Block**.
* Set the **Custom Variations** option to `rt-largetitle`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Social Buttons

![][demo2]

The Gantry Social Buttons widget creates a floating set of social buttons on the left side of the page. Filling this out is fairly straightforward as you'll want to add your various social URLs to their respective fields before hitting **Save**.

#### Text

![][demo3]

The second Text widget in the section is made a lot like the first. You'll need to enter the following in the main text field.

~~~
<div class="smallpaddingtop">
  <div class="rt-image rt-floatleft medmarginbottom nomarginright">
    <img src="http://demo.rockettheme.com/wordpress/wp_ximenia/wp-content/rockettheme/rt_ximenia_wp/frontpage/general/sidebar-1.jpg" alt="image">
    <span class="cornertab"></span>
    <span class="image-description">Fusion with MegaMenu or SplitMenu menu options.</span>
    <span class="corner-symbol">&#043;</span>    
  </div>
  <div class="clear smallmarginbottom">&nbsp;</div>
  <div class="rt-image rt-floatleft medmarginbottom nomarginright">
    <img src="http://demo.rockettheme.com/wordpress/wp_ximenia/wp-content/rockettheme/rt_ximenia_wp/frontpage/general/sidebar-2.jpg" alt="image">
    <span class="cornertab"></span>
    <span class="image-description">Eight elegant, subtle and conservative styles.</span>
    <span class="corner-symbol">&#043;</span>    
  </div>
  <div class="clear smallmarginbottom">&nbsp;</div>
  <div class="rt-image rt-floatleft medmarginbottom nomarginright">
    <img src="http://demo.rockettheme.com/wordpress/wp_ximenia/wp-content/rockettheme/rt_ximenia_wp/frontpage/general/sidebar-3.jpg" alt="image">
    <span class="cornertab"></span>
    <span class="image-description">RokSprocket style integration.</span>
    <span class="corner-symbol">&#043;</span>    
  </div>
  <div class="clear"></div>
</div>

<a class="readon smallmargintop smallmarginleft" href="#"><span>See More</span></a>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Top Features`.
* Set the **Title Variation** option to **Title 2**.
* Set the **Custom Variations** option to `fronttabs`.
* Leaving everything else at its default setting, select **Save**.

#### RokAjaxSearch

![][demo4]

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you'll want to change to match the demo.

* Set the **Block Variation** option to **No Block**.
* Enter `nopaddingleft nopaddingtop nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_widget_3.jpeg
[demo2]: assets/demo_widget_4.jpeg
[demo3]: assets/demo_widget_5.jpeg
[demo4]: assets/demo_widget_6.jpeg
[demo5]: assets/demo_widget_15.jpg