---
title: Kinetic: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Kinetic Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kinetic:Kinetic

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Kinetic Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Kinetic Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Kinetic September 2010**.

| Option         | Settings                 |
| :----------    | :----------              |
| Title          | `Kinetic September 2010` |
| Status         | Published                |
| Tags           | Blank                    |
| Featured Image | Blank                    |


Most of the magic takes place in the article content:

~~~ .html
<strong>Kinetic</strong> is the September 2010 WordPress Theme release,
sporting a rich, versatile and selective conservative design, founded on the
powerful and flexible Gantry Framework.

<div class="demo-mb">
    <img alt="Main Content 0" border="0" class="mb-image" src=
    "http://demo.rockettheme.com/live/wordpress/kinetic/wp-content/rockettheme/rt_kinetic_wp/frontpage/mb0.jpg">
    <span class="demo-title">Eight Preset Styles</span>An array of stunning,
    unique and professionally designed style variations, in 3 detail levels:
    High, Med and Low. <a href="#">Read More</a>
</div>

<div class="demo-mb">
    <img alt="Main Content 1" border="0" class="mb-image" src=
    "http://demo.rockettheme.com/live/wordpress/kinetic/wp-content/rockettheme/rt_kinetic_wp/frontpage/mb1.jpg">
    <span class="demo-title">Triple Level Splitmenu</span>Splitmenu displays
    its 2nd level items horizontally, in the navigation position, and the rest
    in the sidebar. <a href="#">Read More</a>
</div>

<div class="demo-mb">
    <img alt="Main Content 2" border="0" class="mb-image" src=
    "http://demo.rockettheme.com/live/wordpress/kinetic/wp-content/rockettheme/rt_kinetic_wp/frontpage/mb2.jpg">
    <span class="demo-title">Widget Variations</span>Choose from 8 Ribbon and 8
    Box styles to diversify and enhance your widget content beyond simple
    default styling. <a href="#">Read More</a>
</div>
~~~

[demo]: assets/demo_8.jpeg
[mainbody]: assets/setadvanced.jpg
