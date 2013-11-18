---
title: Leviathan: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Leviathan Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/leviathan:Leviathan

---

Showcase Section
-----
![][demo]

:   1. **Showcase - RokAjaxSearch** [25%, 6%, se]
	2. **Showcase - Text** [45%, 6%, se]
	3. **Showcase - RokSprocket** [25%, 29%, se]

Here's the widget breakdown for the Showcase section:

* RokAjaxSearch
* Text
* Gantry Divider
* RokSprocket

#### RokAjaxSearch
The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you'll want to change to match the demo.

* Enter `Site Search` in the **Title** field.
* Set the **Custom Variations** field to `fp-rokajaxsearch icon-search nomarginbottom nopaddingbottom hidden-tablet hidden-phone nomarginright nomarginleft`.
* Leaving everything else at its default setting, select **Save**.

#### Text
The text widget in this section is titled **Top Feature(s)** and has the following in the main text field.

~~~
<div class="visible-large">
    <div class="gantry-width-25 gantry-width-block">
    <span class="rt-image"><img alt="image" src="http://demo.rockettheme.com/wordpress/wp_leviathan/wp-content/rockettheme/rt_leviathan_wp/frontpage/sidebar-a/img1.jpg" /></span>
  </div>

  <div class="gantry-width-75 gantry-width-block rt-condensed-text">
    <div class="largemarginleft">
      <h4 class="normalfont nomargintop nomarginbottom">Responsive Layout</h4>
      <small>Multiple device support, for mobile, tablet or desktop displays, that are automatically adjusted to.</small>
    </div>
  </div>
  <div class="clear"></div> 
  <div class="gantry-width-25 gantry-width-block largemargintop">
    <span class="rt-image"><img alt="image" src="http://demo.rockettheme.com/wordpress/wp_leviathan/wp-content/rockettheme/rt_leviathan_wp/frontpage/sidebar-a/img2.jpg" /></span>
  </div>

  <div class="gantry-width-75 gantry-width-block rt-condensed-text largemargintop">
    <div class="largemarginleft">
      <h4 class="normalfont nomargintop nomarginbottom">Integrated Plugins</h4>
      <small>Template specific styling for several plugins such as RokSprocket and RokAjaxSearch.</small>
    </div>
  </div>  

</div>

<div class="hidden-phone hidden-tablet hidden-large">
  <div class="gantry-width-30 gantry-width-block">
    <span class="rt-image"><img alt="image" src="http://demo.rockettheme.com/wordpress/wp_leviathan/wp-content/rockettheme/rt_leviathan_wp/frontpage/sidebar-a/img1.jpg" /></span>
  </div>

  <div class="gantry-width-70 gantry-width-block rt-condensed-text">
    <div class="largemarginleft">
      <h4 class="normalfont nomargintop nomarginbottom">Responsive</h4>
      <small>Multiple device support, for mobile, tablet or desktop displays.</small>
    </div>
  </div>  
</div>                            
~~~

* Set the **Title** to `[span class=\"hidden-large\"]Top Feature[/span][span class=\"visible-large\"]Top Features[/span]`.
* Set the **Custom Variations** field to `fp-topfeature icon-star hidden-tablet hidden-phone smallpaddingtop nopaddingbottom medpaddingleft medpaddingright smallmarginleft smallmarginright`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### RokSprocket
The main feature showcase located near the top of the demo is a RokSprocket widget. You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Features Layout Options** for this widget.

| Option           |   Setting |  
| :--------------- | --------: |  
| Display Limit    |         ∞ |  
| Theme            |  Showcase |  
| Article Titles   |      Show |  
| Article Text     |      Show |  
| Preview Length   |         ∞ |  
| Strip HTML Tags  |        No |  
| Arrow Navigation |      Show |  
| Pagination       |      Show |  
| Animation        | Crossfade |  
| Autoplay         |   Disable |  
| Autoplay Delay   |         5 |  
| Image Resize     |   Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Custom Variations** field to `nomarginall nopaddingall`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_showcase.jpeg
[roksprocket]: ../../plugins/roksprocket/