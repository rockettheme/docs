---
title: Spectral: Recreating the Demo - Featured Post
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Featured Post
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Spectral Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Spectral Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Featured Post**.

| Option         | Settings           |  
| :------------- | :----------------- |  
| Title          | `Featured Post`    |  
| Status         | Published          |  
| Tags           | Blank              |  
| Featured Image | Blank              |  


Most of the magic takes place in the post content:

~~~ .html
<span class="rt-featured-title-tag">Multiple Layouts</span>

<div class="gantry-width-66">
    <div class="rt-featured-article">
    <h3 class="nomarginbottom">Flexible Widgets</h3>
    <p><span>Collapsible positions and configurable grid sizes and distributions <span class="visible-desktop">allow for individual page layouts</span>.</span></p>

    <h3 class="nomarginbottom">RokSprocket Layouts</h3>
    <p><span>The various RokSprocket layouts, such as Strips, allow for diverse content display.</span></p>

    <a class="readon" href="http://demo.rockettheme.com/live/wordpress/spectral/features/">Read More</a>
  </div>
</div>
<div>
  <div class="rt-featured-image">
    <img src="http://demo.rockettheme.com/live/wordpress/spectral/wp-content/rockettheme/rt_spectral_wp/frontpage/featured-article/img1.jpg" alt="image" />
  </div>
</div>  

<div class="clear"></div>
~~~ 

[demo]: assets/demo_8.jpeg
[mainbody]: assets/mainbody.jpeg