---
title: Hexeris: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Hexeris Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hexeris:Hexeris

---

Extension
-----

Here is the widget breakdown for the Extension section:

* RokSprocket
* Gantry Divider
* Text
* Gantry Divider
* RokSprocket

#### RokSprocket

![][demo]

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

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

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Set the **Box Variation** option to **Box 3**.
* Set the **Padding Variation** option to **No Padding All**.
* Enter `fp-roksprocket-tabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

![][demo2]

The Text widget in this section is pretty straightforward. You will need to enter the following in the main text field.

~~~
<div class="gantry-width-20 gantry-width-block">
    <span class="box2 rt-med-icon">
		<span class="rokicon-profile2"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Quick Install.</h5>
		<p class="nomarginbottom">Replicate the demo easily with a custom WordPress installation package.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<div class="gantry-width-20 gantry-width-block">
	<span class="box1 rt-med-icon">
		<span class="rokicon-message"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Forum Guide.</h5>
		<p class="nomarginbottom">A forum tutorial on replicating the demo frontpage is also available.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<div class="gantry-width-20 gantry-width-block">
	<span class="box4 rt-med-icon">
		<span class="rokicon-alarm-clock"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Sample Images.</h5>
		<p class="nomarginbottom">Due to copyright reasons, demo images are replaced with sample versions.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<a class="readon" href="http://demo.rockettheme.com/wordpress/wp_hexeris/features/">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Replica [span class=\"rt-subtitle\"]RocketLauncher[/span]`.
* Switch the **Box Variation** option to **Box 3**.
* Enter `hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

### RokSprocket

![][demo3]

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview |  Enable |  
| Display Limit       |       ∞ |  
| Preview Length      |      20 |  
| Strip HTML Tags     |     Yes |  
| Previews Per Page   |       3 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            |       5 |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Gantry Extras`
* Set the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_6.jpeg
[demo3]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/
