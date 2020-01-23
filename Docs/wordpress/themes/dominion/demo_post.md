---
title: Dominion: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Dominion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/dominion:Dominion

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Content** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Dominion Theme -> Advanced -> Content**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Dominion Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **RTL Theme Support**.

| Option         | Settings            |
| :------------- | :-----------------  |
| Title          | `RTL Theme Support` |
| Status         | Published           |
| Tags           | Blank               |
| Featured Image | Blank               |


Most of the magic takes place in the post content:

~~~ .html
<p class="demo-img"><img class="rt-image" alt="demo image" src="http://demo.rockettheme.com/live/wordpress/dominion/wp-content/rockettheme/rt_dominion_wp/frontpage/mb-2.jpg" border="0" /></p>

<h3>Theme side RTL support from the Fusion menu to the Typography.</h3>
<p class="demo-title"><em>This is in conjunction with Gantry RTL support for the automatic flipping of the grid system.</em></p>
If WordPress is set to RTL mode, in its language settings, the Dominion theme will automatically adjust to its RTL layout. The widgets will invert inside a row, such as first showcase widget and the showcase last widget being in alternate locations; the various theme elements such as the breadcrumbs and typography will also flip; and also the menu will adjust accordingly.

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.
~~~ 

[demo]: assets/demo_6.jpeg
[mainbody]: assets/setadvanced.jpeg