---
title: Chimera: Recreating the Demo - Header Slideshow
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP RokSprocket Features - Header Slideshow
-----

![][demo]

The **RokSprocket Showcase** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket module to an article. The **Title**, **Description**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** fields which will likely not work on your local copy as the links will be different.

### Details

![][demo2]

| Option           | Setting                                      |  
| :--------------- | :------------------------------------------- |  
| Title            | `FP RokSprocket Features - Header Slideshow` |  
| Show Title       | Hide                                         |  
| Access           | Public                                       |  
| Position         | slideshow                                    |  
| Status           | Published                                    |  
| Content Provider | Simple                                       |  
| Type             | Features                                     |  

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<div class="wow bounceInDown"><span class="hl">Beauty</span> in the Details</div>
~~~

**Description**

~~~ .html
<div class="wow zoomIn" data-wow-delay="1s">Chimera is a clean, modern and minimalistic theme showcasing the beauty of your content</div><div class="wow bounceInUp" data-wow-delay="1s"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a></div>
~~~

#### Article 2

**Title**

~~~
<span class="hl">Bounce</span> and Zoom
~~~

**Description**

~~~ .html
<div class="wow zoomIn" data-wow-delay="1s">Scroll events trigger a series of effects to animate the introduction of template sections</div><div class="wow bounceInUp" data-wow-delay="1s"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a></div>
~~~

#### Article 3

**Title**

~~~ .html
<span class="hl">Dynamic</span> Fixed Header
~~~

**Description**

~~~ .html
<div class="wow zoomIn" data-wow-delay="1s">The header dynamically appears on scroll, containing both the logo and dropdown menus</div><div class="wow bounceInUp" data-wow-delay="1s"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a></div>
~~~

### Layout Options

![][demo3]

| Option                | Setting               |  
| :-------------------- | :-------------------- |  
| Display Limit         | ∞                     |  
| Theme                 | Full Slideshow        |  
| Article Titles        | Show                  |  
| Article Text          | Show                  |  
| Preview Length        | ∞                     |  
| Strip HTML Tags       | No                    |  
| Arrow Navigation      | Show                  |  
| Pagination            | Hide                  |  
| Animation             | Crossfade             |  
| Autoplay              | Disable               |  
| Autoplay Delay        | 5                     |  
| Image Resize          | Disable               |  
| Default Title         | Default Article Title |  
| Default Article Text  | Default Article Text  |  
| Default Article Image | Default Article Image |  
| Default Link          | Default Article Link  |  

### Advanced

![][demo4]

| Option              | Setting                           |  
| :------------------ | :-------------------------------- |  
| Module Class Suffix | `fp-roksprocket-header-slideshow` |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
