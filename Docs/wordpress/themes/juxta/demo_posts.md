---
title: Juxta: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Juxta Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/juxta:Juxta

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Juxta Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Juxta Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Welcome to Juxta!**.

| Option         | Settings            |
| :----------    | :----------         |
| Title          | `Welcome to Juxta!` |
| Status         | Published           |
| Tags           | Blank               |
| Featured Image | Blank               |


Most of the magic takes place in the post content:

~~~ .html
<div class="floatleft png"><img alt="image" src="http://demo.rockettheme.com/live/wordpress/juxta/wp-content/rockettheme/rt_juxta_wp/frontpage/fp-mb1.jpg" /></div>

<p><strong>Juxta, the December 2010 Theme Club release</strong>, is a design-centric theme, focusing on <em>unique</em>, <em>professional</em> and <em>fresh</em> visuals to constitute the fundamental appearance of the theme. Style is very important with any theme, and Juxta intends to <strong>entice</strong> any visitor of your site.</p>

<p>The theme has a plethora of features beyond its stylistic exterior. The core is composed of the <strong>Gantry Framework</strong>, offering a mature and feature rich foundation for many advanced, flexible and <em>versatile</em> functions to make the theme extremely usable, <em>modern</em> and engaging.</p>

[readon url="#"]View More Features[/readon]
~~~

[demo]: assets/demo_4.jpeg
[mainbody]: assets/setadvanced.jpg
