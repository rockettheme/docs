---
title: Visage: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Visage Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/visage:Visage

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Visage Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Visage Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **A Rich &amp; Refined Design**.

| Option         | Settings                      |
| :------------- | :-----------------            |
| Title          | `A Rich &amp; Refined Design` |
| Status         | Published                     |
| Tags           | Blank                         |
| Featured Image | Blank                         |


Most of the magic takes place in the post content:

~~~ .html
<p class="nomarginbottom"><strong>Visage</strong>, the July 2012 theme release, is a <strong>contemporary</strong> blending of stunning, refined visuals, combined with a <strong>polished</strong> and powerful undertone, providing a unique look that is flexible and intuitive to use. The foundational <strong>Gantry Framework</strong> creates a core rich with features, such as the 960 Grid System, <strong>per override configuration</strong>, amongst many others.</p>
~~~ 

[demo]: assets/demo_8.jpeg
[mainbody]: assets/mainbody.jpeg