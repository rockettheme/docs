---
title: Manticore: BookBlock Particle
description: Your Guide to Recreating Elements of the Manticore Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/manticore:Manticore

---

## Introduction

![](assets/particle_book1.png)

The **BookBlock** particle enables you to present content in a way that mimics a book, with its own page turning animation and plenty of room for written and visual content.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#item-options)
    - [Articles](#articles)
    - [Articles Display](#articles-display)

## Configuration

### Main Options 

![](assets/particle_book2.png)

| Option         | Description                                                                           |
| :-----         | :-----                                                                                |
| CSS Classes    | Sets the CSS class for the content of the particle.                                   |
| Content Source | Select **Particle** or **Joomla** to determine where particle content is pulled from. |
| Section Height | Set the height of the section (in pixels).                                            |
| Loop           | **Enable** or **Disable** looping.                                                    |

### Item Options

These items only appear on the front end if you select **Particle** as the **Content Source**.

![](assets/particle_book3.png)

![](assets/particle_book4.png)

| Option            | Description                                                                                     |
| :-----            | :-----                                                                                          |
| Category          | Enter the category you would like to appear in the particle.                                    |
| Subject           | Enter a subject for the item.                                                                   |
| Intro             | Enter the introductory text you would like to appear in the particle.                           |
| Content           | Enter the content you would like to appear in the particle.                                     |
| Read More Label   | Enter the text you would like to have link to the link you set in the **Read More Link** field. |
| Read More Link    | Enter a URL for the Read More link to take users to.                                            |
| Read More Target  | Select a target window for links to open into.                                                  |
| Read More Classes | Enter any CSS Class(es) that you want to have apply to the read more.                           |
| Image             | Select the image you would like to have appear on the right side of the particle.               |


### Articles

These options are only useful if you select **Joomla** as the **Content Source**.

![](assets/particle_book5.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Enter the categorie(s) you would like to appear in the particle.                       |
| Articles           | Enter the number of articles you would like to have loaded in the particle.            |
| Featured Articles  | Choose whether or not to allow Featured Articles to appear in the particle's rotation. |
| Number of Articles | Set the number of articles to appear as items in the particle.                         |
| Start From         | Set a starting count for the first item.                                               |
| Order by           | Choose how articles are ordered. You can set it to everything from Publish Date to ID. |
| Ordering Direction | Set **Ascending** or **Descending** ordering.                                          |

### Articles Display

These options are only useful if you select **Joomla** as the **Content Source**.

![](assets/particle_book6.png)

| Option           | Description                                                                               |
| :-----           | :-----                                                                                    |
| Image            | **Enable** or **Disable** the image appearing in the particle.                            |
| Categories Names | **Enable** or **Disable** the category of the article in the particle.                    |
| Title            | **Enable** or **Disable** the title of the article appearing in the particle.             |
| Title Limit      | Set the limit (in characters) for the title being displayed.                              |
| Article Text     | **Enable** or **Disable** the **Article Text** appearing under the image in the particle. |
| Text Limit       | Set a limit of text (in characters) appearing in the item.                                |
| Text formatting  | Choose between plain text and                                                             |
| Button Label     | Enter the text you would like to appear in the Read More link.                            |
| Link Target      | Select a target window for links to open into.                                            |