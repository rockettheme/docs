---
title: Reiko: Photo Collage Particle
description: Your Guide to Recreating Elements of the Reiko Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reiko:Reiko

---

## Introduction

![](assets/particle_photocollage1.png)

The **Photo Collage** particle displays images in a fun, modern collage.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Articles](#articles)
    - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_photocollage2.png)

| Option         | Description                                                                                         |
| :-----         | :-----                                                                                              |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end. |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Content Source | Choose between **Particle** and **Joomla** as the Content Source.                                   |
| Title          | Enter a title for the particle that appears on the front end.                                       |
| Item Spacing   | Set a custom amount of spacing between items.                                                       |

### Particle Item Options

These items make up the individual featured items in the particle. 

![](assets/particle_photocollage3.png)

![](assets/particle_photocollage4.png)

| Option       | Description                                                   |
| :-----       | :-----                                                        |
| Width Ratio  | Set the width ratio. (Appears only on large desktops.)        |
| Height Ratio | Set the height ratio. (Appears on all devices except mobile.) |
| Photo        | Select a photo to display as the item.                        |
| Icon         | Set an icon to appear when you hover over the image.          |

### Articles

![](assets/particle_photocollage6.png)

| Option             | Description                                                                                                     |
| :-----             | :-----                                                                                                          |
| Categories         | Select the categories of articles this particle will display.                                                   |
| Articles           | Select the number of articles you would like the particle to fetch.                                             |
| Featured Articles  | Choose how Featured Articles should be filtered. Choose between **Include**, **Exclude**, or **Only Featured**. |
| Number of Articles | Enter the maximum number of articles to display.                                                                |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article).                    |
| Order By           | Choose the type of factor to order by.                                                                          |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.                                 |

### Display

This section configures how articles are displayed.

![](assets/particle_photocollage7.png)

| Option      | Description                                                    |
| :-----      | :-----                                                         |
| Image       | Select which image in an article should be displayed.          |
| Title       | Choose whether or not the title of an article should be shown. |
| Title Limit | Set a character limit for titles.                              |

>> Note: When using Joomla Content source, images can utilize **Width** and **Height** options by adding, for example, **width-2** and/or **height-2** to the ALT field in either the Intro or Full image of the Article(s) you are displaying.
