---
title: Kraken: Chartist Particle
description: Your Guide to Recreating Elements of the Kraken Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/kraken:Kraken

---

## Introduction

![](assets/particle_chartist1.jpeg)

The **Chartist** particle makes it easy to create beautiful pie, line, and bar charts for your website.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)

## Configuration

### Main Options 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_chartist2.jpeg)

| Option        | Description                                                                                    |
| :-----        | :-----                                                                                         |
| Particle Name | Enter the name you would like to assign to the particle. This only appears in the back end.    |
| CSS Classes   | Enter the CSS class(es) you want to use in the content of the particle.                        |
| Title         | Enter a title for your particle. This appears over the chart.                                  |
| Labels Data   | Here, you will enter the data that appears at the bottom of the chart.                         |
| Series Data   | Here, you can insert one or more series of numbers to create the vertical values of the chart. |

Separate each item with comma. For Labels Data, each item should be wrapped with single quote. For example: 'Mon', 'Tue', 'Wed'. For Series Data, all each item should be wrapped with square brackets. For example: `100, 150, 250`. For multiple series, separate each data series with comma. For example: `100, 150, 250`, `250, 180, 590`, `50, 350, 50`.

