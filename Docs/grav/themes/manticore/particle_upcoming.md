---
title: Manticore: Upcoming Games Particle
description: Your Guide to Recreating Elements of the Manticore Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/manticore:Manticore

---

## Introduction

![](assets/particle_upcoming1.png)

The **Upcoming Games** particle lists important releases and upcoming news items in a clean, easy-to-follow particle.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Pages](#pages)
    - [Display](#display)

## Configuration

### Settings

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_upcoming2.png)

| Option         | Description                                                                                         |
|:-------------- |:--------------------------------------------------------------------------------------------------- |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source | Choose between **Particle** and **Grav** as the Content Source.                                |
| CSS Classes    | Enter any CSS class(es) you wish to have apply to the particle.                                     |
| Title          | Set a title for the particle.                                                                       |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_upcoming3.png)

![](assets/particle_upcoming4.png)

| Option    | Description                                                                      |
|:--------- |:-------------------------------------------------------------------------------- |
| Item Name | This is the name of the item. This appears as the item's title on the front end. |
| Date      | Enter a date for the page.                                                       |
| Link      | Enter a URL you would like the item to link to.                                  |
| Target    | Select a target window for the URL to open through.                              |

### Pages

![](assets/particle_upcoming6.png)

| Option             | Description                                                                            |
|:------------------ |:-------------------------------------------------------------------------------------- |
| Categories         | Select the categories of pages this particle will display.                             |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first page to return. The default is '0' (the first page). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the page ordering method.           |

### Display

This section configures how pages are displayed.

![](assets/particle_upcoming7.png)

| Option      | Description                                                     |
|:----------- |:--------------------------------------------------------------- |
| Title       | **Show** or **Hide** the page's title.                          |
| Title Limit | Enter the maximum number of characters in the title to display. |
| Date        | **Show** or **Hide** page dates.                                |
| Date Format | Set the format that dates will be displayed in.                 |
