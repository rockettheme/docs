---
title: Xenon: Recreating the Demo - Top Section
description: Your Guide to Recreating Elements of the Xenon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/xenon:Xenon

---

## Introduction

![](assets/demo_1.jpeg)

:   1. **Logo (Particle)** [10%, 2%, se]
    2. **Overlay Toggle (Particle)** [10%, 65%, se]
    3. **Social (Particle)** [10%, 90%, se]

The **Top** section includes three particles, **Logo**, **Overlay Toggle**, and **Social**. Both the **Overlay Toggle** and **Social** particles are placed within module positions.

![](assets/home_top.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Logo (particle)](#logo-(particle))
* [Overlay Toggle (Particle)](#overlay-toggle-(particle))
* [Social (Particle)](#social-(particle))

## Section Settings

![](assets/demo_top_settings.jpeg)

| Option           | Setting     |
| :--------------- | :---------- |
| Layout           | Boxed       |
| CSS Classes      | Blank       |
| Tag Attributes   | Blank       |

## Logo (Particle)

### Particle Settings

![Demo Top](demo_top_1.jpeg)

| Option        | Setting                |
| :-----        | :-----                 |
| Particle Name | `Logo`                 |
| URL           | Blank                  |
| Image         | Blank                  |
| Text          | `Xenon`                |
| Tagline       | `Vibrant and Elegant.` |
| CSS Classes   | `g-logo`               |

### Block Settings

![Demo Top](demo_top_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `50%`     |

## Overlay Toggle (Particle)

The **Overlay Toggle** particle was placed within the **top-a** module position. This was done to make it easier for users of the RocketLauncher to replace this item with a module if they so desired. It also makes it possible to set CSS classes and variations for the whole position rather than on a per-item basis. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module and assigning it to the position.

### Module Position Particle Settings

#### Particle Settings

![Demo Top](demo_top_3.jpeg)

| Option        | Setting    |
| :-----        | :-----     |
| Particle Name | `FP Top A` |
| Key           | `top-a`    |
| Chrome        | `gantry`   |

#### Block Settings

![Demo Top](demo_top_4.jpeg)

| Option         | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `fp-top-a` |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Fixed Size     | Unchecked  |
| Block Size     | `30%`      |

### Overlay Toggle Particle Settings

#### Particle Settings

![Demo Top](demo_top_5.jpeg)

| Option        | Setting               |
| :-----        | :-----                |
| Particle Name | `Overlay Toggle`      |
| CSS Classes   | Blank                 |
| Title         | Blank                 |
| Menu Text     | `Pricing Information` |

## Social (Particle)

The **Social** particle was placed within the **top-b** module position. This was done to make it easier for users of the RocketLauncher to replace this item with a module if they so desired. It also makes it possible to set CSS classes and variations for the whole position rather than on a per-item basis. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module and assigning it to the position.

### Module Position Particle Settings

#### Particle Settings

![Demo Top](demo_top_6.jpeg)

| Option        | Setting    |
| :-----        | :-----     |
| Particle Name | `FP Top B` |
| Key           | `top-b`    |
| Chrome        | `gantry`   |

#### Block Settings

![Demo Top](demo_top_7.jpeg)

| Option         | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `fp-top-b` |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Fixed Size     | Unchecked  |
| Block Size     | `20%`      |

### Social Particle Settings

#### Particle Settings

![Demo Top](demo_top_8.jpeg)

| Option             | Setting                               |
| :-----             | :-----                                |
| Particle Name      | `Social`                              |
| CSS Classes        | `social`                              |
| Title              | Blank                                 |
| Target             | Self                                  |
| Social Item 1 Name | `Facebook`                            |
| Social Item 1 Icon | `fa fa-facebook fa-fw`                |
| Social Item 1 Text | Blank                                 |
| Social Item 1 Link | `http://www.facebook.com/RocketTheme` |
