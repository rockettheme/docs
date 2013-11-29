---
title: Metropolis: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Metropolis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/metropolis:Metropolis

---

Sidebar Section
-----
![][demo27]

Here is the widget breakdown for the Sidebar section:

* RokSprocket
* Text
* Gantry Divider
* RokAjaxSearch
* Text
* Text

### RokSprocket
The **Help and Tips** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview |  Enable |  
| Display Limit       |       ∞ |  
| Preview Length      |      17 |  
| Strip HTML Tags     |     Yes |  
| Previews Per Page   |       5 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            |       5 |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Help &amp; Tips`
* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Set the Box Variation field to **Box 4**.
* Enter `icon-book` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

### Text
The first Text widget in this section is titled **Our Users** and has the following in the main text field. This section is directly created, and you can replace the image sources with images from your actual user base.

~~~
<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user1.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user2.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user3.jpg" alt="image">
    </span>
  </div>
</div>

<div class="clear"></div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user4.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user5.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="http://yoursite.com/wp-content/rockettheme/rt_metropolis_wp/frontpage/sidebar/user6.jpg" alt="image">
    </span>
  </div>
</div>

<div class="clear"></div>
~~~

### RokAjaxSearch
The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Set the **Title** to `Site Search`
* Set the **Corner Variation** option to **Basic**.
* Enter `rt-dark-block nomarginleft nomarginright nomarginbottom nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

### Text
The next Text widget has no title. The following is entered in the main text field.

~~~
<a href="http://www.yoursite.com/preset-styles/" class="rt-block-link"></a>
<div class="rt-center">
    <div class="module-title">
        <h2 class="title nomarginbottom visible-large">Preset Styles</h2>
        <h2 class="title nomarginbottom hidden-large">Styles</h2>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Box Variation** option to **Box 3**.
* Enter `icon-heart icon-large` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

### Text
The third Text widget of the section highlights the RocketLauncher option. The following appears in the main text field.

~~~
<div class="rt-center">
    <div class="module-title">
      <h2 class="title visible-large">RocketLauncher</h2>
      <h2 class="title hidden-large smallmarginbottom">Replica</h2>
    </div>
</div>

<span class="visible-tablet">A full WordPress installation that installs a edited version of the demo.</span>
<span class="hidden-tablet">A full WordPress installation that installs a edited version of the demo onto your server.</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Box Variation** option to **Box 2**.
* Enter `icon-magic icon-large` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo27]: assets/wp_metropolis_demo_27.jpg