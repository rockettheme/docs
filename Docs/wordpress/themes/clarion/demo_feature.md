---
title: Clarion: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Clarion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/clarion:Clarion

---

Feature
-----

![][demo]

:   1. **Text** [20%, 6%, se]
    2. **RokGallery** [20%, 30%, se]

Here is the widget breakdown for the Feature section:

* Text
* Gantry Divider
* RokGallery

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<p><strong>Clarion</strong>, the September 2012 theme release, is a subtle theme, primed for business use or as a platform for extensive individual customization.</p>
<a href="http://demo.rockettheme.com/live/wordpress/clarion/theme-features/" class="readon"><span>Read More</span></a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `About The Theme`.
* Switch the **Title Variation** option to **Title 5**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokGallery (Grid)

This RokGallery widget is used to display a **Grid** of images in order to demonstrate what RokGallery can do to enhance your site's look.

Here is a breakdown of the widget options: 

| Option              | Setting                   |
| :----------         | :----------               |
| Title               |                           |
| Link Type           | Link to RokBox Full Image |
| Default Linked Item | Home                      |
| Show Title          | Yes                       |
| Show Caption        | Yes                       |
| Sort By             | Order                     |
| Sort Direction      | Ascending                 |
| Slice Limit         | 3                         |
| Gallery Style       | Light                     |
| Gallery Layout      | Grid Layout               |
| Grid Columns        | 3                         |

This will create the widget, but you will need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

[rokgallery]: ../../plugins/rokgallery
[demo]: assets/demo_4.jpeg
