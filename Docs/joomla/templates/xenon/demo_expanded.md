---
title: Xenon: Recreating the Demo - Expanded Section
description: Your Guide to Recreating Elements of the Xenon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/xenon:Xenon

---

## Introduction

![](assets/demo_8.jpeg)

The **Expanded** section includes a single **News Slider** particle assigned to the **expanded-a** module position.

![](assets/home_expanded.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [News Slider (particle)](#news-slider-(particle))

## Section Settings

![](assets/demo_expanded_settings.jpeg)

| Option           | Setting     |
| :--------------- | :---------- |
| Layout           | Boxed       |
| CSS Classes      | Blank       |
| Tag Attributes   | Blank       |

## News Slider (Particle)

The **News Slider** particle was placed within the **expanded-a** module position. This was done to make it easier for users of the RocketLauncher to replace this item with a module if they so desired. It also makes it possible to set CSS classes and variations for the whole position rather than on a per-item basis. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module and assigning it to the position.

### Module Position Particle Settings

#### Particle Settings

![Demo Expanded](demo_expanded_1.jpeg)

| Option        | Setting        |
| :-----        | :-----         |
| Particle Name | `FP Expanded A` |
| Key           | `expanded-a`    |
| Chrome        | `gantry`       |

#### Block Settings

![Demo Expanded](demo_expanded_2.jpeg)

| Option         | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `fp-expanded-a` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Fixed Size     | Unchecked      |
| Block Size     | `100%`         |

### News Slider Particle Settings

#### Particle Settings

![Demo Expanded](demo_expanded_3.jpeg)

| Option                    | Setting                                                                                                                                                                                                                                                       |
| :-----                    | :-----                                                                                                                                                                                                                                                        |
| Particle Name             | `News Slider`                                                                                                                                                                                                                                                 |
| CSS Classes               | Blank                                                                                                                                                                                                                                                         |
| Title                     | Blank                                                                                                                                                                                                                                                         |
| Height                    | `500px`                                                                                                                                                                                                                                                       |
| Item 1 Name               | `The Gantry 5 Framework is the powerhouse behind the Xenon template`                                                                                                                                                                                          |
| Item 1 Subtitle           | `For Joomla & WordPress`                                                                                                                                                                                                                                      |
| Item 1 Header Description | `The latest version of the framework is a ground-up rewrite, focusing on performance and intuitive features`                                                                                                                                                  |
| Item 1 Description        | `Gantry 5 offers several new features, for both end users and developers, such as the drag & drop interface for both the Layout Manager and Menu Editor. Alongside are powerful development features, such as Twig, YAML, SASS and extensive overridability.` |
| Item 1 Button Label       | `Read More`                                                                                                                                                                                                                                                   |
| Item 1 Button Link        | `#`                                                                                                                                                                                                                                                           |
| Item 1 Target             | Self                                                                                                                                                                                                                                                          |
| Item 1 Button Classes     | `button-2`                                                                                                                                                                                                                                                    |
