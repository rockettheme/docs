---
title: Audacity: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Audacity Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/g4audacity:Audacity

---

MainBody Section
-----

![](assets/demo_11.jpeg)

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![](assets/setadvanced.md)

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Audacity Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Audacity Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Also in the **Blog View** tab are three fields for **Post Display**. In this case, the **Leading Posts** is set to `0`, **Intro Posts** to `3`, and the **Columns** to `1`.

Below, we have listed the settings of the post titled **RokGallery Theme Integration**.

| Option         | Settings                                                               |
| :------------- | :-----------------                                                     |
| Title          | `Improve your site by using ultimate media presentation plugin RokBox` |
| Status         | Published                                                              |
| Tags           | Blank                                                                  |
| Featured Image | Blank                                                                  |


Most of the magic takes place in the post content:

~~~ .html
<p class="rt-lead">An advanced multimedia presentation plugin.</p>

<p>This very popular plugin can showcase many different media formats such as images, videos, music, embedded widgets, Ajax content, and WordPress widgets, all from a three-dimensional display.</p>

<a href="http://demo.rockettheme.com/live/wordpress/audacity/features-overview/" class="readon">Read More</a>
~~~ 
