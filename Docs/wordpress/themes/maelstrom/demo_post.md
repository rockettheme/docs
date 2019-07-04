---
title: Maelstrom: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Maelstrom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/maelstrom:Maelstrom

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Maelstrom Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Maelstrom Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Portfolio Series: August 2011 — Maelstrom**.

| Option         | Settings                                    |  
| :------------- | :------------------------------------------ |  
| Title          | `Portfolio Series: August 2011 — Maelstrom` |  
| Status         | Published                                   |  
| Tags           | Blank                                       |  
| Featured Image | Blank                                       |  


Most of the magic takes place in the post content:

~~~ .html
<img src="http://demo.rockettheme.com/live/wordpress/maelstrom/wp-content/rockettheme/rt_maelstrom_wp/frontpage/main1.jpg" alt="image" width="140" height="98" class="rt-image floatleft" />

<span class="rt-author">Individually <a href="#"><em>style</em></a> your modular content.</span>

<p class="smallmarginbottom"><em>Over 250 possible Widget style combinations.</em></p>

<p class="smallmarginbottom">Combine the 31 style variations together to create diverse widget styling, style the titles, widget backgrounds and read more.</p>

<span class="rt-author">Highlights: <a href="#"><em>Icons</em></a>, <a href="#"><em>Combos</em></a>, <a href="#"><em>Layout Suffixes</em></a></span>

<a class="readon floatright" href="#"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="http://demo.rockettheme.com/live/wordpress/maelstrom/wp-content/rockettheme/rt_maelstrom_wp/frontpage/main2.jpg" alt="image" width="140" height="98" class="rt-image floatleft" />

<span class="rt-author">Powered by the <a href="#"><em>RokNavMenu</em></a>.</span>

<p class="smallmarginbottom"><em>Featuring Fusion with MegaMenu abilities.</em></p>

<p class="smallmarginbottom">Fusion is a Mootools enhanced CSS dropdown menu system, that is fully crawlable by search engines, and packed with advanced features.</p>

<span class="rt-author">Highlights: <a href="#"><em>Multi-Columns</em></a>, <a href="#"><em>Subtexts</em></a>, <a href="#"><em>Menu Icons</em></a></span>

<a class="readon floatright" href="#"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="http://demo.rockettheme.com/live/wordpress/maelstrom/wp-content/rockettheme/rt_maelstrom_wp/frontpage/main3.jpg" alt="image" width="140" height="98" class="rt-image floatleft" />

<span class="rt-author">Condense <a href="#"><em>positions</em></a> for more window real estate.</span>

<p class="smallmarginbottom"><em>Scrollable widget positions and rows.</em></p>

<p class="smallmarginbottom">Stacked widgets placed in the configured Widget rows will load this feature; this places stacked widgets inside a rotation element.</p>

<span class="rt-author">Highlights: <a href="#"><em>Smooth</em></a>, <a href="#"><em>Configurable</em></a>, <a href="#"><em>Automated</em></a></span>

<a class="readon floatright" href="#"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="http://demo.rockettheme.com/live/wordpress/maelstrom/wp-content/rockettheme/rt_maelstrom_wp/frontpage/main4.jpg" alt="image" width="140" height="98" class="rt-image floatleft" />

<span class="rt-author">Versatile content <a href="#"><em>rotator</em></a> plugin.</span>

<p class="smallmarginbottom"><em>A new RokStories layout mode.</em></p>

<p class="smallmarginbottom">The new Scroller Showcase layout, showcasing large images in an intuitive and elegant manner, perfect for any portfolio site.</p>

<span class="rt-author">Highlights: <a href="#"><em>Multiple Layouts</em></a>, <a href="#"><em>Advanced Controls</em></a></span>

<a class="readon floatright" href="#"><span>Read More...</span></a>

<div class="clear"></div>
~~~

[demo]: assets/demo_9.jpeg
[mainbody]: assets/setadvanced.jpeg
