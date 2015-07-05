---
title: Ambrosia: Recreating the Demo - Feature Section
description: Your Guide to Recreating Elements of the Ambrosia Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ambrosia:Ambrosia

---

## Introduction

![](assets/demo_feature.jpeg)

:   1. **Feature A - RokSprocket (Tabs)** [17%, 7%, se]
    2. **Feature B - RokSprocket (Headlines)** [70%, 7%, se]

The **Feature** section contains two **Module Position** particles set in two rows. These particles create the `feature-a` and `feature-b` positions, which are host to **RokSprocket (Tabs)** and **RokSprocket (Headlines)** modules.

Here is a breakdown of the modules and particles that appear in this section:

* [Module Position (feature-a)](#module-position-(feature-a))
    * [RokSprocket (Tabs)](#assigned-module(s)---roksprocket-(tabs))
        * [Gantry 5 Particle (Module)](#gantry-5-particle-(module))
            * [Tab Image (Particle)](#tab-image-(particle))
* [Module Position (feature-b)](#module-position-(feature-b))
    * [RokSprocket (Headlines)](#assigned-module(s)---roksprocket-(headlines))

![](assets/home_feature.jpeg)

Settings used in the demo for the particle used in this section can be found below.

## Section Settings

![](assets/demo_feature_1.jpeg)

| Field          | Setting   |
| :-----         | :-----    |
| Layout         | Fullwidth |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |

## Module Position (feature-a)

There is an important aspect of this module position used in our demo you should be aware of. First, the `feature-a` module position contains a RokSprocket (Tabs) module. This module loads multiple module positions through its simple items' descriptions. These module positions are then used to assign **Gantry 5 Particle** modules which enable you to embed Gantry 5 particles within RokSprocket.

### Particle Settings

![](assets/demo_feature_2.jpeg)

| Field         | Setting                    |
| :-----        | :-----                     |
| Particle Name | `RokSprocket Tabs Feature` |
| Key           | `feature-a`                |
| Chrome        | `gantry`                   |

### Block Settings

![](assets/demo_feature_3.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | `flush` |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

### Assigned Module(s) - RokSprocket (Tabs)

The `feature-features` module position is host to a single **RokSprocket** module.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket module to an article. You can find examples of the **Simple** items used in this module in the **Filtered Article List** section below.

#### Details

![](assets/demo_feature_4.jpeg)

| Option           | Setting                       |
| :-----           | :-----                        |
| Title            | `FP RokSprocket Tabs Feature` |
| Show Title       | Hide                          |
| Access           | Public                        |
| Position         | `feature-a`                   |
| Status           | Published                     |
| Content Provider | Simple                        |
| Type             | Tabs                          |

#### Filtered Article List

##### Item 1

| Option      | Setting                         |
| :-----      | :-----                          |
| Tab Label   | `News`                          |
| Icon        | None                            |
| Link        | None                            |
| Description | `{loadposition feature-tabs-1}` |

##### Item 2

| Option      | Setting                         |
| :-----      | :-----                          |
| Tab Label   | `Games`                         |
| Icon        | None                            |
| Link        | None                            |
| Description | `{loadposition feature-tabs-2}` |

##### Item 3

| Option      | Setting                         |
| :-----      | :-----                          |
| Tab Label   | `Reviews`                       |
| Icon        | None                            |
| Link        | None                            |
| Description | `{loadposition feature-tabs-3}` |

>> NOTE: The description fields for these items load module positions (for example: `feature-tabs-1`), which have been assigned **Gantry 5 Particle** modules, each of which contain a single **Tab Image** particle. You will find the details for the **Tab Image** particle assigned to the **Gantry 5 Particle** module, and assigned to the `feature-tabs-1` position loaded in the `News` tab in the [Tab Image](#tab-image-(particle)) section below.

#### Layout Options

![](assets/demo_feature_5.jpeg)

| Option                | Setting               |
| :-----                | :-----                |
| Theme                 | Default               |
| Display Limit         | `∞`                   |
| Tabs Position         | Right                 |
| Animation             | Fade                  |
| Autoplay              | Disable               |
| Autoplay Delay        | `5`                   |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

#### Advanced

![](assets/demo_feature_6.jpeg)

| Option              | Setting |
| :-----              | :-----  |
| Module Class Suffix | Blank   |

### Gantry 5 Particle (Module)

In this section, we will cover one of the embedded particles that appear in the **RokSprocket** module assigned to the `feature-a` position. This **Gantry 5 Particle** module loads a single **Tab Image** particle.

#### Details

![](assets/demo_feature_7.jpeg)

| Option     | Setting             |
| :-----     | :-----              |
| Title      | `FP Feature Tabs 1` |
| Show Title | Hide                |
| Position   | `feature-tabs-1`    |
| Particle   | Tab Image           |

### Tab Image (Particle)

#### Particle Settings

![](assets/demo_feature_8.jpeg)

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Tab Image` |
| CSS Classes   | Blank       |
| Title         | None        |

#### Tab Image Example

![](assets/demo_feature_9.jpeg)

| Field               | Setting                                                             |
| :-----              | :-----                                                              |
| Tab Image 1 Name    | `Layout - Drag & Drop`                                              |
| Tab Image 1 Image   | Custom                                                              |
| Tab Image 1 Link    | `#`                                                                 |
| Tab Image 1 Label   | `Read More`                                                         |
| Tab Image 1 Text    | `Unlimited layout possibilities powered by a drag & drop interface` |
| Tab Image 1 Tag     | `Layout`                                                            |
| Tab Image 1 Sub Tag | `Drag & Drop`                                                       |

## Module Position (feature-b)

### Particle Settings

![](assets/demo_feature_10.jpeg)

| Field         | Setting                 |
| :-----        | :-----                  |
| Particle Name | `RokSprocket Headlines` |
| Key           | `feature-b`             |
| Chrome        | `gantry`                |

### Block Settings

![](assets/demo_feature_11.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Box 1   |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

### Assigned Module(s) - RokSprocket (Headlines)

The `feature-b` module position is host to a single **RokSprocket** module.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket module to an article. You can find examples of the **Simple** items used in this module in the **Filtered Article List** section below.

#### Details

![](assets/demo_feature_12.jpeg)

| Option           | Setting                            |
| :-----           | :-----                             |
| Title            | `FP RokSprocket Headlines Feature` |
| Show Title       | Hide                               |
| Access           | Public                             |
| Position         | `feature-b`                        |
| Status           | Published                          |
| Content Provider | Simple                             |
| Type             | Headlines                          |

#### Filtered Article List

##### Item 1

| Option      | Setting                                                               |
| :-----      | :-----                                                                |
| Image       | None                                                                  |
| Link        | `#`                                                                   |
| Description | `Gantry 5's new layout manager features drag-and-drop functionality.` |

##### Item 2

| Option      | Setting                                                                      |
| :-----      | :-----                                                                       |
| Image       | None                                                                         |
| Link        | `#`                                                                          |
| Description | `The Particles system makes it easy to create and configure content blocks.` |

##### Item 3

| Option      | Setting                                                                 |
| :-----      | :-----                                                                  |
| Image       | None                                                                    |
| Link        | `#`                                                                     |
| Description | `Menu Editor allows for inserting Modules and adding icons in seconds.` |

#### Layout Options

![](assets/demo_feature_13.jpeg)

| Option                | Setting               |
| :-----                | :-----                |
| Theme                 | Default               |
| Display Limit         | `∞`                   |
| Label Text            | `Newsflash`           |
| Preview Length        | `∞`                   |
| Strip HTML Tags       | Yes                   |
| Arrow Navigation      | Show                  |
| Animation             | Fade                  |
| Autoplay              | Disable               |
| Autoplay Delay        | `5`                   |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

#### Advanced

![](assets/demo_feature_14.jpeg)

| Option              | Setting                           |
| :-----              | :-----                            |
| Module Class Suffix | `g-roksprocket-headlines-style-1` |
