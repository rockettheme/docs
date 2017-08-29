---
title: Notio: Particles Particle
description: Your Guide to Recreating Elements of the Notio Demo for WordPress
breadcrumb: /wordpress:WordPress/!templates:Templates/notio:Notio

---

## Introduction

![](assets/particle_particles.jpeg)

The **Particles** particle makes it easy to bring your site to life with gorgeous animated backgrounds that don't distract from your content. You'll find this particle in use in the **Top** section of the home page in our demo.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)

## Configuration

### Main Options 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_particles2.jpeg)

| Option                | Description                                                                                                                                                           |
| :-----                | :-----                                                                                                                                                                |
| Particle Name         | Enter the name you would like to assign to the particle. This only appears in the back end.                                                                           |
| CSS Classes           | Enter any CSS class(es) you wish to have affect the particle.                                                                                                         |
| Configuration Presets | Choose between **rectangles**, **circles**, **triangles**, **polygons**, **stars**, and **circles and lines**.                                                        |
| Sync Presets          | Enable presets synchronization. For example, template styles **Preset 1** will sync with first particle configuration preset.                                         |
| Section Only          | Enable or Disable the display of the animation within the bounds of the section it is placed in. Disabling it displays the background on the entire page (see below). |
| Custom Configuration  | Give your site a custom look with this field. Explained in more detail below.                                                                                         |

A custom configuration file gives you almost endless possibilities to animate your background. You can generate your configuration file (with realtime preview) here: http://vincentgarreau.com/particles.js/. Then simply upload it to your theme's json / particlejs directory.

The **Top** and **Slideshow** are where you would want to place this particle in Notio if you wish to display the animation throughout the whole page by disabling the **Section Only** option.