---
title: Lumiere: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Lumiere Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/lumiere:Lumiere

---

Utility Section
-----
![][demo]

: 1. **Utility - Text** [15%, 31%, se]
	2. **Utility - RokSprocket** [30%, 6%, se]

Here's the widget breakdown for the Utility section:

* Text
* Gantry Divider
* RokSprocket

#### Text
The text widget in this section has no title, and only contains one small amount of code in the text field.

~~~
<div class="rt-center">
    <p class="promo2 nomarginbottom">Top News of the Week.</p>
	<p class="promo3 nomarginbottom">Lumiere uses HTML5 video to create a dynamic and interactive user experience.</p>	
</div>                         
~~~

* Set the **Margin Variation** option to **No Margin Bottom**.
* Set the **Padding Variation** option to **No Padding Bottom**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket
This area of the front page is a **RokSprocket** widget using the **Mosaic** layout type. You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Mosaic Layout Options** for this widget.

| Option          |                      Setting |  
| :-------------- | ---------------------------: |  
| Theme           |                      Default |  
| Display Limit   |                            ∞ |  
| Columns         |                            3 |  
| Preview Length  |                           16 |  
| Strip HTML Tags |                          Yes |  
| Blocks per View |                            3 |  
| Article Details |         Hide author and date |  
| Block Animation |          Fade, Scale, Rotate |  
| Ordering        | Default, Title, Date, Random |  
| Image Resize    |                      Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you'll need to complete the following.

* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Set the **Corner Variation** option to **Basic**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_8.jpeg
[roksprocket]: ../../plugins/roksprocket/