---
title: Topaz: Recreating the Demo - Slideshow Section
description: Your Guide to Recreating Elements of the Topaz Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/topaz:Topaz

---

## Introduction

![](assets/demo_3.jpg)

The **Slideshow** area of the page is made up of three columned sections wrapped in a **Container**. **Slideshow Left** and **Slideshow Right** do not appear on the front end as they have no assigned content. However, there is a **Slideshow A** widget position in the **Slideshow Main** section which contains three different particles: **Grid Statistic**, **Custom HTML**, and **Grav Pages**.

![](assets/home_slideshow.jpg)

Here is a breakdown of the widget(s) and particle(s) that appear in these sections:

* [Container](#container)
    - Slideshow Left
    - [Slideshow Main](#slideshow-main)
        + [Owl Carousel (particle)](#owl-carousel-(particle))
    - Slideshow Right

## Container

![](assets/demo_slideshow_1.jpg)

| Option         | Setting          |
| :-----         | :-----           |
| Layout         | Remove Container |
| CSS Classes    | Blank            |
| Tag Attributes | Blank            |

The container wrapping the **Slideshow** sections enables the three sections to exist within a single horizontal space. 

## Slideshow Main

The **Slideshow Main** section hosts the **Owl Carousel** particle on the front page. You will find the settings used in the section below.

### Section Settings

![](assets/demo_slideshow_2.jpg)

| Option         | Setting        |
| :-----         | :-----         |
| CSS Classes    | `fp-slideshow` |
| Tag Attributes | Blank          |

### Section Block Settings

![](assets/demo_slideshow_3.jpg)

| Option         | Setting           |
| :-----         | :-----            |
| CSS ID         | Blank             |
| CSS Classes    | `g-middle-column` |
| Variations     | Blank             |
| Tag Attributes | Blank             |
| Fixed Size     | Checked           |
| Block Size     | `70%`             |

#### Slideshow A (Widget Position)

##### Particle Settings

![](assets/demo_slideshow_4.jpg)

| Option | Setting      |
| :----- | :-----       |
| Key    | `slideshow-a` |
| Chrome | `gantry`     |

##### Block Settings

![](assets/demo_slideshow_5.jpg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

##### Owl Carousel (Particle)

![](assets/demo_slideshow_6.jpg)

The **Owl Carousel** particle is assigned to the **Slideshow A** widget position. This is done by creating a **Gantry 5 Particle** widget and assigning it to the **slideshow-a** position, then selecting **Owl Carousel** as the **Particle** in the widget's settings. You will find its settings below.

| Option                             | Setting                                                                                                                                                       |
| :-----                             | :-----                                                                                                                                                        |
| CSS Classes                        | Blank                                                                                                                                                         |
| Content Source                     | Particle                                                                                                                                                      |
| Display at Once                    | `1`                                                                                                                                                           |
| Title                              | Blank                                                                                                                                                         |
| Description                        | Blank                                                                                                                                                         |
| Layout                             | NewsSlider                                                                                                                                                    |
| Width                              | Full Width                                                                                                                                                    |
| In Animation                       | fadeIn                                                                                                                                                        |
| Out Animation                      | fadeOut                                                                                                                                                       |
| Prev Next                          | Disable                                                                                                                                                       |
| Prev Text                          | Blank                                                                                                                                                         |
| Next Text                          | Blank                                                                                                                                                         |
| Dots                               | Disable                                                                                                                                                       |
| Loop                               | Enable                                                                                                                                                        |
| Autoplay                           | Disable                                                                                                                                                       |
| Autoplay Speed                     | `5000`                                                                                                                                                        |
| Pause on Hover                     | Enable                                                                                                                                                        |
| Owl Carousel Item 1 Name           | `Item 1`                                                                                                                                                      |
| Owl Carousel Item 1 Image          | Custom                                                                                                                                                        |
| Owl Carousel Item 1 Icon           | `fa fa-compass`                                                                                                                                               |
| Owl Carousel Item 1 Title          | `Item 1`                                                                                                                                                      |
| Owl Carousel Item 1 Subtitle       | `Heading`                                                                                                                                                     |
| Owl Carousel Item 1 Author         | `Grace Kelly`                                                                                                                                                 |
| Owl Carousel Item 1 Author Image   | Custom                                                                                                                                                        |
| Owl Carousel Item 1 Description    | `Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.` |
| Owl Carousel Item 1 Link           | Blank                                                                                                                                                         |
| Owl Carousel Item 1 Link Text      | Blank                                                                                                                                                         |
| Owl Carousel Item 1 Target         | Self                                                                                                                                                          |
| Owl Carousel Item 1 Button Classes | Blank                                                                                                                                                         |

![](assets/demo_slideshow_7.jpg)

| Option            | Setting     |
| :-----            | :-----      |
| Grav Categories | Blank       |
| Pages to Fetch | `1`         |
| Intro Image       | Enable      |
| Categories Names  | Enable      |
| Article Title     | Enable      |
| Intro Text        | Enable      |
| Author            | Enable      |
| Link              | Enable      |
| Link Text         | `Read More` |