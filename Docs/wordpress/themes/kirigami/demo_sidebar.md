---
title: Kirigami: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Kirigami Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kirigami:Kirigami

---

Sidebar Section
-----
![][demo27]

:   1. **Sidebar** The steps to create this area of the demo are detailed below. [11%, 75%, se]

Here is the widget breakdown for the Sidebar section:

* RokSprocket
* Text

### RokSprocket
The **Gantry Extras** widget located in the sidebar section of the page is a RokSprocket Lists widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting |  
| :------------------ | ------: |  
| Theme               | Default |  
| Collapsible Preview |  Enable |  
| Display Limit       |       ∞ |  
| Preview Length      |      20 |  
| Strip HTML Tags     |     Yes |  
| Previews Per Page   |       4 |  
| Arrow Navigation    |    Show |  
| Pagination          |    Show |  
| Autoplay            |       5 |  
| Image Resize        | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Gantry Extras`
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

### Text
The Text widget in this section is titled **Demo Replica** and has the following in the main text field.

~~~
<p class="medmarginbottom hidden-tablet"><strong>RocketLauncher</strong> is a customized <strong>WordPress</strong> install, that installs a <strong>replica</strong> of the <strong>demo</strong>.</p>

<p>All sample content images, shown in this demo, will be replaced with blanks in the <a href="http://demo.rockettheme.com/wordpress/wp_kirigami/tutorials/installation/"><strong>Kirigami RocketLauncher</strong></a> package to avoid any copyright issue.</p>4

<a class="readon" href="http://demo.rockettheme.com/wordpress/wp_kirigami/tutorials/installation/"><span>Download</span></a>
~~~

* Set the **Title** to `Demo Replica`
* Set the **Box Variation** option to **Box 1**.
* Set the **Title Variation** option to **Basic Title**.
* Enter `hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo27]: assets/wp_kirigami_demo_5.jpeg