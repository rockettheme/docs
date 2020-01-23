---
title: Graffito: Recreating the Demo - Top News of the Week
description: Your Guide to Recreating Elements of the Graffito Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/graffito:Graffito

---

Top News of the Week
-----

![][demo1]

:	1. **Post** [15%, 6%, se]

This area of the front page is a post. We assigned it the **Front Page** category which is called to the front page of our demo by setting it as the default **Blog View** category. You can do this by navigating to **Admin -> Graffito Theme -> Content -> Blog View** and entering the blog category you wish to have appear on the content area of the front page. In this instance, we set the **Posts Display** option to **1** in order to only show a single post in that space.

![][blogview]

>> NOTE: You can find out the category number of a particular post category by editing the category in **Admin -> Posts -> Categories**. In the category editor screen, the URL will contain a sting similar to `tag_ID=2` The **tag_ID** number in the URL is the category number.

You will also want to make sure that **Advanced -> Display Content** is turned **On** for the front page. 

![][postbody]

Here is the content body of the post.

~~~ .html
<div class="gantry-width-50 gantry-width-block hidden-large">
    <div class="gantry-width-spacer nomarginleft nomarginright">
        <div class="rt-image">
      <img src="http://demo.rockettheme.com/wordpress-themes/wp_graffito/wp-content/rockettheme/rt_graffito_wp/frontpage/general/featured-1.jpg" alt="image" />
    </div>
  </div>
</div>  

<div class="gantry-width-50 gantry-width-block hidden-large">
  <div class="gantry-width-spacer largepaddingleft">
    <p><strong>Graffito</strong> is a corporate-esque design, perfect for many sites with its contrast of visual character with subtlety.</p> 

    <p class="hidden-tablet">Built with the <strong>Gantry4</strong> Framework, it features a responsive layout and LESS CSS support for dynamic behaviours within stylesheets.</p>

    <p class="visible-tablet">Built with the <strong>Gantry4</strong> Framework, it features a responsive layout.</p>

    <a class="readon" href="http://demo.rockettheme.com/wordpress-themes/wp_graffito/features/"><span>See More</span></a>
  </div>
</div>

<div class="gantry-width-40 gantry-width-block visible-large">
    <div class="gantry-width-spacer nomarginleft nomarginright">
      <div class="rt-image">
      <img src="http://demo.rockettheme.com/wordpress-themes/wp_graffito/wp-content/rockettheme/rt_graffito_wp/frontpage/general/featured-1.jpg" alt="image" />
    </div>
  </div>
</div>  

<div class="gantry-width-60 gantry-width-block visible-large">
  <div class="gantry-width-spacer largepaddingleft">
    <p><strong>Graffito</strong>, the May 2013 theme release, is a corporate-esque design, perfect for many sites with its contrast of visual character with subtlety.</p> 

    <p>Built with the <strong>Gantry4</strong> Framework, it features a responsive layout and LESS CSS support  for dynamic behaviours within stylesheets.</p>

    <a class="readon" href="http://demo.rockettheme.com/wordpress-themes/wp_graffito/features/"><span>See More</span></a>
  </div>
</div>
~~~

Once the post is set to **Published**, you should be able to see it on the page.

[demo1]: assets/wp_graffito_demo_4.jpeg
[postbody]: assets/postbody.jpg
[blogview]: assets/blogview.jpg