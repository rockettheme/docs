---
title: Horizon: Slider Particle
description: Your Guide to Recreating Elements of the Horizon Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/horizon:Horizon

---

## Introduction

![](assets/particle_slider1.png)

The **Slider** particle is a great way to display images in your website.

Here are the topics covered in this guide:

- [Configuration](#configuration)
  - [Settings](#settings)
  - [Particle Item Options](#particle-item-options)
  - [Pages](#pages)
  - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_slider2.png)

| Option           | Description                                                                                         |
| :-----           | :-----                                                                                              |
| Particle Name         | This is the name of the particle used for back end management. It does not appear on the front end.             |
| Content Source        | Choose between **Particle** and **Grav** as the content source for the particle.                              |
| Autoplay              | **Enable** or **Disable** autoplay for the particle.                                                            |
| Autoplay Timeout      | Set the time (in milliseconds) between slides in autoplay mode.                                                 |
| Hexagon Patterns               | **Enable** or **Disable** the pattern feature of the particle.                                         |
| Pagination                  | **Enable** or **Disable** dot navigation.                                                                 |
| Loop                  | **Enable** or **Disable** looping slides.                                                                       |
| Speed                 | Set the transition speed (in milliseconds).                                                                     |
| Touch Move            | **Enable** or **Disable** touch movements.                                                                      |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_slider3.png)

![](assets/particle_slider4.png)

| Option                 | Description                                                      |
| :-----                 | :-----                                                           |
| Title             	 | This is the name of the item. This will appear on the frontend |
| Image                  | Select an image to appear in the slide.                          |
| Link                   | Enter a URL you would like the item to link to.                  |
| Link Text              | Set a link text.                  |
| Link Target            | Choose the target tab you would like the URL to open to.         |

### Pages

![](assets/particle_slider6.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how posts are displayed.

![](assets/particle_slider6.png)

| Option        | Description                                                                                                                                              |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image         | Choose between the **Intro**, **Full**, or no image to display with each item.                                                                           |
| Title         | Choose whether or not the title of a page should be shown.                                                                                              |
| Title Limit   | Set a character limit for titles.                                                                                                                        |
| Article Text    | Select the article text to appear in each item.                                                    |
| Text Limit      | Set a limit (in characters) of article text to appear in the item.                                 |
| Text Formatting | Choose to display **Plain Text** or **HTML** in the article text.                                  |
| Button Link          | **Enable** or **Disable** the link to the page.																									|
| Button Label  | Enter the text you would like to have appear as the button link.                                                                                         |
| Button Target   | Set the target for the button. You can choose between **Self** which opens the link in the current tab or **New Window** which opens links in a new tab. |