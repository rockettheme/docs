---
title: Isotope: Recreating the Demo - Showcase Section
description: Your Guide to Recreating Elements of the Isotope Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/isotope:Isotope

---

## Introduction

![](assets/demo_3.jpeg)

:	1. **FlexSlider** [10%, 20%, se]
	2. **Custom HTML** [90%, 40%, se]

The **Showcase** section includes one module position, **Showcase A**. In that module position we assigned two **Gantry 5 Particle** modules. One being a **FlexSlider** particle, and the other a **Custom HTML** particle..

![](assets/home_showcase.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Module Position (showcase-a)](#module-position-(showcase-a))
	* [FlexSlider (particle)](#flexslider-(particle))
	* [Custom HTML (particle)](#custom-html-(particle))

## Section Settings

![](assets/demo_showcase_settings.jpeg)

| Option           | Setting                   |
| :--------------- | :----------               |
| Layout           | Fullwidth (Boxed Content) |
| CSS Classes      | Blank                     |
| Tag Attributes   | Blank                     |

## Module Position (showcase-a)

### Particle Settings

![Demo Showcase](demo_showcase_1.jpeg)

| Option        | Setting      |
| :-----        | :-----       |
| Particle Name | `Showcase`   |
| Key           | `showcase-a` |
| Chrome        | `gantry`     |

### Block Settings

![Demo Showcase](demo_showcase_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

### Assigned Particle(s)

Using the **Gantry 5 Particle** module, we assigned **FlexSlider** and **Custom HTML** particles to this position. You will find the settings used in these particles, below.

#### FlexSlider (Particle)

##### Particle Settings

![Demo Showcase](demo_showcase_3.jpeg)

| Option                                 | Setting                                                                                                                            |
| :-----                                 | :-----                                                                                                                             |
| Particle Name                          | `FlexSlider`                                                                                                                       |
| CSS Classes                            | Blank                                                                                                                              |
| Title                                  | Blank                                                                                                                              |
| Layout                                 | `Testimonial`                                                                                                                      |
| Thumbnail Width                        | `150`                                                                                                                              |
| Autoplay                               | Disable                                                                                                                            |
| Autoplay Speed                         | `5000`                                                                                                                             |
| Pause on Hover                         | `Enable`                                                                                                                           |
| RTL Mode                               | `Disable`                                                                                                                          |
| FlexSlider Item 1 Name                 | `Testimonial 1`                                                                                                                    |
| FlexSlider Item 1 Background Image     | Blank                                                                                                                              |
| FlexSlider Item 1 Overlay Image        | Blank                                                                                                                              |
| FlexSlider Item 1 Overlay Parallax     | Enabled                                                                                                                            |
| FlexSlider Item 1 Parallax Ratio       | `0.3`                                                                                                                              |
| FlexSlider Item 1 Title                | Blank                                                                                                                              |
| FlexSlider Item 1 Description          | `Headroom allows for select sections to scroll with the page, and hide dynamically. Just apply the g-headroom class to a section.` |
| FlexSlider Item 1 Testimonial Image    | Custom                                                                                                                             |
| FlexSlider Item 1 Testimonial Name     | `Taylor Jackson`                                                                                                                   |
| FlexSlider Item 1 Testimonial Position | `CEO of Kuceeng, Inc.`                                                                                                             |
| FlexSlider Item 1 Link                 | Blank                                                                                                                              |
| FlexSlider Item 1 Link Text            | Blank                                                                                                                              |
| FlexSlider Item 1 Target               | Self                                                                                                                               |
| FlexSlider Item 1 Button Class         | Blank                                                                                                                              |

#### Custom HTML (Particle)

##### Particle Settings

![Demo Showcase](demo_showcase_4.jpeg)

| Option             | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Unchecked     |

**Custom HTML**
~~~ .html
<div class="title-center">
	<h2 class="g-title largetopspace">What We Made Recently</h2>
</div>
~~~
