---
title: Spectral: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Feature Section
-----

![][demo]

:   1. **RokSprocket** [10%, 5%, se]
    2. **Text** [10%, 52%, se]

Here is the widget breakdown for the Feature section:

* RokSprocket - Tabs
* Gantry Divider
* Text

#### RokSprocket - Tabs

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Tabs Position   | Top            |
| Display Limit   | ∞              |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | ∞              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Tab Label**

~~~ .html
<span class="icon-cloud-download"></span>
~~~

**Description**

~~~ .html
<p>RokSprocket is a powerful, versatile and flexible content presentation
plugin. It is prebuilt with many layout options, such as Tabs and Lists, to
cover most desired configurations, and is easily expandable.</p>

<p class="hidden-tablet"><span>It also benefits from an advanced <span class=
"visible-large">but user friendly</span> administrator <span class=
"visible-large">for quick and easy setup</span>.</span></p>
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `Popular Features[span class="rt-title-tag"]By RokSprocket[/span]` in the **Title** field.
* Enter `fp-roksprocket-tabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="fp-about-spectral-image-container">
    <div class="gantry-width-50">
    <div class="rt-image-container">
      <img src="http://demo.rockettheme.com/live/wordpress/spectral/wp-content/rockettheme/rt_spectral_wp/frontpage/about-spectral/img1.jpg" alt="image" />
      <div class="rt-image-description rt-hover1">
        <div class="rt-image-content">
          <span class="icon-heart"></span>
          <span class="rt-image-text">Elegant</span>          
        </div>
      </div>      
    </div>
  </div>
  <div class="gantry-width-50">
    <div class="rt-image-container">
      <img src="http://demo.rockettheme.com/live/wordpress/spectral/wp-content/rockettheme/rt_spectral_wp/frontpage/about-spectral/img2.jpg" alt="image" />
      <div class="rt-image-description rt-hover2">
        <div class="rt-image-content">
          <span class="icon-camera"></span>
          <span class="rt-image-text">Modern</span>         
        </div>
      </div>      
    </div>
  </div>  
  <div class="clear"></div>
</div>

<h2 class="title">About Spectral<span class="rt-title-tag">RocketTheme Theme</span></h2>

<p>A theme design inspired by recent visual trends, blending subtle backgrounds and overlays, with text set by custom fonts, to create an alluring experience for your visitors, whilst maintaining an professional and functional look.</p>
<a class="readon" href="http://demo.rockettheme.com/live/wordpress/spectral/features/">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Box Variation** option to **Box 4**.
* Enter `fp-about-spectral` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[roksprocket]: ../../plugins/roksprocket/