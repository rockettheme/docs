---
title: Myriad: Animation on Scroll
description: Your Guide to Using Animation on Scroll
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

AOS Atom
---------
Starting with Myriad 2.1.0, we have implemented the <a href="https://michalsnik.github.io/aos/">Animation on Scroll</a> (AOS) library to allow animations to be used within the Myriad template.

To initialize the library, go to your Base Outline > Page Settings and drag the Animate on Scroll atom into the dock. You can then save the Page Settings.

![](assets/aos_atom.jpg)

By clicking on the atom, you will find the Global settings to be used for your AOS elements:

![](assets/aos_settings.jpg)

AOS Attributes
---------
Once the atom is in place, you can now use the data-aos attributes within any of your HTML tags as shown here:

~~~ .html
<div data-aos="fade-up">Photo Centric Template</div>
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
