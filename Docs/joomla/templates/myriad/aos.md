---
title: Myriad: Animation on Scroll
description: Your Guide to Using Animation on Scroll
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

AOS Atom
---------
Starting with Myriad 2.1.0+, we have implemented the <a href="https://michalsnik.github.io/aos/">Animation on Scroll</a> (AOS) library to allow animations to be used within the Myriad theme.

To initialize the library, go to your Base Outline > Page Settings and drag the Animate on Scroll atom into the dock. You can then save the Page Settings.

![](assets/aos_atom.jpg)

By clicking on the atom, you will find the Global settings to be used for your AOS elements:

![](assets/aos_settings.jpg)

AOS Tags
---------
Once the atom is in place, you can now use attributes within any of your HTML tags as shown here:

~~~ .html
<span data-aos="fade-up" data-aos-delay="500">Photo Centric Theme</span>
~~~

You can also use the animation within a Section / Block as shown here via the Tag Attribute option:

![](assets/aos_tag.jpg)

The list of predefined options for animations are the following:

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
