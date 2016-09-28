---
title: Protean: Owl Carousel Particle
description: Your Guide to Recreating Elements of the Protean Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/protean:Protean

---

## Introduction

![](assets/particle_owl1.jpg)

The **Owl Carousel** particle is a diverse particle with multiple layouts, a wide range of features and customization options, and the ability to source content from both the CMS and custom items set up in the particle itself.

The **Owl Carousel** particle is based on the open source project of the same name by [Bartosz Wojciechowski](http://www.owlcarousel.owlgraphic.com/index.html).

Here are the topics covered in this guide:

* [Layouts](#layouts)
    - [Standard](#standard)
    - [NewsSlider](#newsslider)
    - [Showcase](#showcase)
* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#item-options)
    - [CMS Options](#cms-options)

## Layouts

Owl Carousel features four layouts, three of which are used in Protean's demo. You will see examples of these layouts below.

### Standard

The **Standard** layout is a great way to present written content from the CMS, as well as directly from the individual particle. You can display written content, images, or a combination of the two with ease.

### NewsSlider

The **NewsSlider** layout is a great way to pack a lot of written content into a single space. With easy-to-configure tabs opening content items in the particle, this layout type is great for showcasing features and/or providing details about a variety of topics.

### Showcase

The **Showcase** layout enables you to set up a quick and elegant series of links to important content, along with thumbnails. Great for adding a simple list of featured headlines.

### Testimonial

The **Testimonial** layout enables you to display testimonies from customers, users, and other individuals in a simple and elegant fashion.

## Configuration

The settings panel for **Owl Carousel** is filled with options, bells, and whistles you can use to configure your particle. Here is a quick breakdown of the settings you will find in this particle in Protean.

### Main Options 

![](assets/particle_owl4.jpeg)

| Option          | Description                                                                                                                                  |
| :-----          | :-----                                                                                                                                       |
| CSS Classes     | Sets the CSS class for the content of the particle.                                                                                          |
| Content Source  | Select **Particle** or **Joomla** to determine where particle content is pulled from.                                                        |
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

| Option                           | Description                                                                                                                                                      |
| :-----                           | :-----                                                                                                                                                           |
| Owl Carousel Item Name           | Sets the name for the item in the carousel. This is only seen on the back end.                                                                                   |
| Owl Carousel Item Image          | Enables you to define an image for the item. This is the primary image that appears most prominently as the item is displayed.                                   |
| Owl Carousel Item Icon           | You can use this field to assign an icon to the item that appears with its **Title**. For example: `fa fa-cogwheel fa-fw`.                                       |
| Owl Carousel Item Title          | Enter a title for the item here.                                                                                                                                 |
| Owl Carousel Item Subtitle       | Enter the item's subtitle here. Typically displayed just below the title in a smaller font.                                                                      |
| Owl Carousel Item Author         | Enter the author of the item here. Great for attributing authors of written content linked by the item.                                                          |
| Owl Carousel Item Author Image   | This image field enables you to add a smaller thumbnail image for the author. Displayed typically next to the author's name.                                     |
| Owl Carousel Item Description    | This is the main content body of the item. Enter any information you want to have displayed in paragraph form here.                                              |
| Owl Carousel Item Link           | This is where you would enter a link you want the item to send visitors to when clicked.                                                                         |
| Owl Carousel Item Link Text      | This text is what the visitor would click to activate the link.                                                                                                  |
| Owl Carousel Item Target         | Sets how you would like the link to open. You can choose between **Self** and **New Window**. Self will open in the current tab, and new window opens a new tab. |
| Owl Carousel Item Button Classes | This field enables you to enter a CSS class you would like to apply to the clickable link's button.                                                              |

### CMS Options

These options are only useful if you select **Joomla** as the **Content Source**.

![](assets/particle_owl6.jpeg)

| Option            | Description                                                                                   |
| :-----            | :-----                                                                                        |
| Joomla Categories | Enables you to set which categories (by name) appear in the particle.                         |
| Articles to Fetch | Sets the number of articles you want to have fetched by the particle from the CMS.            |
| Intro Image       | Sets whether or not the particle will display the article's assigned intro image.             |
| Categories Names  | Sets whether or not the particle will display the article's category name.                    |
| Article Title     | Sets whether or not the particle will display the article's title.                            |
| Intro Text        | Sets whether or not the particle will display the article's intro text.                       |
| Author            | Sets whether or not the particle will display the article's author.                           |
| Link              | Enables or disables direct links to the article(s) from the particle.                         |
| Link Text         | You can use this field to enter text you would like to have appear. For example: `Read More`. |
