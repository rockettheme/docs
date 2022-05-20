---
title: Studius: Feature Slider Particle
description: Your Guide to Recreating Elements of the Studius Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/studius:Studius

---

## Introduction

![](assets/particle_featureslider1.png)

The **Feature Slider** particle displays text and images to feature various services. 

Here are the topics covered in this guide:

- [Configuration](#configuration)
  - [Settings](#settings)
  - [Particle Item Options](#particle-item-options)
  - [Pages](#pages)
  - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_featureslider2.png)

| Option           | Description                                                                                         |
| :-----           | :-----                                                                                              |
| Particle Name         | This is the name of the particle used for back end management. It does not appear on the front end.             |
| Content Source        | Choose between **Particle** and **Grav** as the content source for the particle.                              |
| Autoplay              | **Enable** or **Disable** autoplay for the particle.                                                            |
| Autoplay Timeout      | Set the time (in milliseconds) between slides in autoplay mode.                                                 |
| Loop                  | **Enable** or **Disable** looping slides.                                                                       |
| Speed                 | Set the transition speed (in milliseconds).                                                                     |
| Height                | Particle minimum height..                                                                 |
| Touch Move            | **Enable** or **Disable** touch movements.                                                                      |
| Touch Move Tabs           | Decide if you want to be able to move tabs using touch.                                                                     |
| Hexagon Patterns               | **Enable** or **Disable** the pattern feature of the particle.                                         |


### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_featureslider3.png)

![](assets/particle_featureslider4.png)

| Option                 | Description                                                      |
| :-----                 | :-----                                                           |
| Title             	 | This is the name of the item. This will appear on the frontend |
| Description            	 | Enter slide description. |
| Image                  | Select an image to appear in the slide.                          |

### Pages

![](assets/particle_featureslider6.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how posts are displayed.

![](assets/particle_featureslider6.png)

| Option             | Description                                                                                       |
| :-----             | :-----                                                                                            |
| Image              | Choose between the **Intro**, **Full**, or no image to display with each item.                    |
| Title              | Choose whether or not the title of an post should be shown.                                       |
| Title Limit        | Set a character limit for titles.                                                                 |
| Article Text    	 | Choose between showing the **Introduction** or **Full Article** text to display. You can also **Hide** text. |
| Text Limit         | Set a limit (in characters) of the post's text to appear.                                                    |
| Text Formatting    | Select between **Plain Text** and **HTML** text formatting.                                                  |