---
title: Ricochet: Tips and Tricks
description: Your Guide to Using the Ricochet Style for phpBB.
breadcrumb: /phpbb:phpBB/!styles:Styles/!ricochet:Ricochet/
tags: [Style, Template, Theme, Features, Description, Tutorials, rokBB 5]

---

Introduction
-----

The **Ricochet** design for phpBB comes with several features that set it apart from other phpBB styles. We have outlined some tips and tricks to help you make the most of the style below.

Animation
-----

![][animation1]

The animated elements that trigger as you scroll down the page are handled via classes applied to HTML elements, icons etc. You can access **Ricochet's** main settings area by navigating to **Admin > Styles > Ricochet**. From here, you will want to select the **Imageset Editor** tab where you can find the **Forum Icons** settings. In these fields, you can enter the tag of the animation(s) you wish to use. You can find a list (as well as visual examples) of these [animation classes here](http://daneden.github.io/animate.css/).

In our demo, we used the following in the three **Forum Icons** field.

| Option       | Setting                          |
| :----------  | :----------                      |
| Forum        | `fa fa-folder-open-o wow zoomIn` |
| Forum Linked | `fa fa-unlink wow zoomIn`        |
| Forum Locked | `fa fa-folder-o wow zoomIn`      |

The class name `wow zoomIn` sets the animation of each component to zoom in. The `wow` portion is the prefix, and `zoomIn` is the name of the animation. The `fa fa-(name)` classes set the **Font Awesome** icon used for each component.

SideSlider
-----

![][sideslider1]

The SideSlider adds additional space for content outside of the main style area. There are several options available for configuring the SideSlider feature, such as the toggle or whether it is fixed or slides into view. The position is perfect for extra content or advertisements.

![][sideslider2]

You can configure the SideSlider's text, background color, and set it to either dynamic or static by navigating to **Admin > Styles > Ricochet > Settings** and toggling the features there.

[adminguide]: ../../start/styles.md#installing-administrative-modules
[style]: assets/ricochet.jpeg
[sideslider1]: assets/sideslider_1.png
[animation1]: assets/animation_1.jpeg
[sideslider2]: assets/sideslider_2.jpeg
[rokbridge]: http://www.rockettheme.com/extensions-joomla/rokbridge
