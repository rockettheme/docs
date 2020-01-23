---
title: Reaction: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Reaction Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/reaction:Reaction

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Content** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Reaction Theme -> Advanced -> Content**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Reaction Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Latest Blog**.

| Option         | Settings           |
| :------------- | :----------------- |
| Title          | `Latest Blog`      |
| Status         | Published          |
| Tags           | Blank              |
| Featured Image | Blank              |


Most of the magic takes place in the post content:

~~~ .html
<img class="rt-image" alt="Blog Image" src="http://demo.rockettheme.com/live/wordpress/reaction/wp-content/rockettheme/rt_reaction_wp/frontpage/blog1.jpg">
<p><span class="rt-article-subline">Gantry: The Brand New, Powerful and Intricate Framework / Platform from the RocketTheme Team</span></p>
<p>The new <strong>Gantry Framework</strong> allows for a much more efficient, more powerful underlying system; that can transcend to other platforms with ease. The main features of Gantry are its 960 Grid system, and its advanced administrative control panel, with a vast assortment of other features ready to enhance your WordPress experience.</p><!--more-->

Nam pulvinar, odio sed rhoncus suscipit, sem diam ultrices mauris, eu consequat purus metus eu velit. Proin metus odio, aliquam eget molestie nec, gravida ut sapien. Phasellus quis est sed turpis sollicitudin venenatis sed eu odio. Praesent eget neque eu eros interdum malesuada non vel leo. Sed fringilla porta ligula egestas tincidunt. Nullam risus magna, ornare vitae varius eget, scelerisque a libero. Morbi eu porttitor ipsum. Nullam lorem nisi, posuere quis volutpat eget, luctus nec massa. Pellentesque aliquam lacinia tellus sit amet bibendum. Ut posuere justo in enim pretium scelerisque. Etiam ornare vehicula euismod. Vestibulum at risus augue. Sed non semper dolor. Sed fringilla consequat velit a porta. Pellentesque sed lectus pharetra ipsum ultricies commodo non sit amet.

Nam pulvinar, odio sed rhoncus suscipit, sem diam ultrices mauris, eu consequat purus metus eu velit. Proin metus odio, aliquam eget molestie nec, gravida ut sapien. Phasellus quis est sed turpis sollicitudin venenatis sed eu odio. Praesent eget neque eu eros interdum malesuada non vel leo. Sed fringilla porta ligula egestas tincidunt. Nullam risus magna, ornare vitae varius eget, scelerisque a libero. Morbi eu porttitor ipsum. Nullam lorem nisi, posuere quis volutpat eget, luctus nec massa. Pellentesque aliquam lacinia tellus sit amet bibendum. Ut posuere justo in enim pretium scelerisque. Etiam ornare vehicula euismod. Vestibulum at risus augue. Sed non semper dolor. Sed fringilla consequat velit a porta. Pellentesque sed lectus pharetra ipsum ultricies commodo non sit amet.
~~~ 

[demo]: assets/demo_5.jpeg
[mainbody]: assets/setadvanced.jpeg