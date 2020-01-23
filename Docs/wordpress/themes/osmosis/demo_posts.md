---
title: Osmosis: Recreating the Demo - Featured Post
description: Your Guide to Recreating Elements of the Osmosis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/osmosis:Osmosis

---

Featured Post Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** and **Display Content** options set to **On** in your theme settings. You can find these options by navigating to **Admin -> Osmosis Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Osmosis Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **RokSprocket Strips**.

| Option         | Settings    |
| :----------    | :---------- |
| Title          | None        |
| Status         | Published   |
| Tags           | Blank       |
| Featured Image | Blank       |


Most of the magic takes place in the post content:

~~~ .html
<div class="box5">
<div class="gantry-width-container">
<div class="gantry-width-50">
<div class="fp-featured-content-animate">
<div class="gantry-width-container">
<div class="gantry-width-50 fp-featured-content-block">
<div class="fp-featured-content-image-block"><img class="fp-featured-image-01" src="http://(Your Site URL)/wp-content/rockettheme/rt_osmosis_wp/home/featured-content/img-01.jpg" alt="image" />
<div class="rt-desc-overlay"></div>
</div>
</div>
<div class="gantry-width-50 fp-featured-content-block">
<div class="fp-featured-content-image-block"><img class="fp-featured-image-02" src="http://(Your Site URL)/wp-content/rockettheme/rt_osmosis_wp/home/featured-content/img-02.jpg" alt="image" />
<div class="rt-desc-overlay"></div>
</div>
</div>
<div class="clear"></div>
<div class="gantry-width-50 fp-featured-content-block">
<div class="fp-featured-content-image-block"><img class="fp-featured-image-03" src="http://(Your Site URL)/wp-content/rockettheme/rt_osmosis_wp/home/featured-content/img-03.jpg" alt="image" />
<div class="rt-desc-overlay"></div>
</div>
</div>
<div class="gantry-width-50 fp-featured-content-block">
<div class="fp-featured-content-image-block"><img class="fp-featured-image-04" src="http://(Your Site URL)/wp-content/rockettheme/rt_osmosis_wp/home/featured-content/img-04.jpg" alt="image" />
<div class="rt-desc-overlay"></div>
</div>
</div>
</div>
</div>
</div>
<div class="gantry-width-50">
<div class="gantry-width-spacer largepaddingtop largemargintop">
<p class="rt-text-small nomarginbottom">RokSprocket Plugin</p>

<h2 class="rt-text-large rt-text-white nomarginleft nomarginright">Multiple Layouts &amp; A Custom Administrator</h2>
<p class="rt-text-white hidden-tablet">RokSprocket is a revolutionary content plugin<span class="hidden-large"> with great flexibility</span><span class="visible-large">, offering an extremely flexible and versatile approach to presenting content</span>.</p>
<p class="rt-text-small">The custom interface is intuitive and extensive, allowing you to quickly setup your content in varying ways<span class="hidden-tablet">, with drag n drop, ajax and dynamic filters</span>.</p>
<a href="#" class="readon">Read More</a>

</div>
</div>
</div>
<div class="clear"></div>
</div>
~~~ 

[demo]: assets/demo_6.jpeg
[mainbody]: assets/setadvanced.jpeg