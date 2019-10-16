---
title: Akuatik: Top Rated Particle
description: Your Guide to Recreating Elements of the Akuatik Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/akuatik:Akuatik

---

## Introduction

![](assets/particle_top1.png)

The **Top Rated** particle displays your latest articles or featured content, along with images and text.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Articles](#articles)
    - [Display](#display)

## Configuration

### Settings

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_top2.png)

| Option              | Description                                                                                         |
|:------------------- |:--------------------------------------------------------------------------------------------------- |
| Particle Name       | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source      | Choose between **Particle** and **Grav** as the Content Source.                                   |
| CSS Classes         | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title               | Set a title for the particle.                                                                       |
| Display Slides      | Enter the number of slides to display at once.                                                      |
| Slides to Scroll    | Enter the number of slides to scroll at once.                                                       |
| All Platforms Label | Enter a text label to bring up all items regardless of category.                                    |
| Filtering           | **Enable** or **Disable** filtering by category.                                                    |
| Prev / Next         | **Enable** or **Disable** Previous / Next Navigation.                                               |
| Autoplay            | **Enable** or **Disable** autoplay.                                                                 |
| Autoplay Timeout    | Set the time between autoplay between items (in milliseconds).                                      |
| Loop                | **Enable** or **Disable** looping of slides.                                                        |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_top3.png)

![](assets/particle_top4.png)

![](assets/particle_top5.png)

| Option      | Description                                                                      |
|:----------- |:-------------------------------------------------------------------------------- |
| Item Name   | This is the name of the item. This appears as the item's title on the front end. |
| CSS Classes | Enter any CSS class(es) you want to have apply to the item.                      |
| Image       | Set an image to appear in the item.                                              |
| Score       | Give your subject a numerical score.                                             |
| Ribbon Text | Input the ribbon text to appear in the corner ribbon.                            |
| Subtitle    | Enter a subtitle.                                                                |
| Description | Enter a text description for the item.                                           |
| Link        | Enter a URL you would like the item to link to.                                  |
| Link Target | Select a target window for the URL to open through.                              |

### Articles

![](assets/particle_top6.png)

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

![](assets/particle_top7.png)

| Option          | Description                                                                                           |
|:--------------- |:----------------------------------------------------------------------------------------------------- |
| Image           | Display the image assigned to the article's **Intro**, **Full** or **None**.                          |
| Title           | **Show** or **Hide** the article's title.                                                             |
| Title Limit     | Enter the maximum number of characters in the title to display.                                       |
| Article Text    | Choose between **Introduction**, **Hide**, and **Full Article** for the article text to be displayed. |
| Text Limit      | Set a limit (in characters) for the article text displayed.                                           |
| Text Formatting | Choose between **HTML** and **Plain Text** formatting for the article's text.                         |
| Link Items      | Select if the items should have links.                                                                |
| Link Target     | Set a target window for the read more link.                                                           |
