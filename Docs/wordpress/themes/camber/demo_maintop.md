---
title: Camber: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Camber Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/camber:Camber

---

Main Top Section
-----

![][demo]

:   1. **RokGallery** [10%, 7%, se]
    2. **RokNewsPager** [10%, 66%, se]

Here is the widget breakdown for the Main Top section:

* RokGallery
* Gantry Divider
* RokNewsPager

#### RokGallery

This area of the demo is a RokGallery widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokGallery gallery. You can do this by navigating to **Administration -> RokGallery Admin** and creating a new gallery.

You can find out more about RokGallery and how to set up and modify widgets by visiting our [RokGallery documentation][rokgallery].

Here is a look at the **Features Layout Options** for this widget.

| Option                  | Setting                   |
| :----------             | :----------               |
| Show Title              |                           |
| Gallery                 | Front Main                |
| Link Type               | Link to RokBox Full Image |
| Default Linked Item     | RokGallery                |
| Show Title              | No                        |
| Show Caption            | No                        |
| Sort By                 | Title                     |
| Sort Direction          | Ascending                 |
| Slice Limit             | 10                        |
| Gallery Style           | Light                     |
| Gallery Layout          | Slideshow Layout          |
| Show Arrows             | Only on Hover             |
| Navigation Type         | Thumbnails                |
| Slice Animation Type    | Random                    |
| Animation Duration (ms) | 500                       |
| Autoplay                | Enabled with Progress     |
| Autoplay Delay          | 7                         |

Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

[demo]: assets/demo_4.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
