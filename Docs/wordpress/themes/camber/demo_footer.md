---
title: Camber: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Camber Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/camber:Camber

---

Footer Section
-----

![][demo1]

:   1. **RokGallery** [15%, 6%, se]
    2. **Text 1** [15%, 37%, se]
    3. **Text 2** [40%, 37%, se]
    4. **Text 3** [15%, 76%, se]
    5. **Text 4** [55%, 76%, se]

Here is the widget breakdown for the Footer section:

* RokGallery
* Gantry Divider
* Text
* Text
* Gantry Divider
* Text
* Text

#### RokGallery (Grid)

This RokGallery widget is used to display a **Grid** of images in order to demonstrate what RokGallery can do to enhance your site's look.

Here is a breakdown of the widget options:

| Option           | Setting                    |
| :----------      | :----------                |
| Title            | `Photo Gallery`            |
| Link Type        | Link to RokBox Slice Image |
| Show Title       | No                         |
| Show Caption     | No                         |
| Sort By          | Title                      |
| Sort Direction   | Ascending                  |
| Slice Limit      | 9                          |
| Gallery Style    | Light                      |
| Gallery Layout   | Grid Layout                |
| Grid Columns     | 3                          |

This will create the widget, but you will need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="nomarginbottom">
<em class="bold">DEMO NOTICE:</em> All demo content is for sample purposes only, intended to represent a live site. RokGallery images are licensed from <a target="_blank" href="http://www.bigstockphoto.com/">BigStockPhoto</a> and are for use on THIS DEMO SITE ONLY.
</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Demo Information` in the **Title** field.
* Enter `nomarginbottom nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="smallmarginbottom"><img class="rt-image" alt="Footer" src="http://demo.rockettheme.com/live/wordpress/camber/wp-content/rockettheme/rt_camber_wp/general/footer1.jpg" height="150" width="360" /></p>
<span>1111 6th Street - San Francisco CA 96542</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Our Location` in the **Title** field.
* Enter `nomargintop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<ul class="menu">
        <li class="item28">
                <a href="#">
            <span class="menuitem">ColorChooser</span>
            </a>
                    </li>
                <li class="item18">
                <a href="#">
            <span class="menuitem">Gantry Framework</span>
            </a>
                    </li>
                <li class="item29">
                <a href="#">
            <span class="menuitem">Fusion with MegaMenu</span>
            </a>
                    </li>
                <li class="item30">
                <a href="#">
            <span class="menuitem">29 Widget Variations</span>
            </a>
                    </li>
        </ul>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Core Features` in the **Title** field.
* Enter `nomarginbottom nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 4

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<span class="text-icon phone">1 (555) 555-555</span>
<span class="text-icon email">contact@camber.com</span>
<span class="text-icon twitter">@cambercom</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Contact Details` in the **Title** field.
* Enter `nomargintop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_6.jpeg
[rokgallery]: ../../plugins/rokgallery
