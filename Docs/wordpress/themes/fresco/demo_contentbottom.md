---
title: Fresco: Recreating the Demo - Content Bottom
description: Your Guide to Recreating Elements of the Fresco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/fresco:Fresco

---

Content Bottom Section
-----
Here's the widget breakdown for the Content Top section:

* RokGallery
* Gantry Divider
* Text

#### RokGallery
![][demo1]
This RokGallery widget is used to display a **Grid** of images in order to demonstrate what RokGallery can do to enhance your site's look.

Here's a breakdown of the widget options: 

| Option | Setting |
|:-------|------:|
| Title | Adobe Fireworks PNG Sources |
| Link Type | None |
| Show Title | No |
| Show Caption | No |
| Sort By | Order |
| Sort Direction | Ascending |
| Slice Limit | 6 |
| Gallery Style | Light |
| Gallery Layout | Grid Layout |
| Grid Columns | 3 |
| Custom Variations | `fp-rokgallery bg5` |

This will create the widget, but you'll need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text
![][demo2]
The Text widget in this section is titled **Plugins Support** and has the following in the main text field.

~~~
<p><strong>RokTwittie</strong> displays tweets from any Twitter account and/or search terms; and has <strong>Fresco</strong>-specific styling.</p>

<img src="http://demo.rockettheme.com/wordpress/wp_fresco/wp-content/rockettheme/rt_fresco_wp/frontpage/general/cb-img1.jpg" class="rt-image cb-img1" alt="image" width="330" height="145" />
~~~

* Set the **Title** to `Plugins Support`.
* Set the **Custom Variations** field to `bg6`.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_10.jpeg
[demo2]: assets/demo_11.jpeg
[rokgallery]: ../../plugins/rokgallery