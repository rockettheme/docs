---
title: Tessellate: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Tessellate Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Tessellate Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post which has no title.

| Option         | Settings  |  
| :------------- | :-------- |  
| Title          |           |  
| Status         | Published |  
| Tags           | Blank     |  
| Featured Image | Blank     |  


Most of the magic takes place in the post content:

~~~ .html
<div class="rt-center">
<h3 class="fp-article-feature">"Tessellate is a sharp, elegant and refined template. It is designed to not only enrich your content, but also to provide an overall artistic base, with animated extras, to impress your visitors, and best reflect the focus of your site." - <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Read More</a></h3>
</div>
~~~

[demo]: assets/demo_8.jpeg
[mainbody]: assets/setadvanced.jpeg
