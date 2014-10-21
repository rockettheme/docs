---
title: Crystalline: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Crystalline Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/crystalline:Crystalline

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Content** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Crystalline Theme -> Advanced -> Content**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Crystalline Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Other Featured Stuff Continued**.

| Option         | Settings                         |
| :------------- | :-----------------               |
| Title          | `Other Featured Stuff Continued` |
| Status         | Published                        |
| Tags           | Blank                            |
| Featured Image | Blank                            |


Most of the magic takes place in the article content:

~~~ .html
<div class="demo-mb">
    <img src="http://demo.rockettheme.com/live/wordpress/crystalline/wp-content/rockettheme/rt_crystalline_wp/frontpage/mb1.jpg" alt="Oct10 Demo Image" class="demo-fp-img img-left"/>
    <p><em>Native Right-To-Left (RTL) Support for both Gantry and independent theme elements such as module styling.</em></p>
    <p>The Gantry grid system will automatically invert the placement of module positions inside a given row when RTL mode is detected from WordPress. The template is prebuilt with CSS styles and Images that are peculiar to RTL.</p>
    <p><a href="#" class="readon"><span>Learn More</span></a></p>
</div>
~~~ 

[demo]: assets/demo_4.jpeg
[mainbody]: assets/setadvanced.jpeg