---
title: Ambrosia: Recreating the Demo - Header Section
description: Your Guide to Recreating Elements of the Ambrosia Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/ambrosia:Ambrosia

---

## Introduction

![](assets/demo_header.jpeg)

:   1. **Logo (Particle)** [40%, 5%, se]
    2. **Menu (Particle)** [40%, 65%, se]

The **Header** section is made up of the System Messages position, as well as two particles set in two rows.

![](assets/home_header.jpeg)

The **System Messages** Position displays system messages in your layout. Always include this particle to all of your layouts. Otherwise users will not see important system messages like login failures.

In the second row, we have a **Logo** particle and a **Horizontal Menu** particle which make up the visual body of this area of the site. Settings used in our demo for each of these particles can be found below.

## Section Settings

![](assets/demo_header_settings.jpeg)

| Field          | Setting   |
| :-----         | :-----    |
| Layout         | Fullwidth |
| CSS Classes    | `g-home`  |
| Tag Attributes | Blank     |

## System Messages (Position)

### Particle Settings

![Demo Top](demo_header_5.jpeg)

### Block Settings

![Demo Top](demo_header_6.jpeg)

| Field          | Setting               |
| :-----         | :-----                |
| CSS ID         | Blank                 |
| CSS Classes    | Blank                 |
| Variations     | No Margin, No Padding |
| Tag Attributes | Blank                 |
| Block Size     | `100%`                |

## Logo (Particle)

### Particle Settings

![Demo Header](demo_header_1.jpeg)

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Logo`     |
| URL           | Blank      |
| Image         | Custom     |
| Text          | `Ambrosia` |
| CSS Classes   | `g-logo`   |

### Block Settings

![Demo Header](demo_header_2.png)

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `g-logo-block` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `25%`          |

## Horizontal Menu (Particle)

### Particle Settings

![Demo Header](demo_header_3.jpeg)

| Field            | Setting                                              |
| :-----           | :-----                                               |
| Particle Name    | `Top Menu`                                           |
| CSS Classes      | Blank                                                |
| Target           | New Window                                           |
| Menu Item 1 Name | `Features`                                           |
| Menu Item 1 Text | `Features`                                           |
| Menu Item 1 Link | `http://docs.gantry.org/gantry5/basics/key-features` |

### Block Settings

![Demo Header](demo_header_4.jpeg)

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `75%`   |
