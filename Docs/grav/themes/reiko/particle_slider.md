---
title: Reiko: Slider Particle
description: Your Guide to Recreating Elements of the Reiko Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/reiko:Reiko

---

## Introduction

![](assets/particle_slider1.jpeg)

The **Slider** particle is a great way to display images in your website.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Pages](#articles)
    - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_slider2.jpeg)

| Option               | Description                                                                                         |
| :-----               | :-----                                                                                              |
| Particle Name        | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source       | Choose between **Particle** and **Grav** as the Content Source.                                   |
| Prev / Next          | **Enable** or **Disable** the prev / next navigation.                                               |
| Autoplay             | **Enable** or **Disable** autoplay.                                                                 |
| Items - Desktop      | Select the number of items to display on a Desktop browser.                                         |
| Items - Tablet       | Select the number of items to display on a Tablet browser.                                          |
| Items - Mobile       | Select the number of items to display on a Mobile browser.                                          |
| Items - Small Mobile | Select the number of items to display on a Small Mobile browser.                                    |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_slider3.jpeg)

![](assets/particle_slider4.jpeg)

| Option    | Description                                                      |
| :-----    | :-----                                                           |
| Item Name | This is the name of the item. This only appears in the back end. |
| Icon      | Select a Font Awesome icon for the item.                         |
| Caption   | Enter a text caption for the item.                               |
| Link      | Enter a URL you would like the item to link to.                  |
| Target    | Choose the target tab you would like the URL to open to.         |

### Pages

![](assets/particle_slider5.jpeg)

| Option             | Description                                                                                                     |
| :-----             | :-----                                                                                                          |
| Categories         | Select the categories of articles this particle will display.                                                   |
| Pages           | Select the number of articles you would like the particle to fetch.                                             |
| Featured Pages  | Choose how Featured Pages should be filtered. Choose between **Include**, **Exclude**, or **Only Featured**. |
| Number of Pages | Enter the maximum number of articles to display.                                                                |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article).                    |
| Order By           | Choose the type of factor to order by.                                                                          |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.                                 |

### Display

This section configures how articles are displayed.

![](assets/particle_slider6.jpeg)

| Option          | Description                                                                  |
| :-----          | :-----                                                                       |
| Image           | Display the image assigned to the article's **Intro**, **Full** or **None**.        |
| Article Text    | Choose whether to display the **Introduction**, **Full Title**, or **Hide** (none). |
| Text Limit      | Enter the number of characters you wish to limit the text displayed to.             |
| Text Formatting | Choose between plain text and HTML.                                                 |
| Title           | **Show** or **Hide** the article's title.                                           |
| Title Limit     | Enter the maximum number of characters in the title to display.                     |
| Date            | Enter a date for the item.                                                          |
| Date Format     | Select the format you want the date to be displayed in.                             |
| Read More       | **Show** or **Hide** the Read More link.                                            |
| Read More Label | Enter any text you wish to have appear as the read more link.                       |
| Target          | Choose whether to have the link open in a new tab or the same tab.                  |
| Button Classes  | Enter any CSS class(es) you wish to have apply to the button.                       |