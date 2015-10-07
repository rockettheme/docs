---
title: Kraken: Recreating the Demo - FixedSide Section
description: Your Guide to Recreating Elements of the Kraken Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kraken:Kraken

---

## Introduction

![](assets/demo_1.png)

:   1. **Logo (Particle)** [10%, 20%, se]
    2. **Social (Particle)** [40%, 20%, se]
    3. **Side Menu (Particle)** [60%, 20%, se]

The **FixedSide** section includes two particles, each arranged in its own row in the section.

![](assets/home_fixedside.png)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Logo (particle)](#logo-(particle))
* [Social (particle)](#social-(particle))
* [Module Position (fixedside)](#fixedside-(module-position))
    - [Side Menu (Particle)](#gantry-5-particle-(side-menu))

## Section Settings

![](assets/demo_fixedside_settings.png)

| Option         | Setting   |
| :-----         | :-----    |
| Layout         | Fullwidth |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |

## Style Settings

![](assets/demo_fixedside_style.png)

The settings present in the **Style** administrative panels are 

| Option          | Setting   |
| :-----          | :-----    |
| Background      | `#151a23` |
| Text            | `#ffffff` |
| FixedSide Width | `12rem`   |
| Position        | Left      |

## Logo (particle)

#### Particle Settings

![Demo FixedSide](demo_fixedside_1.png)

| Option        | Setting            |
| :-----        | :-----             |
| Particle Name | `Logo`             |
| URL           | Blank              |
| Rel           | Blank              |
| Image         | Custom             |
| Alt           | `Kraken`           |
| Text          | `Kraken`           |
| CSS Classes   | `g-fixedside-logo` |

#### Block Settings

![Demo FixedSide](demo_fixedside_2.png)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

## Social (particle)

#### Particle Settings

![Demo FixedSide](demo_fixedside_3.png)

| Option             | Setting               |
| :-----             | :-----                |
| CSS Classes        | `social`              |
| Title              | Blank                 |
| Target             | New Window            |
| Social Item 1 Name | `Twitter`             |
| Social Item 1 Icon | `fa fa-twitter fa-fw` |
| Social Item 1 Text | Blank                 |
| Social Item 1 Link | `#`                   |

#### Block Settings

![Demo FixedSide](demo_fixedside_4.png)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

## FixedSide (module position)

#### Particle Settings

![Demo Feature](assets/demo_fixedside_5.png)

| Option | Setting     |
| :----- | :-----      |
| Key    | `fixedside` |
| Chrome | gantry      |

#### Block Settings

![Demo Feature](assets/demo_fixedside_6.png)

| Option         | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

### Assigned Module(s)

#### Gantry 5 Particle (Side Menu)

We added a **Side Menu** particle to the `fixedside` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Side Menu** particle in the module's settings. 

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Feature](assets/demo_fixedside_7.png)

| Option                      | Setting                                                                     |
| :-----                      | :-----                                                                      |
| Particle Name               | `Side Menu`                                                                 |
| Menu                        | Use Default Menu                                                            |
| Base Item                   | Active                                                                      |
| Start Level                 | `1`                                                                         |
| Max Levels                  | `2`                                                                         |
| Render Titles               | Unchecked                                                                   |
| Mobile Target               | Unchecked                                                                   |
