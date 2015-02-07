---
title: Sirocco: Tips and Tricks
description: Your Guide to Using the sirocco Style for phpBB.
breadcrumb: /phpbb:phpBB/!styles:Styles/!sirocco:Sirocco/
tags: [Style, Template, Theme, Features, Description, Tutorials, rokBB 5]

---

Introduction
-----

The **Sirocco** design for phpBB comes with several features that set it apart from other phpBB styles. We have outlined some tips and tricks to help you make the most of the style below.

Animation
-----

![Animation](animation.png)

The animated elements that trigger as you scroll down the page are handled via classes applied to HTML elements, icons etc. You can access **Sirocco's** main settings area by navigating to **Admin > Styles > Sirocco**. From here, you will want to select the **Imageset Editor** tab where you can find the **Forum Icons** settings. In these fields, you can enter the tag of the animation(s) you wish to use. You can find a list (as well as visual examples) of these [animation classes here](http://daneden.github.io/animate.css/).

In our demo, we used the following in the three **Forum Icons** field.

| Option       | Setting                          |
| :----------  | :----------                      |
| Forum        | `fa fa-folder-open-o wow zoomIn` |
| Forum Linked | `fa fa-unlink wow zoomIn`        |
| Forum Locked | `fa fa-folder-o wow zoomIn`      |

The class name `wow zoomIn` sets the animation of each component to zoom in. The `wow` portion is the prefix, and `zoomIn` is the name of the animation. The `fa fa-(name)` classes set the **Font Awesome** icon used for each component.

