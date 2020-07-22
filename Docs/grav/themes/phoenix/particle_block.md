---
title: Phoenix: Block Content Particle
description: Your Guide to Recreating Elements of the Phoenix Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/phoenix:Phoenix

---

## Introduction

![](assets/particle_block1.png)

The **Block Content** particle is a great way to create a clean and simple content block with images and text. 

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

![](assets/particle_block2.png)

| Option         | Description                                                                                                                                              |
| :-----         | :-----                                                                                                                                                   |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end.                                                      |
| Content Source | Choose between **Particle** and **Grav** as the Content Source.                                                                                        |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                                                                          |
| Title          | Enter a title for the particle that appears on the front end.                                                                                            |
| Icon           | Set the icon that appears next to the title.                                                                                                             |
| Image          | Set a main image that appears separate from any Block Item images.                                                                                       |
| Headline       | Enter a headline you want to appear on the front end.                                                                                                    |
| Description    | Enter the text you wish to have appear as the description for the particle. This text appears below the title and headline.                              |
| Button Label   | Customize the text you want to have appear in the link button.                                                                                           |
| Button Link    | Customize the link you want the link button to go to.                                                                                                    |
| Button Classes | Add CSS class(es) you would like to have apply to the button.                                                                                            |
| Target         | Set the target for the button. You can choose between **Self** which opens the link in the current tab or **New Window** which opens links in a new tab. |

### Particle Item Options

These items make up the individual featured items in the particle. 

![](assets/particle_block3.png)

![](assets/particle_block4.png)

| Option          | Description                                                                                                                                              |
| :-----          | :-----                                                                                                                                                   |
| Item Name       | The item name becomes the title of the content block item.                                                                                               |
| Accent          | Select an accent color used for the item.                                                                                                                |
| Icon            | Select the icon you would like to have appear with the title area in the block item.                                                                     |
| Image           | Select the image you would like to have displayed with the item.                                                                                         |
| Lightcase Image | If you would like to have a popup appear with a larger version of the image when the image is clicked, this is where you assign the larger image.        |
| Caption         | Add a caption for the image here.                                                                                                                        |
| Subtitle        | Add a subtitle for the item here.                                                                                                                        |
| Description     | Enter a description for the item here, appears as paragraphed text.                                                                                      |
| CSS Classes     | Enter any CSS classes you would like to have apply just to this item.                                                                                    |
| Button Label    | Enter the text you would like to have appear as the button link.                                                                                         |
| Button Link     | Enter the url you want that link to go to.                                                                                                               |
| Button Classes  | Enter any CSS classes you want to have apply just to the button.                                                                                         |
| Target          | Set the target for the button. You can choose between **Self** which opens the link in the current tab or **New Window** which opens links in a new tab. |

### Pages

![](assets/particle_block5.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how pages are displayed.

![](assets/particle_block6.png)

| Option          | Description                                                                                             |
| :-----          | :-----                                                                                                  |
| Image           | Choose to **Show** or **Hide** the page's image.                                                        |
| Title           | Choose to **Show** or **Hide** the page's title.                                                        |
| Title Limit     | Enter a character limit for page's title displayed in this particle.                                    |
| Article Text    | Choose between **Introduction** or **Full Article** as the content type. You can also **Hide** content. |
| Text Limit      | Enter a character limit for page's content displayed in this particle.                                  |
| Text Formatting | Choose between **Plain Text** and **HTML** for the page's content to be displayed in.                   |
| Button Link     | Choose to **Enable** or **Disable** the page's link.                                                    |
| Button Label    | Enter a label to appear in the button.                                                                  |
| Link Target     | Choose which window/tab the link opens to.                                                              |