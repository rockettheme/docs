---
title: Kraken: Recreating the Demo - Mainbar and Aside Sections
description: Your Guide to Recreating Elements of the Kraken Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kraken:Kraken

---

## Introduction

![](assets/demo_7.jpeg)

The **Mainbar** section includes three module positions, `mainbar-a`, `mainbar-b`, and `mainbar-c`. In a second row, the **Pagecontent** position has been added, inserting any article content that is assigned to the page. We are only using `mainbar-a` from this section actively, so only it is rendering to the front end.

![](assets/demo_8.jpeg)

: 1. **Icon Menu (Particle)** [3%, 8%, se]
  2. **Grid Content (Particle)** [15%, 8%, se]
  3. **Block Content (Particle)** [44%, 8%, se]
  4. **Swiper (Particle)** [70%, 8%, se]

The **Aside** section makes up the sidebar to the right of the **Mainbar**. This section contains a single module position, `aside`.

![](assets/home_mainbar.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in front end from the **Mainbar** section:

* [Mainbar A (module position)](#mainbar-a-(module-position))
    - [Grid Content (particle)](#gantry-5-particle-(grid-content))

Here is a breakdown of the module(s) and particle(s) that appear in front end from the **Aside** section:

* [Aside (module position)](#aside-(module-position))
    - [Icon Menu (particle)](#gantry-5-particle-(icon-menu))
    - [Grid Content (particle)](#gantry-5-particle-(grid-content)-2)
    - [Block Content (particle)](#gantry-5-particle-(block-content))
    - [Swiper (particle)](#gantry-5-particle-(swiper))

## Section Settings

### Container

![](assets/demo_container_settings.jpeg)

| Option         | Setting   |
|:---------------|:----------|
| Layout         | Fullwidth |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |

### Mainbar

![](assets/demo_mainbar_settings.jpeg)

| Option         | Setting |
|:---------------|:--------|
| CSS Classes    | Blank   |
| Tag Attributes | Blank   |

| Option         | Setting |
|:---------------|:--------|
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `60%`   |

### Aside

![](assets/demo_aside_settings.jpeg)

| Option         | Setting |
|:---------------|:--------|
| CSS Classes    | Blank   |
| Tag Attributes | Blank   |

| Option         | Setting |
|:---------------|:--------|
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `40%`   |

## Mainbar A (module position)

#### Particle Settings

![Demo Mainbar](assets/demo_mainbar_1.jpeg)

| Option | Setting     |
|:-------|:------------|
| Key    | `mainbar-a` |
| Chrome | gantry      |

#### Block Settings

![Demo Mainbar](assets/demo_mainbar_2.jpeg)

| Option         | Setting    |
|:---------------|:-----------|
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | Blank      |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Assigned Module(s)

#### Gantry 5 Particle (Grid Content)

We added a **Grid Content** particle to the `mainbar-a` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Grid Content** particle in the module's settings.

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Mainbar](assets/demo_mainbar_9.jpeg)

| Option                                | Setting                                                                                                            |
|:--------------------------------------|:-------------------------------------------------------------------------------------------------------------------|
| Particle Name                         | `Grid Content`                                                                                                     |
| CSS Classes                           | Blank                                                                                                              |
| Title                                 | Blank                                                                                                              |
| Description                           | Blank                                                                                                              |
| Readmore Text                         | Blank                                                                                                              |
| Readmore Link                         | Blank                                                                                                              |
| Readmore Style                        | Button 3                                                                                                           |
| Grid Column                           | 1 Column                                                                                                           |
| Grid Columns Item 1 Name              | Blank                                                                                                              |
| Grid Columns Item 1 Icon              | Blank                                                                                                              |
| Grid Columns Item 1 Image             | Custom                                                                                                             |
| Grid Columns Item 1 Title Class       | Style 3                                                                                                            |
| Grid Columns Item 1 SubTitle          | `Photo`                                                                                                            |
| Grid Columns Item 1 Title             | `The new and powerful Gantry 5`                                                                                    |
| Grid Columns Item 1 Description       | `Gantry 5 is an advanced, versatile and multi-platform template framework, perfectly designed for the modern web.` |
| Grid Columns Item 1 Link Text         | Blank                                                                                                              |
| Grid Columns Item 1 Link              | `#`                                                                                                                |
| Grid Columns Item 1 Link Button Style | Arrow                                                                                                              |

## Aside (module position)

#### Particle Settings

![Demo Mainbar](assets/demo_mainbar_10.jpeg)

| Option | Setting |
|:-------|:--------|
| Key    | `aside` |
| Chrome | gantry  |

#### Block Settings

![Demo Mainbar](assets/demo_mainbar_11.jpeg)

| Option         | Setting |
|:---------------|:--------|
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `100%`  |

### Assigned Module(s)

#### Gantry 5 Particle (Icon Menu)

We added a **Icon Menu** particle to the `aside` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Icon Menu** particle in the module's settings.

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Mainbar](assets/demo_mainbar_12.jpeg)

| Option                   | Setting                     |
|:-------------------------|:----------------------------|
| Particle Name            | `Icon Menu`                 |
| CSS Classes              | `g-title-bordered` `center` |
| Title                    | `Compatibility`             |
| Icon Menu Item 1 Name    | `Firefox`                   |
| Icon Menu Item 1 Icon    | `fa fa-firefox fa-fw fa-2x` |
| Icon Menu Item 1 Text    | `Firefox`                   |
| Icon Menu Item 1 SubText | `v. 40+`                    |
| Icon Menu Item 1 Link    | `#`                         |
| Icon Menu Item 1 Target  | New Window                  |

#### Gantry 5 Particle (Grid Content) 2

We added a **Grid Content** particle to the `aside` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Grid Content** particle in the module's settings.

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Mainbar](assets/demo_mainbar_13.jpeg)

| Option                                | Setting                                                                                                                                                                                 |
|:--------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Particle Name                         | `Grid Content`                                                                                                                                                                          |
| CSS Classes                           | `g-titled-border` `center`                                                                                                                                                              |
| Title                                 | `Must Read`                                                                                                                                                                             |
| Description                           | Blank                                                                                                                                                                                   |
| Readmore Text                         | Blank                                                                                                                                                                                   |
| Readmore Link                         | Blank                                                                                                                                                                                   |
| Readmore Style                        | Button 3                                                                                                                                                                                |
| Grid Column                           | 1 Column                                                                                                                                                                                |
| Grid Columns Item 1 Name              | `Contemporary Interface provides Multiple Options for Users `                                                                                                                           |
| Grid Columns Item 1 Icon              | Blank                                                                                                                                                                                   |
| Grid Columns Item 1 Image             | Blank                                                                                                                                                                                   |
| Grid Columns Item 1 Title Class       | Style 4                                                                                                                                                                                 |
| Grid Columns Item 1 SubTitle          | Blank                                                                                                                                                                                   |
| Grid Columns Item 1 Title             | `<span>Contemporary Interface<span class="hidden-tablet"> provides Multiple Options for Users</span></span>`                                                                            |
| Grid Columns Item 1 Description       | `<span>Gantry 5's administrative interface<span class="hidden-tablet"> has been completely rebuilt from the ground up to meet the needs of tomorrow's developer, todays.</span></span>` |
| Grid Columns Item 1 Link Text         | Blank                                                                                                                                                                                   |
| Grid Columns Item 1 Link              | Blank                                                                                                                                                                                   |
| Grid Columns Item 1 Link Button Style | Button 3                                                                                                                                                                                |

#### Gantry 5 Particle (Block Content)

We added a **Block Content** particle to the `aside` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Block Content** particle in the module's settings.

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Mainbar](assets/demo_mainbar_14.jpeg)

| Option                          | Setting                                                                                                                         |
|:--------------------------------|:--------------------------------------------------------------------------------------------------------------------------------|
| Particle Name                   | `Block Content`                                                                                                                 |
| CSS Classes                     | `g-title-bordered` `center`                                                                                                     |
| Title                           | `Past Week`                                                                                                                     |
| Icon Menu Item 1 Name           | `Customize from the Styles Panel`                                                                                               |
| Icon Menu Item 1 Title          | `<span class="hidden-tablet">Customize from the </span>Styles Panel`                                                            |
| Icon Menu Item 1 Icon           | Blank                                                                                                                           |
| Icon Menu Item 1 Image          | Custom                                                                                                                          |
| Icon Menu Item 1 RokBox Image   | Custom                                                                                                                          |
| Icon Menu Item 1 Caption        | `Style Panel`                                                                                                                   |
| Icon Menu Item 1 SubTitle       | Blank                                                                                                                           |
| Icon Menu Item 1 Description    | `<span>Style elements of the Kraken theme<span class="hidden-tablet">, such as links, font or background colors.</span></span>` |
| Icon Menu Item 1 CSS Classes    | Blank                                                                                                                           |
| Icon Menu Item 1 Button Label   | Blank                                                                                                                           |
| Icon Menu Item 1 Button Link    | Blank                                                                                                                           |
| Icon Menu Item 1 Button Classes | Blank                                                                                                                           |

#### Gantry 5 Particle (Swiper)

We added a **Swiper** particle to the `aside` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Swiper** particle in the module's settings.

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Mainbar](assets/demo_mainbar_15.jpeg)

| Option                    | Setting                                                                  |
|:--------------------------|:-------------------------------------------------------------------------|
| Particle Name             | `Swiper`                                                                 |
| CSS Classes               | `g-title-bordered` `title-center` `g-swiper-stories`                     |
| Title                     | `Trending`                                                               |
| Element ID                | `swiper-3`                                                               |
| Layout                    | Horizontal Slides                                                        |
| Element Height            | Auto                                                                     |
| Slide per View            | `2`                                                                      |
| Swiper Item 1 Name        | `Item 1`                                                                 |
| Swiper Item 1 Image       | Custom                                                                   |
| Swiper Item 1 SubTitle    | Blank                                                                    |
| Swiper Item 1 Title       | `Particles System`                                                       |
| Swiper Item 1 Link        | Blank                                                                    |
| Swiper Item 1 Link Text   | Blank                                                                    |
| Swiper Item 1 Description | `Gantry 5's Particles system makes it easy to configure content blocks.` |
