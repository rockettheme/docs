---
title: Salient: Recreating the Demo - Feature Section
description: Your Guide to Recreating Elements of the Salient Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/salient:Salient

---

## Introduction

![](assets/demo_7.png)

The **Feature** section includes one module position, `feature-a`. It also includes a spacer, set at 50% width to the left of the module position. Both the spacer and the module position can be set up using the **Layout Manager**.

![](assets/home_feature.png)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Spacer (position)](#spacer-(positions-particle))
* [Feature A (module position)](#feature-a-(module-position))
    - [Promo Content (particle)](#gantry-5-particle-(promo-content))

## Section Settings

![](assets/demo_feature_settings.png)

| Option         | Setting   |
| :-----         | :-----    |
| Layout         | Fullwidth |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |

## Spacer (positions particle)

#### Particle Settings

![Demo Feature](demo_feature_1.png)

#### Block Settings

![Demo Feature](demo_feature_2.png)

| Option         | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `50%`   |


## Feature A (module position)

#### Particle Settings

![Demo Feature](demo_feature_3.png)

| Option | Setting     |
| :----- | :-----      |
| Key    | `feature-a` |
| Chrome | gantry      |

#### Block Settings

![Demo Feature](demo_feature_4.png)

| Option         | Setting                       |
| :-----         | :-----                        |
| CSS ID         | Blank                         |
| CSS Classes    | `nomarginall`, `nopaddingall` |
| Variations     | Blank                         |
| Tag Attributes | Blank                         |
| Block Size     | `50%`                         |

### Assigned Module(s)

#### Gantry 5 Particle (Promo Content)

We added a **Promo Content** particle to the `feature-a` position. This was done by creating a **Gantry 5 Particle** module and selecting the **Promo Content** particle in the module's settings. 

You will find the particle settings used in this particle below:

##### Particle Settings

![Demo Feature](demo_feature_5.png)

| Option           | Setting                                                                                                                                                                                                                                |
| :-----           | :-----                                                                                                                                                                                                                                 |
| CSS Classes      | `g-overlay`                                                                                                                                                                                                                            |
| Title            | Blank                                                                                                                                                                                                                                  |
| Promo Style      | Super Promo                                                                                                                                                                                                                            |
| Promo Text       | `Mobile <br /> Responsive`                                                                                                                                                                                                             |
| Description      | `<p>Salient is built with a responsive layout, which means it automatically adapts to the viewing device, so it will expand and contract accordingly to the size and resolution of the screen, whether mobile, tablet or desktop.</p>` |
| Readmore Text    | `&rarr;`                                                                                                                                                                                                                               |
| Readmore Classes | `button-arrow`, `nopaddingall`                                                                                                                                                                                                         |
| Link             | `#`                                                                                                                                                                                                                                    |
| Readmore Style   | Block                                                                                                                                                                                                                                  |
| Tag Item 1 Name  | `Flexible`                                                                                                                                                                                                                             |
| Tag Item 1 Icon  | Blank                                                                                                                                                                                                                                  |
| Tag Item 1 Text  | `Flexible`                                                                                                                                                                                                                             |
| Tag Item 1 Link  | `#`                                                                                                                                                                                                                                    |
