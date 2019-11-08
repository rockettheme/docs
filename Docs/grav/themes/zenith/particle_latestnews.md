---
title: Zenith: Latest News Particle
description: Your Guide to Recreating Elements of the Zenith Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/zenith:Zenith

---

## Introduction

![](assets/particle_latestnews1.png)

The **Latest News** particle displays your latest pages or featured content, along with images and text.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Pages](#pages)
    - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_latestnews2.png)

| Option            | Description                                                                                         |
| :-----            | :-----                                                                                              |
| Particle Name     | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source    | Choose between **Particle** and **Grav** as the Content Source.                                   |
| Title             | Set a title for the particle.                                                                       |
| CSS Classes       | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Grid Column       | Set the number of columns items appear in.                                                          |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_latestnews3.png)

![](assets/particle_latestnews4.png)

| Option      | Description                                                                              |
| :-----      | :-----                                                                                   |
| Item Name   | This is the name of the item. This appears as the item's title on the front end.         |
| Layout      | Choose between **Photo**, **Photo Large**, and **Text** as the layout type for the item. |
| Image       | Set an image to appear in the item.                                                      |
| Description | Enter a text description for the item.                                                   |
| News Date   | Add a date to be applied to the item on the front end.                                   |
| URL         | Enter a URL you would like the item to link to.                                          |

### Pages

![](assets/particle_latestnews5.png)

| Option             | Description                                                                               |
| :-----             | :-----                                                                                    |
| Categories         | Select the categories of pages this particle will display.                                |
| Number of Pages    | Select the number of pages you would like the particle to fetch.                          |
| Start From         | Enter offset specifying the first post to return. The default is '0' (the first article). |
| Order By           | Choose the type of factor to order by.                                                    |
| Ordering Direction | Choose between **Ascending** and **Descending** as the post ordering method.              |

### Display

This section configures how pages are displayed.

![](assets/particle_latestnews6.png)

| Option             | Description                                                                                        |
| :-----             | :-----                                                                                             |
| Image              | Display the image assigned to the article's **Intro**, **Full** or **None**.                       |
| Article Text       | Choose between **Introduction**, **Full Article**, and **Hide** for the post text to be displayed. |
| Text Limit         | Set a limit (in characters) for the post text displayed.                                           |
| Text Formatting    | Choose between **HTML** and **Plain Text** formatting for the article's text.                      |
| Date               | **Show** or **Hide** post dates.                                                                   |
| Date Format        | Set the format that dates will be displayed in.                                                    |
| Category           | Choose to **Show** or **Hide** Category.                                                           |
| Title              | **Show** or **Hide** the article's title.                                                          |
| Title Limit        | Enter the maximum number of characters in the title to display.                                    |
| Read More          | **Show** or **Hide** the Read More link.                                                           |
| Read More Label    | Enter a text label to appear as the read more link                                                 |
| Target             | Set a target window for the read more link.                                                        |
| Button CSS Classes | Enter any CSS Class(es) to apply to the items.                                                     |

>> Note: When using Grav Content source, images can utilize **Photo** and **Photo Large** layouts by adding **photo** or **photo-large** to the **Alt Text** field for either the Intro or Full image of the Article(s) you are displaying.
