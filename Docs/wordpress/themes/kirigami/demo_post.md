---
title: Kirigami: Recreating the Demo - Top News of the Week
description: Your Guide to Recreating Elements of the Kirigami Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kirigami:Kirigami

---

Top News of the Week
-----

![][demo1]

:	1. **Post** [12%, 6%, se]

This area of the front page is a post. We assigned it the **Front Page** category which is called to the front page of our demo by setting it as the default **Blog View** category. You can do this by navigating to **Admin -> Kirigami Theme -> Content -> Blog View** and entering the blog category you wish to have appear on the content area of the front page. In this instance, we set the **Posts Display -> Intro Posts** option to **1** in order to only show a single post in that space.

![][blogview]

>> NOTE: You can find out the category number of a particular post category by editing the category in **Admin -> Posts -> Categories**. In the category editor screen, the URL will contain a sting similar to `tag_ID=2` The **tag_ID** number in the URL is the category number.

You will also want to make sure that **Advanced -> Display Content** is turned **On** for the front page. 

![][postbody]

Here is the content body of the post.

~~~ .html
<div class="rt-demo-block rt-demo-width-60">
    <div class="rt-featured-image">
    <div class="rt-image">
      <img src="http://demo.rockettheme.com/wordpress-themes/wp_kirigami/wp-content/rockettheme/rt_kirigami_wp/frontpage/general/fp-featured.jpg" alt="image" />
    </div>
  </div>
</div>  

<div class="rt-demo-block rt-demo-width-40">
  <div class="rt-demo-spacer nomargintop">
    <p>The main focus of the <strong>Kirigami</strong> release, is its Responsive Layout. <span class="hidden-tablet"><strong>Responsive</strong> effectively means a design that will adapt automatically to match whatever device or window size is loading it.</span></p> 

    <p>Therefore, you can have one template that will adjust itself to a <strong>mobile</strong>, tablet or desktop, without necessarily needing to load a separate layout with different content.</p>

    <a class="readon" href="http://demo.rockettheme.com/wordpress-themes/wp_kirigami/features/"><span>See More</span></a>
  </div>
</div>
~~~

Once the post is set to **Published**, you should be able to see it on the page.

[demo1]: assets/wp_Kirigami_demo_5.jpeg
[postbody]: assets/postbody.jpeg
[blogview]: assets/blogview.jpeg