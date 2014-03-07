---
title: Paradigm: Recreating the Demo - Main Bottom
description: Your Guide to Recreating Elements of the Paradigm Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/paradigm:Paradigm

---

Main Bottom Section
-----

![][demo]

:   1. **RokSprocket** [10%, 8%, se]
    2. **Gantry NewsFlash** [10%, 50%, se]

Here is the widget breakdown for the Main Bottom section:

* RokSprocket
* Gantry Divider
* Gantry NewsFlash


#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Description** is custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

**Description**

~~~ .html
<span class="rt-testimonial-item">Paradigm is a rich infusion of elegant,
transparent visuals with a contemporary design frame, to create a subtle but
invigorating site experience. <span class="hidden-tablet">The dynamically
changing, transparent to opaque, fixed header, combines design and
functionality.</span> </span><span class="rt-testimonial-img"><img alt="image"
src=
"http://demo.rockettheme.com/live/wordpress/paradigm/wp-content/rockettheme/rt_paradigm_wp/frontpage/mainbottom/img1.jpg"></span><span class="rt-testimonial-author">Linda
Smith</span><span class="rt-testimonial-position">CEO of Hexeris</span>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            |      Setting |
| :---------------- | :----------- |
| Display Limit     |            2 |
| Theme             |      Default |
| Preview Length    |            ∞ |
| Strip HTML Tags   |           No |
| Previews Per Page |            1 |
| Items Per Row     |            1 |
| Arrow Navigation  |         Show |
| Pagination        |         Hide |
| Animation         | Fade Delayed |
| Autoplay          |      Disable |
| Autoplay Delay    |            5 |
| Image Resize      |      Disable |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Enter `What Our Customers Said` in the **Tilte** field.
* Set the **Title Variation** option to **Title 2**.
* Set the **Align Variation** option to _**RT-Center**.
* Enter `fp-roksprocket-strips icon-comments rt-stacked` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry NewsFlash

Gantry NewsFlash is a widget used to display information from the blog in a way that sits apart from the typical mainbody. In this case, it's used to display posts that exist in the **Front Page** category.

| Option          | Setting    |  
| :-------------- | :--------- |  
| Category        | Front Page |  
| Show Post Title | Yes        |  
| Linked Titles   | No         |  
| Header Level    | H1         |  
| Post Content    | Content    |  
| Read More Link  | Show       |  
| Number of Posts | 1          |  
| Order Results   | Date       |  

When you have done this, you will need to complete the following.

* Enter `Latest From the Blog` in the **Tilte** field.
* Set the **Title Variation** option to **Title 2**.
* Set the **Align Variation** option to _**RT-Center**.
* Enter `fp-newsflash icon-list-alt` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Featured Article

The article featured in the **Gantry NewsFlash** widget is set to the **Front Page** category. Below, you will find the **Title** and **Content Body** used in the demo.

**Title**

~~~ .html
Dynamic Control of Page Layouts
~~~

**Content**

~~~ .html
<p>The Gantry Grid System splits each widget row, such as showcase, into a maximum of 6 widgets, and their widths can be individually determined.</p>

<p class="hidden-tablet">In addition, you can also force a number of widget positions for a particular row, which will infuse blank grid positions in, to suit your desired layout. Furthermore, the layouts can be configured on a per-override basis.</p>

<!--more-->

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi.</p>

<p>Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consecetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>
~~~

[demo]: assets/demo_6.jpeg
[roksprocket]: ../../plugins/roksprocket/
