---
title: Ethereal: Recreating the Demo - Copyright Section
description: Your Guide to Recreating Elements of the Ethereal Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ethereal:Ethereal

---

## Introduction

![](assets/demo_copyright.jpeg)

:   1. **Logo (Particle)** [25%, 5%, se]
    2. **Custom HTML (Particle)** [25%, 35%, se]
    3. **Copyright (Particle)** [65%, 5%, se]
    4. **Horizontal Menu (Particle)** [65%, 35%, se]
    5. **To Top (Particle)** [65%, 85%, se]

The **Copyright** section is made up of five particles displaying various information about the site, including its **Logo**, **Demo Information**, **Copyright**, a **Horizontal Menu**, and a **To Top** button.

Here is a breakdown of the particles that appear in this section:

* [Logo (Particle)](#logo-(particle))
* [Custom HTML (Particle)](#custom-html-(particle))
* [Copyright (Particle)](#copyright-(particle))
* [Horizontal Menu (Particle)](#horizontal-menu-(particle))
* [To Top (Particle)](#to-top-(particle))

![](assets/home_copyright.jpeg)

Settings used in the demo for the particle used in this section can be found below.

## Section Settings

![](assets/demo_copyright_settings.jpeg)

| Field          | Setting   |
| :-----         | :-----    |
| Layout         | Fullwidth |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |

### Logo (Particle)

#### Particle Settings

![Demo Copyright](demo_copyright_1.jpeg)

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Logo`     |
| URL           | Blank      |
| Image         | Custom     |
| Text          | `Ethereal` |
| CSS Classes   | `g-logo`   |

#### Block Settings

![Demo Copyright](demo_copyright_2.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `33%`   |

### Custom HTML (Particle)

#### Particle Settings

![Demo Copyright](demo_copyright_3.jpeg)

| Field           | Setting            |
| :-----          | :-----             |
| Particle Name   | `Demo Information`        |

**Custom HTML**
~~~ .html
<div class="g-tag"><a href="#">Demo Information</a></div>

<p>All demo content is for sample purposes only, intended to represent a live site. All content images are licensed from their respective sources for exclusive use on this demo only.</p>
~~~

#### Block Settings

![Demo Copyright](demo_copyright_4.jpeg)

| Field          | Setting           |
| :-----         | :-----            |
| CSS ID         | Blank             |
| CSS Classes    | `bordered-bottom` |
| Variations     | Blank             |
| Tag Attributes | Blank             |
| Block Size     | `67%`             |

### Copyright (Particle)

#### Particle Settings

![Demo Copyright](demo_copyright_5.jpeg)

| Field           | Setting           |
| :-----          | :-----            |
| Particle Name   | `Copyright`       |
| Start Year      | `2007`            |
| End Year        | `now`             |
| Copyright Owner | `RocketTheme LLC` |

#### Block Settings

![Demo Copyright](demo_copyright_6.jpeg)

| Field          | Setting       |
| :-----         | :-----        |
| CSS ID         | Blank         |
| CSS Classes    | `g-copyright` |
| Variations     | Blank         |
| Tag Attributes | Blank         |
| Block Size     | `33%`         |

### Horizontal Menu (Particle)

#### Particle Settings

![Demo Copyright](demo_copyright_7.jpeg)

| Field            | Setting                                              |
| :-----           | :-----                                               |
| Particle Name    | `Horizontal Menu`                                    |
| CSS Classes      | Blank                                                |
| Target           | Self                                                 |
| Menu Item 1 Name | `Features`                                           |
| Menu Item 1 Text | `Features`                                           |
| Menu Item 1 Link | `http://docs.gantry.org/gantry5/basics/key-features` |

#### Block Settings

![Demo Copyright](demo_copyright_8.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `57%`   |

### To Top (Particle)

#### Particle Settings

![Demo Copyright](demo_copyright_9.jpeg)

| Field         | Setting                                               |
| :-----        | :-----                                                |
| Particle Name | `To Top`                                              |
| CSS Classes   | `particle_gantry_totop`                               |
| Text          | `<i class="fa fa-fw fa-2x fa-arrow-circle-o-up"></i>` |

#### Block Settings

![Demo Copyright](demo_copyright_10.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `10%`   |
