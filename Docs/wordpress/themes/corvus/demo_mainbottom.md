---
title: Corvus: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Main Bottom Section
-----

![][demo]

:   1. **Text** [13%, 5%, se]
    2. **RokSprocket** [13%, 35%, se]

Here is the widget breakdown for the Main Bottom section:

* Text
* Gantry Divider
* RokSprocket

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h3 class="nomargintop">Replicate the <a href="#">demo</a> with the
RocketLauncher package</h3>

<p><a href=
"http://demo.rockettheme.com/wordpress-themes/wp_corvus/installation/"><span class=
"rt-image-b"><img alt="image" src=
"http://demo.rockettheme.com/wordpress-themes/wp_corvus/wp-content/rockettheme/rt_corvus_wp/frontpage/mainbottom-a/img1.jpg"></span></a></p>

<p><span>The RocketLauncher package installs a full version of WordPress
<span class="hidden-tablet">with the demo sample data and sample images
included</span>.</span></p><span class="readon-wrapper2"><a class="readon"
href="http://demo.rockettheme.com/wordpress-themes/wp_corvus/installation/">Read
More</a></span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Box Variation** option to **Box 5**.
* Enter `fp-mainbottom-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Strips Layout Options** for this widget.

| Option                   | Setting   |  
| :----------------------- | :-------- |  
| Display Limit            | 6         |  
| Theme                    | Default   |  
| Preview Length           | 50        |  
| Strip HTML Tags          | No        |  
| Article Details Position | Inside    |  
| Previews Per Page        | 3         |  
| Items Per Row            | 4         |  
| Arrow Navigation         | Show      |  
| Pagination               | Hide      |  
| Animation                | Scale Out |  
| Autoplay                 | Disable   |  
| Autoplay Delay           | 5         |  
| Image Resize             | Disable   |  
| Default Title            | None      |  
| Default Link             | None      |  

**Article Item**

We did a little customization to each article item that appears in this area of the page. Below are the settings we used for one of these items.

| Option                   | Setting   |  
| :----------------------- | :-------- |  
| Title | Preset Styles |
| Image | Custom |
| Link | Default |
| Tags | Games, Music |

Description

~~~ .html
<span class="hidden-tablet">A selection of ten configuration style<span class="visible-large"> variation</span>s.</span><span class="visible-tablet">10 preset styles.</span>
~~~

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Features widget in the **Choose Widget** field.
* Enter `Popular Features` in the **Title** field.
* Set the **Box Variation** option to **Box 6**.
* Enter `fp-mainbottom-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/