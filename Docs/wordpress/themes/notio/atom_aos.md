---
title: Notio: Animation on Scroll
description: Your Guide to Using Animation on Scroll
breadcrumb: /wordpress:WordPress/!themes:Themes/notio:Notio

---

AOS Atom
---------

<a href="https://michalsnik.github.io/aos/">Animation on Scroll</a> (AOS) is a small JS library that allows you to animate elements on your page as you scroll.

To initialize the library, go to your Base Outline > Page Settings and drag the Animate on Scroll atom into the dock. You can then save the Page Settings.

![](assets/aos_atom.jpg)

By clicking on the atom, you will find the Global settings to be used for your AOS elements:

![](assets/aos_settings.jpg)

| Option        | Description                                                                                 |
| :-----        | :-----                                                                                      |
| Duration      | Values from 0 to 3000, with step 50ms. 													  |
| Once          | Whether animation should happen only once - while scrolling down.	                      	  |
| Delay         | Values from 0 to 3000, with step 50ms.                                                      |
| Easing        | Default easing for AOS animations.                     									  |
| Offset        | Offset (in px) from the original trigger point.                                             |

AOS Attributes
---------
Once the atom is in place, you can now use the data-aos attributes within any of your HTML tags as shown here:

~~~ .html
<div data-aos="fade-up">Photo Centric Theme</div>
~~~

You can also set each elements duration and delay as shown here:

~~~ .html
<div data-aos="fade-up" data-aos-delay="500" data-aos-duration="500">Focus</div>
~~~

The animation attributes can also be used within a Section / Block via the Tag Attribute option:

![](assets/aos_tag.jpg)

Predefined Options
---------

Here is a list of predefined options for animations:

Fade animations:

* fade
* fade-up
* fade-down
* fade-left
* fade-right
* fade-up-right
* fade-up-left
* fade-down-right
* fade-down-left

Flip animations:

* flip-up
* flip-down
* flip-left
* flip-right

Slide animations:

* slide-up
* slide-down
* slide-left
* slide-right

Zoom animations:

* zoom-in
* zoom-in-up
* zoom-in-down
* zoom-in-left
* zoom-in-right
* zoom-out
* zoom-out-up
* zoom-out-down
* zoom-out-left
* zoom-out-right
