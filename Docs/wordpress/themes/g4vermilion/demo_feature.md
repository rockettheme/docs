---
title: Vermilion: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Feature Section
-----

![][demo]

:   1. **RokSprocket (Headlines)** [10%, 7%, se]
    2. **Text** [20%, 7%, se]

Here is the widget breakdown for the Feature section:

* RokSprocket (Headlines)
* Text

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Headlines** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate posts or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting                                                                  |
| :---------- | :----------                                                              |
| Image       | None                                                                     |
| Link        | None                                                                     |
| Description | `The Gantry Framework is the powerful platform that supports Vermilion.` |

Here is a look at the **Headlines Layout Options** for this widget.

| Option           | Setting      |
| :----------      | :----------  |
| Theme            | Default      |
| Label Text       | Recent News: |
| Display Limit    | ∞            |
| Preview Length   | ∞            |
| Strip HTML Tags  | Yes          |
| Arrow Navigation | Show         |
| Animation        | Fade         |
| Autoplay         | Disable      |
| Autoplay Delay   | 5            |
| Image Resize     | Disable      |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Set the **Widget Variations** to **Box 1, No Margin All**.
* Enter `fp-feature-02` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img src="http://(Your Site URL)/wp-content/rockettheme/rt_vermilion_wp/home/fp-feature/img-01.jpg" alt="image" />
        <div class="rt-desc-overlay fp-feature-animate-1">
            <h3>Advanced &amp; adaptable CSS <span class="hidden-tablet">dropdown </span>menu</h3>
            <p class="rt-text-small">Two Menu Options</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge"><a href="#"><span class="fa fa-dashboard"></span></a></div>
        <h5 class="medpaddingtop">Multiple Configurable Navigation Systems</h5>
        <p>Choose between our CSS-based dropdown menu with advanced features such as adjustable columns, or SplitMenu.</p>
    </div>
</div>

<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img src="http://(Your Site URL)/wp-content/rockettheme/rt_vermilion_wp/home/fp-feature/img-02.jpg" alt="image" />
        <div class="rt-desc-overlay fp-feature-animate-2">
            <h3>Integrated styling for RokSprocket<span class="visible-large"> layout modes</span></h3>
            <p class="rt-text-small">Content Widget</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge"><a href="#"><span class="fa fa-comments-o"></span></a></div>
        <h5 class="medpaddingtop">Versatile Content Switchblade Plugin</h5>
        <p>Multiple default layout modes to choose from, and an advanced &amp; powerful custom administrative interface.</p>
    </div>
</div>

<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img src="http://(Your Site URL)/wp-content/rockettheme/rt_vermilion_wp/home/fp-feature/img-03.jpg" alt="image" />
        <div class="rt-desc-overlay fp-feature-animate-3">
            <h3>Powerful and free core framework<span class="visible-large"> for WordPress</span></h3>
            <p class="rt-text-small">Gantry Framework</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge"><a href="#"><span class="fa fa-book"></span></a></div>
        <h5 class="medpaddingtop">Extensive Array of Standard Features</h5>
        <p>Gantry is the powerful core framework that sits at the core of Vermilion, providing a rich feature set.</p>
    </div>
</div>

<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img src="http://(Your Site URL)/wp-content/rockettheme/rt_vermilion_wp/home/fp-feature/img-04.jpg" alt="image" />
        <div class="rt-desc-overlay fp-feature-animate-4">
            <h3><span><span class="visible-tablet">Several</span><span class="hidden-tablet">Eight stylistics and </span><span class="hidden-large"><span class="hidden-tablet">other</span></span><span class="visible-large">several structural</span> widget variations</span></h3>
            <p class="rt-text-small">Customization</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge"><a href="#"><span class="fa fa-unlink"></span></a></div>
        <h5 class="medpaddingtop">Quick and Easy Widget Individualization</h5>
        <p>A diverse selection of configurable widget variations, either stylistic or structural in function.</p>
    </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Widget Variations** to **RT-Center**.
* Enter `fp-feature-01` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg