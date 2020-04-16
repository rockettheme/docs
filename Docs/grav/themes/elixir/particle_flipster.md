---
title: Elixir: Flipster Cover Flow Particle
description: Your Guide to Recreating Elements of the Elixir Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/elixir:Elixir

---

## Introduction

![](assets/particle_flipster1.png)

The **Flipster Cover Flow** particle is an excellent choice for displaying testimonial content, as well as important information for your visitors.

Here are the topics covered in this guide:

- [Introduction](#introduction)
- [Configuration](#configuration)
  - [Settings](#settings)
  - [Particle Item Options](#particle-item-options)
  - [Pages](#pages)
  - [Display](#display)

## Configuration

### Settings

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_flipster2.png)

| Option         | Description                                                                                         |
| :------------- | :-------------------------------------------------------------------------------------------------- |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source | Choose whether to have content load from particle items or the CMS.                                 |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title          | Set a title for the particle.                                                                       |
| Start          | Choose where to start the praticle off when the page loads.                                         |
| FadeIn         | Speed of the animation (in milliseconds) for items to fade in on page load.                         |
| Loop           | **Enable** or **Disable** the loop around when the items reach the end of the list.                 |
| Autoplay       | Enter the number of milliseconds between item switches on autoplay. `0` disables autoplay.          |
| Pause On Hover | **Enable** or **Disable** Pause on Hover.                                                           |
| Style          | Set the style. Options include: **Cover Flow**, **Carousel**, **Flat**, and **Wheel**.              |
| Spacing        | Space between items relative to the item's width.                                                   |
| Click          | Clicking an item switches to that item.                                                             |
| Keyboard       | **Enable** or **Disable** arrow right/left navigation.                                              |
| Scroll Wheel   | **Enable** or **Disable** Scroll Wheel navigation.                                                  |
| Touch          | **Enable** or **Disable** touch navigation.                                                         |

### Particle Item Options

These items make up the individual featured items in the particle.

![](assets/particle_flipster3.png)

![](assets/particle_flipster4.png)

| Option         | Description                                                           |
| :------------- | :-------------------------------------------------------------------- |
| Item Name      | This is the name of the item. This name only appears on the back end. |
| Accent         | Select the accent color to feature as the background of the item.     |
| Description    | Enter a text description for the item.                                |
| Title          | Enter a title for the item.                                           |
| Image          | Set an image to appear in the item.                                   |
| Button Label   | Enter a label to appear as the button for the item.                   |
| Button Link    | Enter a URL you would like the item to link to.                       |
| Target         | Select a target window for the URL to open through.                   |
| Button Classes | Enter any CSS class(es) to apply to the item.                         |


### Pages

![](assets/particle_flipster5.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how posts are displayed.

![](assets/particle_flipster6.png)

| Option          | Description                                                                                         |
| :------------   | :-------------------------------------------------------------------------------------------------- |
| Image           | Choose between the **Intro**, **Full**, or no image to display with each item.                      |
| Article Text    | Choose between **Introduction**, **Full Article**, or **Hide** content text to display.             |
| Text Limit      | Enter a limit (in characters) of page text to display with each item.                               |
| Text Formatting | Choose between **Plain Text** and **HTML** text formatting options.                                 |
| Title           | **Show** or **Hide** the page's title.                                                              |
| Title Limit     | Enter the maximum number of characters in the title to display.                                     |
| Link            | **Show** or **Hide** the link.                                                                      |
| Link Target     | Choose whether to have the link open in a new tab or the same tab.                                  |
