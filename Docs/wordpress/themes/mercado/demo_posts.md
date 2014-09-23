---
title: Mercado: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Mercado Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/mercado:Mercado

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Mercado Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Mercado Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Digital SLRs**.

| Option         | Settings       |  
| :------------- | :------------- |  
| Title          | `Digital SLRs` |  
| Status         | Published      |  
| Tags           | Blank          |  
| Featured Image | Blank          |  


Most of the magic takes place in the article content:

~~~ .html
<div class="rt-grid-3 rt-alpha floatleft"><div class="demo-main-img">
  <a href="#"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/main-camera-1.jpg" alt="image" width="190" height="120" /></a>
  <div class="module-shadow"><div class="module-shadow2"><div class="module-shadow3"></div></div></div>
  <a href="#"><em>Minolta FXX33</em></a><br />
  <strong>$1299.99</strong> | SKU 00005
  </div></div>

<div class="demo-main-img floatleft nomarginright">
  <a href="#"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/main-camera-2.jpg" alt="image" width="190" height="120" /></a>
  <div class="module-shadow"><div class="module-shadow2"><div class="module-shadow3"></div></div></div>
  <a href="#"><em>Pentax PP399</em></a><br />
  <strong>$1099.99</strong> | SKU 00020
</div>

<div class="clear"></div><br />

<div class="rt-grid-3 rt-alpha floatleft"><div class="demo-main-img">
  <a href="#"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/main-camera-3.jpg" alt="image" width="190" height="120" /></a>
  <div class="module-shadow"><div class="module-shadow2"><div class="module-shadow3"></div></div></div>
  <a href="#"><em>Nikon D500Ti</em></a><br />
  <strong>$649.99</strong> | SKU 00014
  </div></div>

<div class="demo-main-img floatleft nomarginright">
  <a href="#"><img src="http://demo.rockettheme.com/live/wordpress/mercado/wp-content/rockettheme/rt_mercado_wp/frontpage/main-camera-4.jpg" alt="image" width="190" height="120" /></a>
  <div class="module-shadow"><div class="module-shadow2"><div class="module-shadow3"></div></div></div>
  <a href="#"><em>Sony PSG042x</em></a><br />
  <strong>$379.99</strong> | SKU 00018
</div>

<div class="clear"></div>
~~~

[demo]: assets/demo_8.jpeg
[mainbody]: assets/setadvanced.jpeg
