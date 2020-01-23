---
title: Modulus: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Modulus Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/modulus:Modulus

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Modulus Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Modulus Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Integrated RocketTheme Extensions**.

| Option         | Settings                             |
| :------------- | :-----------------                   |
| Title          | `Integrated RocketTheme Extensions` |
| Status         | Published                            |
| Tags           | Blank                                |
| Featured Image | Blank                                |


Most of the magic takes place in the post content:

~~~ .html
<img src="http://demo.rockettheme.com/live/wordpress/modulus/wp-content/rockettheme/rt_modulus_wp/frontpage/fp-main1.jpg" alt="image" width="193" height="157" class="rt-image floatleft" />

<p><strong>Modulus</strong> has integrated styling for <strong>9</strong> RocketTheme Plugins, that are compatible with WordPress 3, as well as supporting a further 4 utility plugins, as available in the RocketLauncher.</p>

<p>Examples of styled plugins used on this page include <em>RokTabs</em> and <em>RokFeatureTable</em>, with all others demoed under the <a href="#">Plugins</a> menu tab above, with documentation on their use and download information.</p>
<!--more-->
<div class="clear"></div>
<span>The above comments are powered by <a href="http://intensedebate.com/" target="_blank">IntenseDebate</a></span>
~~~

![][blogview]

The settings used to create the layout of this area of the page can be found in **Admin > Modulus Theme > Content > Blog View**. This is where the **Blog Category** is set, telling WordPress which category to place on the front page. The **Post Count** sets the amount of posts showed. The **Leading Posts** sets the amount of posts that are shown in larger, single column layouts, ahead of the two-column post display for the others.

[demo]: assets/demo_5.jpeg
[mainbody]: assets/setadvanced.jpeg
[blogview]: assets/blogview.jpeg
