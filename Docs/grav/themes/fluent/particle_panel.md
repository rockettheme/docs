---
title: Fluent: Panel Slider Particle
description: Your Guide to Recreating Elements of the Fluent Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/fluent:Fluent

---

## Introduction

![](assets/particle_panel1.jpeg)

The **Panel Slider** particle creates beautiful image slideshows that work perfectly at the top of your page. The content of this particle can either be entered manually or generated automatically using content from the CMS.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#item-options)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_panel2.jpeg)

| Option         | Description                                                                                         |
| :-----         | :-----                                                                                              |
| Particle Name  | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source | Choose between **Particle** and **Grav** as the Content Source.                                   |
| Display Items  | Select the number of items to display in the particle.                                              |
| Prev / Next    | **Enable** or **Disable** the prev / next navigation.                                               |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_panel3.jpeg)

![](assets/particle_panel4.jpeg)

| Option      | Description                                              |
| :-----      | :-----                                                   |
| Item Name   | This is the name of the item.                            |
| Top Line    | Enter the line you wish to have appear at the top.       |
| Description | Enter a text description for the item.                   |
| Link        | Enter a URL you would like the item to link to.          |
| Link Label  | Enter a text label you wish to have appear as the link.  |
| Target      | Choose the target tab you would like the URL to open to. |

### Pages

![](assets/particle_panel5.jpeg)

| Option             | Description                                                                                                     |
| :-----             | :-----                                                                                                          |
| Categories         | Select the categories of articles this particle will display.                                                   |
| Pages           | Select the number of articles you would like the particle to fetch.                                             |
| Featured Pages  | Choose how Featured Pages should be filtered. Choose between **Include**, **Exclude**, or **Only Featured**. |
| Number of Pages | Enter the maximum number of articles to display.                                                                |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article).                    |
| Order By           | Choose the type of factor to order by.                                                                          |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.                                 |

### Display

This section configures how articles are displayed.

![](assets/particle_panel6.jpeg)

| Option             | Description                                                                  |
| :-----             | :-----                                                                       |
| Image              | Display the image assigned to the article's **Intro**, **Full** or **None**. |
| Article Text       | Choose which text to pull from the article.                                  |
| Text Limit         | Set a limit (in characters) of the text to appear in the item.               |
| Text Formatting    | Choose between plain text and HTML as the text format.                       |
| Title              | **Show** or **Hide** the article's title.                                    |
| Title Limit        | Enter the maximum number of characters in the title to display.              |
| Date               | Enter a date for the item.                                                   |
| Date Format        | Select the format you want the date to be displayed in.                      |
| Read More          | Show or Hide the read more link.                                             |
| Read More Label    | Add a text label for the read more link.                                     |
| Button CSS Classes | Add any CSS class(es) you wish to have apply to the button.                  |