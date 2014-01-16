---
title: Corvus: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Corvus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/corvus:Corvus

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Corvus Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Corvus Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **RokSprocket Strips**.

| Option         | Settings           |  
| :------------- | :----------------- |  
| Title          | RokSprocket Strips |  
| Status         | Published          |  
| Tags           | Blank              |  
| Featured Image | Blank              |  


Most of the magic takes place in the article content:

~~~ .html
<div class="gantry-width-30 gantry-width-block">
    <img class="rt-image-a" src="http://demo.rockettheme.com/wordpress/wp_corvus/wp-content/rockettheme/rt_corvus_wp/frontpage/featured/img2.jpg" alt="image">
</div>

<div class="gantry-width-60 gantry-width-block">
	<div class="largemarginleft">
		<p>Strips is a layout mode for RokSprocket <span class="hidden-tablet">that displays<span class="visible-large"> and rotates through</span> horizontal content <span class="visible-large">and image</span> blocks<span class="visible-large">, perfect for highlighting content</span></span>.</p>
	</div>
</div>

<div class="clear"></div>

<span class="rt-tags">
	<span class="rt-tag">Games</span>
	<span class="rt-tag">Action</span>
</span>

<a href="http://demo.rockettheme.com/wordpress/wp_corvus/plugins/" class="readon2 rt-floatright">+</a>
~~~ 

[demo]: assets/demo_10.jpeg
[mainbody]: assets/mainbody.jpg