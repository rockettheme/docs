---
title: Elixir: Flipster Cover Flow Particle
description: Your Guide to Recreating Elements of the Elixir Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/elixir:Elixir

---

## Introduction

![](assets/particle_flipster1.png)

The **Flipster Cover Flow** particle is an excellent choice for displaying testimonial content, as well as important information for your visitors.

Here are the topics covered in this guide:

- [Introduction](#introduction)
- [Configuration](#configuration)
  - [Settings](#settings)
  - [Particle Item Options](#particle-item-options)
  - [Articles](#articles)
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


### Articles

![](assets/particle_flipster5.png)

| Option             | Description                                                                                                     |
| :----------------- | :-------------------------------------------------------------------------------------------------------------- |
| Categories         | Select the categories of articles this particle will display.                                                   |
| Articles           | Select the number of articles you would like the particle to fetch.                                             |
| Featured Articles  | Choose how Featured Articles should be filtered. Choose between **Include**, **Exclude**, or **Only Featured**. |
| Number of Articles | Enter the maximum number of articles to display.                                                                |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article).                    |
| Order By           | Choose the type of factor to order by.                                                                          |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.                                 |

### Display

This section configures how articles are displayed.

![](assets/particle_flipster6.png)

| Option       | Description                                                                                                                                              |
| :----------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image        | Select which image in an article should be displayed.                                                                                                    |
| Article Text | Choose between showing the **Introduction** or **Full Article** text to display. You can also **Hide** text.                                             |
| Text Limit   | Set a limit (in characters) of the article's text to appear.                                                                                             |
| Title        | Choose whether or not the title of an article should be shown.                                                                                           |
| Title Limit  | Set a character limit for titles.                                                                                                                        |
| Link         | Choose to Show or Hide the link to the article.                                                                                                          |
| Target       | Set the target for the button. You can choose between **Self** which opens the link in the current tab or **New Window** which opens links in a new tab. |
