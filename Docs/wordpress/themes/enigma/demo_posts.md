---
title: Enigma: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Enigma Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/enigma:Enigma

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Enigma Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Enigma Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Elegant Design and Flexible Features**.

| Option         | Settings                               |
| :------------- | :-----------------                     |
| Title          | `Elegant Design and Flexible Features` |
| Status         | Published                              |
| Tags           | Blank                                  |
| Featured Image | Blank                                  |


Most of the magic takes place in the post content:

~~~ .html
<img class="rt-image floatleft smallmarginbottom" src="http://demo.rockettheme.com/live/wordpress/enigma/wp-content/rockettheme/rt_enigma_wp/frontpage/fp-article.jpg" width="125" height="100" alt="RocketTheme" />

<p>The Enigma theme is built for WordPress <strong>3.x</strong> platforms. This includes the theme, the RocketTheme Plugins demoed (some plugins like RokGallery might require a higher version like 3.2.1+), the Gantry Framework, in addition to <strong>RocketLauncher</strong>. All products are available from a consolidated WordPress Download area for Enigma.</p>

<p>The theme is based on the <strong>Gantry Framework</strong>, therefore, standard features such as the 960 Grid System, <strong>iPhone/Android</strong> viewing support. Layered on top is an intricate array of design elements, textures, patterns and backgrounds providing an elegant but complex appearance.</p>

<!--more-->

<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>

<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
~~~ 

[demo]: assets/demo_7.jpeg
[mainbody]: assets/mainbody.jpg