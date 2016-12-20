---
title: Versla: Owl Carousel Particle
description: Your Guide to Recreating Elements of the Versla Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/versla:Versla

---

## Introduction

![](assets/particle_owl1.jpeg)

The **Owl Carousel** particle is a diverse particle with multiple layouts, a wide range of features and customization options, and the ability to source content from both the CMS and custom items set up in the particle itself.

The **Owl Carousel** particle is based on the open source project of the same name by [Bartosz Wojciechowski](http://www.owlcarousel.owlgraphic.com/index.html).

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#item-options)

### Main Options 

![](assets/particle_owl4.jpeg)

| Option          | Description                                                                                                                                  |
| :-----          | :-----                                                                                                                                       |
| CSS Classes     | Sets the CSS class for the content of the particle.                                                                                          |
| Content Source  | Select **Particle** or **Grav** to determine where particle content is pulled from.                                                        |
| Demo Sync       | Syncs the images with the currently-selected preset.                                                                                         |
| Lazy Loading    | Enables or disables a technique for loading images as they are needed rather than on initial page load.                                      |
| Display at Once | Determines how many items are displayed at a given time in the particle.                                                                     |
| Title           | Sets the title of the particle, as it will appear on the front end.                                                                          |
| Description     | s you to enter a description for the particle. This is independent of individual item descriptions.                                          |
| Layout          | Choose between the [supported layouts](#layouts) for the particle. This determines how the particle will look, and how content is displayed. |
| Width           | Choose between **Full Width** and **Compact** to determine how content is displayed.                                                         |
| In Animation    | Sets the animation type as content is brought in. `fadeIn` is a popular option.                                                              |
| Out Animation   | Sets the animation type as content is removed on the front end. `fadeOut` is a popular option.                                               |
| Prev Next       | Enables a previous / next switcher on the front end.                                                                                         |
| Prev Text       | Allows you to set text that appears in the Previous switch on the front end.                                                                 |
| Next Text       | Allows you to set text that appears in the Next switch on the front end.                                                                     |
| Dots            | Enables or disables pagination dots.                                                                                                         |
| Loop            | Enables or disables looping of content, going from finish to start continuously.                                                             |
| Autoplay        | Enables or disables autoplay, allowing the particle to automatically move through items.                                                     |
| Autoplay Speed  | Sets the speed at which items are automatically progressed in autoplay.                                                                      |
| Pause on Hover  | Pauses the automatic switching between items in autoplay.                                                                                    |

### Item Options

These items only appear on the front end if you select **Particle** as the **Content Source**.

![](assets/particle_owl5.jpeg)

| Option                           | Description                                                                                                                    |
| :-----                           | :-----                                                                                                                         |
| Owl Carousel Item Name           | Sets the name for the item in the carousel. This is only seen on the back end.                                                 |
| Owl Carousel Item Image          | Enables you to define an image for the item. This is the primary image that appears most prominently as the item is displayed. |
| Owl Carousel Item Icon           | You can use this field to assign an icon to the item that appears with its **Title**. For example: `fa fa-cogwheel fa-fw`.     |
| Owl Carousel Item Title          | Enter a title for the item here.                                                                                               |
| Owl Carousel Item Description    | This is the main content body of the item. Enter any information you want to have displayed in paragraph form here.            |
| Owl Carousel Item Link           | This is where you would enter a link you want the item to send visitors to when clicked.                                       |
