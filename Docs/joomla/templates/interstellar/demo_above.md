---
title: Interstellar: Recreating the Demo - Above Section
description: Your Guide to Recreating Elements of the Interstellar Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/interstellar:Interstellar

---

## Introduction

![](assets/demo_4.jpeg)

:   1. **Spacer** [40%, 5%, se]
    2. **Simple Content** [40%, 40%, se]
    3. **Simple Content** [40%, 70%, se]

The **Above** section includes three particles: **Spacer**, **Simple Content**, and **Simple Content**. The **Spacer** particle is placed directly in the **Above** section, while the two **Simple Content** particles are assigned to the **above-b** and **above-c** module positions.

![](assets/home_above.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Spacer (particle)](#spacer-(particle))
* [Simple Content (particle)](#simple-content-(particle))
* [Simple Content (Particle)](#simple-content-(particle)-2)

## Section Settings

![](assets/demo_above_settings.jpeg)

| Option           | Setting                   |
| :--------------- | :----------               |
| Layout           | Fullwidth (Boxed Content) |
| CSS Classes      | Blank                     |
| Tag Attributes   | Blank                     |

## Spacer (Particle)

### Particle Settings

![Demo Above](demo_above_1.jpeg)

### Block Settings

![Demo Above](demo_above_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `40%`     |

## Simple Content (Particle)

The **Simple Content** particle is a **Gantry 5 Particle** module placed within the **above-b** module position. You can create a module position by dragging and dropping a **Module Position** particle into the desired location within the **Layout Manager**. The module position's settings are as follows.

### Module Position Particle Settings

#### Particle Settings

![Demo Above](demo_above_3.jpeg)

| Option        | Setting         |
| :-----        | :-----          |
| Particle Name | `FP Above B` |
| Key           | `above-b`    |
| Chrome        | `gantry`        |

#### Block Settings

![Demo Above](demo_above_4.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `30%`     |

### Simple Content Particle Settings

The next step involves assigning the particle to the module position. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module by navigating to **Admin > Extensions > Modules** and clicking the green **New** button. Select the **Gantry 5 Particle** module type and create the particle using the settings found in the section below, and assigning it to the position.

#### Particle Settings

![Demo Above](demo_above_5.jpeg)

| Option                   | Setting                                                                                                                                                                     |
| :-----                   | :-----                                                                                                                                                                      |
| Particle Name            | `Simple Content`                                                                                                                                                            |
| CSS Classes              | Blank                                                                                                                                                                       |
| Title                    | Blank                                                                                                                                                                       |
| Item 1 Name              | `Our Office`                                                                                                                                                                |
| Item 1 Layout Style      | Standard                                                                                                                                                                    |
| Item 1 Created Date      | Blank                                                                                                                                                                       |
| Item 1 Content Title     | `Our Office`                                                                                                                                                                |
| Item 1 Author            | Blank                                                                                                                                                                       |
| Item 1 Leading Content   | `Interstellar was handcrafted by the talented RocketTheme team on the incredible Gantry 5 framework. It was designed to be a perfect match for a wide variety of websites.` |
| Item 1 Main Content      | Blank                                                                                                                                                                       |
| Item 1 Read More Label   | Blank                                                                                                                                                                       |
| Item 1 Read More Link    | Blank                                                                                                                                                                       |
| Item 1 Read More Classes | Blank                                                                                                                                                                       |
| Item 1 Target            | Self                                                                                                                                                                        |

## Simple Content (Particle) 2

The **Simple Content** particle is a **Gantry 5 Particle** module placed within the **above-c** module position. You can create a module position by dragging and dropping a **Module Position** particle into the desired location within the **Layout Manager**. The module position's settings are as follows.

### Module Position Particle Settings

#### Particle Settings

![Demo Above](demo_above_6.jpeg)

| Option        | Setting      |
| :-----        | :-----       |
| Particle Name | `FP Above C` |
| Key           | `above-c`    |
| Chrome        | `gantry`     |

#### Block Settings

![Demo Above](demo_above_7.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `30%`     |

### Simple Content Particle Settings

The next step involves assigning the particle to the module position. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module by navigating to **Admin > Extensions > Modules** and clicking the green **New** button. Select the **Gantry 5 Particle** module type and create the particle using the settings found in the section below, and assigning it to the position.

#### Particle Settings

![Demo Above](demo_above_8.jpeg)

| Option                   | Setting          |
| :-----                   | :-----           |
| Particle Name            | `Simple Content` |
| CSS Classes              | Blank            |
| Title                    | Blank            |
| Item 1 Name              | `Contact Info`   |
| Item 1 Layout Style      | Standard         |
| Item 1 Created Date      | Blank            |
| Item 1 Content Title     | `Contact Info`   |
| Item 1 Author            | Blank            |
| Item 1 Main Content      | Blank            |
| Item 1 Read More Label   | Blank            |
| Item 1 Read More Link    | Blank            |
| Item 1 Read More Classes | Blank            |
| Item 1 Target            | Self             |

**Item 1 Leading Content**
~~~ .html
<br /><br />
<div class="info2"><strong><i class="fa fa-map-marker"></i> Interstellar  LTD.</strong> <br />
ul. Szarych Szeregów 10/28 <br />
15-666 Białystok <br />
Poland <br />
<i class="fa fa-phone"></i> 555 555 555 <br />
<i class="fa fa-envelope-o"></i> office@interstellar.co <br />
</div>
~~~