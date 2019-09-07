---
title: Koleti: Slider Particle
description: Your Guide to Recreating Elements of the Koleti Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/koleti:Koleti

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
| Particle Title       | Enter a text title you wish to have display on the front end.                                       |
| Particle Description | Enter a text description for the particle.                                                          |
| Slide Height         | Enter the height (in pixels) for the slider. Example: `500`                                         |
| Autoplay             | **Enable** or **Disable** autoplay.                                                                 |
| Autoplay Timeout     | Set the timeout (in milliseconds) for the autoplay. Example: `5000`.                                |
| Speed                | Set the speed of the transitions. This is also in milliseconds. Example: `250`                      |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_slider3.jpeg)

![](assets/particle_slider4.jpeg)

| Option                 | Description                                                  |
| :-----                 | :-----                                                       |
| Item Name              | This is the name of the item. This appears on the front end. |
| Additional Description | Add an additional description for the item.                  |
| Icon                   | Select a Font Awesome icon for the item.                     |
| Image                  | Set the background image for the slide.                      |
| Link                   | Enter a URL you would like the item to link to.              |
| Target                 | Choose the target tab you would like the URL to open to.     |

### Pages

![](assets/particle_slider5.jpeg)

| Option             | Description                                                                                  |
| :-----             | :-----                                                                                       |
| Categories         | Select the categories of pages this particle will display.                                   |
| Number of Pages    | Enter the maximum number of pages to display.                                                |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article). |
| Order By           | Choose the type of factor to order by.                                                       |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.              |

### Display

This section configures how pages are displayed.

![](assets/particle_slider6.jpeg)

| Option          | Description                                                                         |
| :-----          | :-----                                                                              |
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