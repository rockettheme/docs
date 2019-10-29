---
title: Chimera: Tips and Tricks
description: Your Guide to Using the chimera Style for phpBB.
breadcrumb: /phpbb:phpBB/!styles:Styles/!chimera:Chimera/
tags: [Style, Template, Theme, Features, Description, Tutorials, rokBB 5]

---

Introduction
-----

The **Chimera** design for phpBB comes with several features that set it apart from other phpBB styles. We have outlined some tips and tricks to help you make the most of the style below.

Animation
-----

![][animation1]

The animated elements that trigger as you scroll down the page are handled via classes applied to HTML elements, icons etc. You can access **Chimera's** main settings area by navigating to **Admin > Styles > Chimera**. From here, you will want to select the **Imageset Editor** tab where you can find the **Forum Icons** settings. In these fields, you can enter the tag of the animation(s) you wish to use. You can find a list (as well as visual examples) of these [animation classes here](http://daneden.github.io/animate.css/).

In our demo, we used the following in the three **Forum Icons** field.

| Option       | Setting                          |
| :----------  | :----------                      |
| Forum        | `fa fa-folder-open-o wow zoomIn` |
| Forum Linked | `fa fa-unlink wow zoomIn`        |
| Forum Locked | `fa fa-folder-o wow zoomIn`      |

The class name `wow zoomIn` sets the animation of each component to zoom in. The `wow` portion is the prefix, and `zoomIn` is the name of the animation. The `fa fa-(name)` classes set the **Font Awesome** icon used for each component.

Full-Image for Slideshow Module Position
-----

![][slideshow1]

:   1. **Full Slideshow** [45%, 78%, se]

One of the core features of Chimera's design is the full, bold header image. You don't *have* to use it on your site, but you do have the option. To turn it on, simply navigate to **Admin > Styles > Chimera > Settings** and switch the **Full Slideshow** option to **Yes**.

![][slideshow2]

:   1. **Demostyle Type** [55%, 59%, se]

If you want to customize the image that appears in the **Slideshow** position, you can do so by uploading it to `theme/images/background` and setting the **Demostyle Type** option to **Custom**. You will also need to add the name of the custom image file you have uploaded in the field directly below that.

[adminguide]: ../../start/styles.md#installing-administrative-modules
[style]: assets/chimera.jpeg
[slideshow1]: assets/slideshow1.jpeg
[animation1]: assets/animation1.jpeg
[slideshow2]: assets/slideshow2.jpeg
[rokbridge]: http://www.rockettheme.com/extensions-joomla/roklegacy
