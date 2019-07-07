---
title: Manticore: Testimonials Particle
description: Your Guide to Recreating Elements of the Manticore Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/manticore:Manticore

---

## Introduction

The **Testimonials** particle displays testimonials in an elegant, east-to-read way. You can manually input testimonial content, or pull it from your CMS.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#particle-items)
    - [Pages](#pages)
    - [Articles Display](#display)

## Configuration

### Main Options

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_testimonials2.png)

| Option         | Description                                                                                         |
| :-----         | :-----                                                                                              |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source | Choose between **Particle** and **Grav** as the content source.                                   |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title          | Enter a title for the particle. This will appear on the front end.                                  |
| Subtitle       | enter a subtitle for the particle.                                                                  |
| Out Animation  | Set the type of animation that runs when a testimonial is going out.                                |
| In Animation   | Set the type of animation that runs when a testimonial is coming in.                                |
| Prev / Next    | **Enable** or **Disable** the prev / next navigation.                                               |
| Dots           | **Enable** or **Disable** dots navigation.                                                          |
| Loop           | **Enable** or **Disable** looping of items.                                                         |
| Autoplay       | **Enable** or **Disable** autoplay.                                                                 |
| Autoplay Speed | Enter (in milliseconds) the delay between automatic switching between items.                        |
| Pause on Hover | **Enable** or **Disable** pausing of autoplay on hover.                                             |

### Particle Items

These items make up the individual featured items in the particle. They sit apart from the particle's title and introduction. Each item can have its own properties, including icons and written content.

![](assets/particle_testimonials3.png)

![](assets/particle_testimonials4.png)


| Option              | Description                                                                        |
| :-----              | :-----                                                                             |
| Item Name           | This is the name of the item. This becomes the name that appears on the front end. |
| Testimonial Content | Descriptive text goes here. This is the bulk of the item's content.                |
| Testimony Author    | Enter the name of the person giving the testimonial.                               |
| Person Position     | Enter a title or position for the author of the testimonial.                       |
| Person Photo        | The image file can be linked here.                                                 |

### Pages

![](assets/particle_testimonials5.png)

| Option             | Description                                                                                                     |
|:------------------ |:--------------------------------------------------------------------------------------------------------------- |
| Categories         | Select the categories of pages this particle will display.                                                      |
| Number of Pages    | Enter the maximum number of pages to display.                                                                   |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page).                          |
| Order By           | Choose the type of factor to order by.                                                                          |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.                                    |

### Display

This section configures how pages are displayed.

![](assets/particle_testimonials6.png)

| Option          | Description                                                                                                                                              |
|:--------------- |:-------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image           | Select which image in an page should be displayed.                                                                                                       |
| Article Text    | Choose between showing the **Introduction** or **Full Article** text to display. You can also **Hide** text.                                             |
| Text Limit      | Set a limit (in characters) of the page's text to appear.                                                                                                |
| Text Formatting | Select between **Plain Text** and **HTML** text formatting.                                                                                              |
| Author          | Choose to **Show** or **Hide** the author.                                                                                                               |
| Button Label    | Enter the text you would like to have appear as the button link.                                                                                         |
| Button Link     | Enter the url you want that link to go to.                                                                                                               |
| Link Target     | Set the target for the button. You can choose between **Self** which opens the link in the current tab or **New Window** which opens links in a new tab. |
