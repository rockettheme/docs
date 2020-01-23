---
title: Clarion: Recreating the Demo - Featured Post
description: Your Guide to Recreating Elements of the Clarion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/clarion:Clarion

---

Featured Post Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** and **Display Content** options set to **On** in your theme settings. You can find these options by navigating to **Admin -> Clarion Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Clarion Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Professional Theme**.

| Option         | Settings             |
| :----------    | :----------          |
| Title          | `Professional Theme` |
| Status         | Published            |
| Tags           | Blank                |
| Featured Image | Blank                |


Most of the magic takes place in the post content:

~~~ .html
<img class="rt-image floatright medmarginbottom" alt="image" src="http://demo.rockettheme.com/live/wordpress/clarion/wp-content/rockettheme/rt_clarion_wp/frontpage/fp-mainbody-1.jpg" width="320" height="210" />
<div class="title5 floatleft"><div class="module-title"><h2 class="title">Professional Theme</h2></div></div><br /><br /><br />
<p>Built on the <strong>Gantry Framework</strong>, Clarion has a range of powerful, flexible and intuitive features and functions.</p>
<p>The administrative interface offers a user friendly control panel for intricately customizing the <strong>themes layouts</strong>.</p>
<a href="http://demo.rockettheme.com/live/wordpress/clarion/theme-features/" class="nobold"><span>View All Features +</span></a>
~~~

[demo]: assets/demo_10.jpeg
[mainbody]: assets/setadvanced.jpeg
