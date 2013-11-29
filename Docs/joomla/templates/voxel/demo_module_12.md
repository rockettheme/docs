---
title: Voxel: Recreating the Demo - Frontpage Article
description: Your Guide to Recreating Elements of the Voxel Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/voxel:Voxel

---

Frontpage Article
----
![][demo]
This area of the front page is a a featured article. You can replicate this by creating a new article by going to **Administrator -> Content -> Article Manager -> Add New Article**. Making it appear on the front page is easy enough. Just assign the article to the home page and make sure you have **MainBody** turned on in your Template Settings page. You will find the settings used in our demo below.

### Edit Article
![][demo2]

| Option   | Setting                |  
| :------- | :--------------------- |  
| Title    | `Top News of the Week` |  
| Featured | Yes                    |  
| Status   | Published              |  
| Access   | Public                 |  
| Language | All                    |  

### Article Text
Enter the following in the **Article Text** editor.

~~~
<div class="rt-floatright">
  {loadposition fp-featured-rokgallery}
</div>
 
<p><strong>Voxel</strong>, the May 2012 template release, is a <strong>magazine</strong> orientated design. Its elegant and engaging style provides a <strong>rich</strong> back-drop to your site content. The new <strong>Mosaic</strong> layout provides a powerful mechanism to easily show content, in a <strong>dynamic</strong> fashion.</p>
 
<p>The template has support for various RocketTheme <strong>Extensions</strong>, a beautifully styled menu, amongst other features.</p>
 
<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108" class="readon">Read More...</a>
 
<div class="clear"></div>
~~~

[demo]: assets/demo_13.jpeg
[demo2]: assets/article_1.jpg