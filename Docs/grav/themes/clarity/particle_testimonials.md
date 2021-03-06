---
title: Clarity: Testimonials Particle
description: Your Guide to Recreating Elements of the Clarity Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/clarity:Clarity

---

## Introduction

![](assets/particle_testimonials1.png)

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
| Content Source | Choose between **Particle** and **Grav** as the content source.                                |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title          | Enter a title for the particle. This will appear on the front end.                                  |
| Grid Column    | Select the number of columns you want testimonials to appear in.                                    |

### Particle Items

These items make up the individual featured items in the particle. They sit apart from the particle's title and introduction. Each item can have its own properties, including icons and written content.

![](assets/particle_testimonials3.png)

![](assets/particle_testimonials4.png)


| Option              | Description                                                               |
| :-----              | :-----                                                                    |
| Item Name           | This is the name of the item. This is just used for backend organization. |
| Testimonial Content | Descriptive text goes here. This is the bulk of the item's content.       |
| Testimonial Author  | Enter the name of the person giving the testimonial.                      |
| Person Position     | Enter a title or position for the author of the testimonial.              |
| Person Photo        | The image file can be linked here.                                        |
| Alt Tag             | Enter an alternative text for the photo.                                  |

### Pages

![](assets/particle_testimonials5.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how pages are displayed.

![](assets/particle_testimonials6.png)

| Option          | Description                                                                                       |
| :-----          | :-----                                                                                            |
| Image           | Select which image in an page should be displayed.                                                |
| Article Text    | Choose between showing just the **Introduction**, the **Full Article**, or to **Hide** page text. |
| Text Limit      | Set a limit (in characters) of the page's text to appear.                                         |
| Text Formatting | Select between **Plain Text** and **HTML** text formatting.                                       |
| Author          | **Show** or **Hide** the author.                                                                  |
