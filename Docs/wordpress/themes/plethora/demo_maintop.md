---
title: Plethora: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Main Top Section
-----

![][demo]

:   1. **RokSprocket (Lists)** [8%, 6%, se]
    2. **Text** [8%, 50%, se]
    3. **RokSprocket (Lists)** [8%, 67%, se]

Here is the widget breakdown for the Main Top section:

* RokSprocket (Lists)
* Gantry Divider
* Text
* Gantry Divider
* RokSprocket (Lists)

#### RokSprocket (Lists)

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

We used the **WordPress** provider, pulling information directly from articles. The default link has been set to `#` and the images are custom set for each item in the **Filtered Article List**.

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting              |
| :------------------ | :------              |
| Theme               | Default              |
| Display Limit       | ∞                    |
| Collapsible Preview | Disable              |
| Preview Length      | 20                   |
| Strip HTML Tags     | Yes                  |
| Previews Per Page   | 3                    |
| Article Details     | Show Author and Date |
| Arrow Navigation    | Show                 |
| Pagination          | Show                 |
| Autoplay            | 5                    |
| Image Resize        | Disable              |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Top News`.
* Set the **Widget Variations** to **Title 1**.
* Enter `fp-roksprocket-lists-maintop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-maintop-b/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Error</span>
        </div>
        <div class="rt-image-content">
            <p class="smallmarginbottom">Custom 404 error page override</p>
            <span class="rt-text-small"><em>error.php</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-maintop-b/img-02.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Maintenance</span>
        </div>      
        <div class="rt-image-content">
            <p class="smallmarginbottom">Custom maintenance page override</p>   
            <span class="rt-text-small"><em>maintenance.php</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="http://demo.rockettheme.com/live/wordpress/plethora/wp-content/rockettheme/rt_plethora_wp/home/fp-maintop-b/img-03.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Coming Soon</span>
        </div>          
        <div class="rt-image-content">
            <p class="smallmarginbottom">Unique coming soon offline page</p>
            <span class="rt-text-small"><em>comingsoon.php</em></span>  
        </div>      
    </div>      
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Top Galleries` in the **Title** field.
* Set the **Widget Variations** setting to **Title 1**.
* Enter `fp-maintop-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket (Lists)

The widget located in this section of the page is a **RokSprocket Lists** widget created in a very similar way to the previous RokSprocket widgets featured on the front page of the demo.

First, you will need to create the RokSprocket widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Lists** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

We used the **WordPress** provider, pulling information directly from articles. The default link has been set to `#` and custom icons are custom set for each item in the **Filtered Article List**. Here is a quick list of the icons used in our demo:

* fa fa-cloud-download
* fa fa-tasks
* fa fa-picture-o
* fa fa-dashboard
* fa fa-camera
* fa fa-folder-open-o

Here is a look at the **Lists Layout Options** for this widget.

| Option              | Setting              |
| :------------------ | :------              |
| Theme               | Default              |
| Display Limit       | ∞                    |
| Collapsible Preview | Disable              |
| Preview Length      | ∞                    |
| Strip HTML Tags     | No                   |
| Previews Per Page   | 6                    |
| Article Details     | Show Author and Date |
| Arrow Navigation    | Hide                 |
| Pagination          | Hide                 |
| Autoplay            | 5                    |
| Image Resize        | Disable              |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Set the **Title** to `Top Reviews`.
* Set the **Widget Variations** to **Title 1**.
* Enter `fp-roksprocket-lists-maintop2` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/