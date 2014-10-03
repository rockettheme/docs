---
title: Hybrid: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Hybrid Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hybrid:Hybrid

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Hybrid Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Hybrid Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Digital SLRs**.

| Option         | Settings                                            |  
| :------------- | :-------------------------------------------------- |  
| Title          | `Style: the Central Focus for the Hybrid Template.` |  
| Status         | Published                                           |  
| Tags           | Blank                                               |  
| Featured Image | Blank                                               |  


Most of the magic takes place in the article content:

~~~ .html
<p><img src="http://demo.rockettheme.com/live/wordpress/hybrid/wp-content/rockettheme/rt_hybrid_wp/frontpage/mb1.jpg" alt="image" class="rt-image" width="660" height="128" /></p>
<p class="nomarginbottom">The theme is <strong>divided</strong> into 4 major style areas: <em>Header, Footer, Body and Body Accent</em>. These denominations control the styling for each area, as selectable from the <strong>Gantry Administrator</strong>. There are <strong>15 style</strong> variations to choose from, by default, which offer a range of color schemes, demonstrating the stylistic versatility of <strong>Hybrid</strong>.</p>
~~~

[demo]: assets/demo_7.jpg
[mainbody]: assets/setadvanced.jpeg
