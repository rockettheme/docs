---
title: Manticore: Latest News Particle
description: Your Guide to Recreating Elements of the Manticore Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/manticore:Manticore

---

## Introduction

![](assets/particle_latestnews1.png)

The **Latest News** particle displays your latest articles or featured content, along with images and text.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Articles](#articles)
    - [Display](#display)

## Configuration

### Settings

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_latestnews2.png)

| Option          | Description                                                                                         |
|:--------------- |:--------------------------------------------------------------------------------------------------- |
| Particle Name   | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source  | Choose between **Particle** and **Joomla** as the Content Source.                                   |
| CSS Classes     | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title           | Set a title for the particle.                                                                       |
| Upper Title     | Enter a title to appear above the main title.                                                       |
| All Items Label | Enter a text label to bring up all items regardless of category.                                    |
| Selected        | Choose the selected nav item by default.                                                            |
| Grid Column     | Set the number of columns items appear in.                                                          |
| Date Format     | Select the date format to be displayed.                                                             |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_latestnews3.png)

![](assets/particle_latestnews4.png)

![](assets/particle_latestnews5.png)

| Option      | Description                                                                              |
|:----------- |:---------------------------------------------------------------------------------------- |
| Item Name   | This is the name of the item. This appears as the item's title on the front end.         |
| Layout      | Choose between **Photo**, **Photo Large**, and **Text** as the layout type for the item. |
| Date        | Enter a date for the article.                                                            |
| Image       | Set an image to appear in the item.                                                      |
| Description | Enter a text description for the item.                                                   |
| URL         | Enter a URL you would like the item to link to.                                          |
| Target      | Select a target window for the URL to open through.                                      |

### Articles

![](assets/particle_latestnews6.png)

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

![](assets/particle_latestnews7.png)

| Option             | Description                                                                                           |
| :-----             | :-----                                                                                                |
| Image              | Display the image assigned to the article's **Intro**, **Full** or **None**.                          |
| Article Text       | Choose between **Introduction**, **Hide**, and **Full Article** for the article text to be displayed. |
| Text Limit         | Set a limit (in characters) for the article text displayed.                                           |
| Text Formatting    | Choose between **HTML** and **Plain Text** formatting for the article's text.                         |
| Title              | **Show** or **Hide** the article's title.                                                             |
| Title Limit        | Enter the maximum number of characters in the title to display.                                       |
| Date               | **Show** or **Hide** article dates.                                                                   |
| Date Format        | Set the format that dates will be displayed in.                                                       |
| Read More          | **Show** or **Hide** the Read More link.                                                              |
| Read More Label    | Enter a text label to appear as the read more link                                                    |
| Target             | Set a target window for the read more link.                                                           |
| Button CSS Classes | Enter any CSS Class(es) to apply to the items.                                                        |

>> Note: When using Joomla Content source, images can utilize the **Photo Large** layout by adding **photo-large** to the **Alt Text** field for either the Intro or Full image of the Article(s) you are displaying.
