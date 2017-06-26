---
title: Supra: Full Page Scroll Atom
description: Your Guide to Using the Supra Template for Joomla
breadcrumb: /grav:Grav/!themes:Themes/supra:Supra

---

## Introduction

One of the most requested features by the RocketTheme community for a new template has been full page scrolling. With this feature, you can modify your visitor's experience with your content by enabling or disabling a full-page section-by-section scroll.

The real beauty behind the Full Page Scrolling atom is that it enables you to set a breakpoint where scrolling goes from a normal smooth scroll to the full page experience. That way, mobile users can still experience a natural user environment while desktop users enjoy the visual experience this atom has to offer.

**Full Page Scroller** is powered by [FullPage.js](https://alvarotrigo.com/fullPage/).

## Setup

![](atom_fullpage1.jpeg)

To set up the atom, simply navigate to the **Page Settings** tab in the outline you wish to apply full page scrolling to and drag-and-drop the **Full Page Scrolling** atom into the white **Atoms** bar. This will activate the atom for the outline.

Next, you can access the atom's settings by selecting the cogwheel icon.

![](atom_fullpage2.jpeg)

| Setting                       | Description                                                                                                                                                                                                                                                                                                    |
| :-----                        | :-----                                                                                                                                                                                                                                                                                                         |
| Custom Section Selector Class | Defines the selector used for the atom sections.                                                                                                                                                                                                                                                               |
| Custom Slide Selector Class   | Defines the selector used for the atom slides.                                                                                                                                                                                                                                                                 |
| Responsive Width              | (default 0) A normal scroll will be used under the defined width in pixels. A class `fp-responsive` is added to the body tag in case the user wants to use it for his own responsive CSS. For example, if set to 900, whenever the browser's width is less than 900 the atom will scroll like a normal site.   |
| Responsive Height             | (default 0) A normal scroll will be used under the defined height in pixels. A class `fp-responsive` is added to the body tag in case the user wants to use it for his own responsive CSS. For example, if set to 900, whenever the browser's height is less than 900 the atom will scroll like a normal site. |

![](atom_fullpage3.jpeg)

You will notice in the **Home** layout preset that sections have a `section` CSS class applied. This enables Full Page Scrolling to work with these sections. A good rule of thumb is if you are using the Full Page Scrolling atom in an outline, apply that CSS class to any sections you use in the outline you'd like to have that section-by-section scrolling apply to.