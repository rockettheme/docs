---
title: Callisto: Grav Content Particle
description: Your Guide to Using Particles in Callisto for Grav
breadcrumb: /grav:Grav/!themes:Themes/callisto:Callisto

---

## Introduction

The **Grav Content** particle (Also known as `contentarray`) gives you the ability to directly list and pull in Grav posts directly from the CMS and present them in a clean, organized way. It's important to note this does not take the place of the **Page Content** particle which essentially displays any article content assigned to the page. This is a controlled, organized particle perfect for showcasing content.

### Main Options 

The particle's settings panel enables you to set exactly what content appears in the particle, and how it's presented. We have provided descriptions to the available options below.

![](assets/particle_grav2.jpeg)

| Option             | Description                                                                                                                                 |
| :-----             | :-----                                                                                                                                      |
| Categories         | Select the categories pages that appear in this particle should be sourced from.                                                            |
| Number of Pages    | Select the maximum number of pages to display.                                                                                              |
| Number of Columns  | Select the number of columns you wish to have the pages displayed in.                                                                       |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article).                                                |
| Order By           | Select how the pages should be ordered. This includes **Publish Date**, **Unpublish Date**, **Date**, **Last Modified Date**, and **Slug**. |
| Ordering Direction | Choose the direction ordered pages are displayed. You can choose: **Ascending** or **Descending**.                                          |
| CSS Classes        | Enter any CSS classes you want to apply to the particle.                                                                                    |
| Tag Attributes     | Enables you to apply extra tag attributes to the particle.                                                                                  |

![](assets/particle_grav3.jpeg)

| Option       | Description                                                                                                                      |
| :-----       | :-----                                                                                                                           |
| Image        | Select to **Show** or **Hide** the article's image in the particle.                                                              |
| Article Text | Choose to display the **Introduction**, **Full Article**, or to **Hide** this content.                                           |
| Text Limit   | Set a limit (in characters) for the article text.                                                                                |
| Formatting   | Choose between **Plain Text** and **HTML**.                                                                                      |
| Title        | Select to **Show** or **Hide** the article's title in the particle.                                                              |
| Title Limit  | Enter the maximum number of characters in the title to display in the particle.                                                  |
| Date         | Select which date (if any) to show in the particle. You can choose: **Hide**, **Created**, **Last Modified**, and **Published**. |
| Date Format  | Select the format by which you want the date to appear.                                                                          |

![](assets/particle_grav4.jpeg)

| Option             | Description                                                        |
| :-----             | :-----                                                             |
| Read More          | Select to **Show** or **Hide** the read more link in the particle. |
| Read More Label    | Enter the text you want to appear as the read more link.           |
| Button CSS Classes | Enter any CSS classes you want to apply to the read more button.   |

![](assets/particle_grav5.jpeg)

| Option         | Description                                                            |
| :-----         | :-----                                                                 |
| Author         | Select to **Show** or **Hide** the article's author in the particle.   |
| Category       | Select to **Show** or **Hide** the article's category in the particle. |
| Category Route | Enter the route to the category page.                                  |
