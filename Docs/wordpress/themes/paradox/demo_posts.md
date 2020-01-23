---
title: Paradox: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Paradox Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/paradox:Paradox

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Paradox Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Paradox Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Paradox February Theme Release**.

| Option         | Settings                         |
| :----------    | :----------                      |
| Title          | `Paradox - June 2011 Theme Demo` |
| Status         | Published                        |
| Tags           | Blank                            |
| Featured Image | Blank                            |


Most of the magic takes place in the post content:

~~~ .html
<p><img src="http://demo.rockettheme.com/live/wordpress/paradox/wp-content/rockettheme/rt_paradox_wp/frontpage/fp2.jpg" alt="image" class="rt-image" width="400" height="131" /></p>

<p class="nomarginbottom">Paradox is driven by the Gantry, a powerful core framework, offering features such as per-override parameters, an iPhone version and so much more, which substantially extends the features and functions of the WordPress core.</p>

<div class="alert"><div class="typo-icon">There is limited support for IE6 as it is restricted in numerous ways such as the forcing of the low detail level, LTR is automatically set regardless of RTL presence, Fusion is replaced by the Suckerfish menu, and various other elements are dropped or modified for basic compatibility.</div></div>
~~~

[demo]: assets/demo_8.png
[mainbody]: assets/setadvanced.png
