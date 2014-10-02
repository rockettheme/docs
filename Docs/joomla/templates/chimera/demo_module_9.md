---
title: Chimera: Recreating the Demo - Slideshow 2
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Slideshow 2
-----

![][demo]

The **RokSprocket Showcase** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket module to an article. The **Title**, **Description**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** fields which will likely not work on your local copy as the links will be different.

### Details

![][demo2]

| Option           | Setting                                      |  
| :--------------- | :------------------------------------------- |  
| Title            | `FP RokSprocket Features - Slideshow 2`      |  
| Show Title       | Hide                                         |  
| Access           | Public                                       |  
| Position         | fullwidth                                    |  
| Status           | Published                                    |  
| Content Provider | Simple                                       |  
| Type             | Features                                     |  

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<div class="wow bounceInDown">  <span>"Sleek Design and Easy Customization Made this the Perfect Theme for Me"</span></div>
~~~

**Description**

~~~ .html
<div class="rt-slideshow2-content wow zoomIn">
    <p>I struggled for a long time to find the right design and functionality for my portfolio site. Chimera was exactly what I was looking for to get my site up and running quickly and easily. I love it!</p>
</div>

<div class="rt-slideshow2-author wow bounceInUp" data-wow-delay="1s">
    <img alt="image" src="images/rocketlauncher/home/fp-fullwidth/img-author-01.jpg"> <span>Martin McDouglas</span>
</div>
~~~

#### Article 2

**Title**

~~~
"A Contemporary Style, Utilizing Modern Design Trends, as well as Being Functional"
~~~

**Description**

~~~ .html
<div class="rt-slideshow2-content">
    <p>I regularly change my site's design to ensure that it remains fresh, new and modern. Chimera offers a theme with all the standard features I've come to expect with a new design approach.</p>
</div>

<div class="rt-slideshow2-author">
    <img alt="image" src="images/rocketlauncher/home/fp-fullwidth/img-author-02.jpg"> <span>Jerry Andrews</span>
</div>
~~~

#### Article 3

**Title**

~~~ .html
"An Impressive Animated Experience for my Visitors, to Ensure the Uniqueness"
~~~

**Description**

~~~ .html
<div class="rt-slideshow2-content">
    <p>Chimera has a series of introductory animations on elements when you scroll through the page. They add character and life, whilst not detracting from the visitor's experience.</p>
</div>

<div class="rt-slideshow2-author">
    <img alt="image" src="images/rocketlauncher/home/fp-fullwidth/img-author-03.jpg"> <span>Sam Santiago</span>
</div>
~~~

### Layout Options

![][demo3]

| Option                | Setting               |  
| :-------------------- | :-------------------- |  
| Display Limit         | `∞`                   |  
| Theme                 | Slideshow Style 2     |  
| Article Titles        | Show                  |  
| Article Text          | Show                  |  
| Preview Length        | `∞`                   |  
| Strip HTML Tags       | No                    |  
| Arrow Navigation      | Show                  |  
| Pagination            | Hide                  |  
| Animation             | Crossfade             |  
| Autoplay              | Disable               |  
| Autoplay Delay        | `5`                   |  
| Image Resize          | Disable               |  
| Default Title         | Default Article Title |  
| Default Article Text  | Default Article Text  |  
| Default Article Image | Default Article Image |  
| Default Link          | Default Article Link  |  

### Advanced

![][demo4]

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-roksprocket-slideshow` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/demo_9a.jpeg
[demo3]: assets/demo_9b.jpeg
[demo4]: assets/demo_9c.jpeg
