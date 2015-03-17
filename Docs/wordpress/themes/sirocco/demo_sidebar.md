---
title: Sirocco: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Sirocco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/sirocco:Sirocco

---

Sidebar Section
-----

![Sidebar](assets/demo_10.jpeg)

Here is the widget breakdown for the Sidebar section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Impressive Selection of Icons</h2>
    <div class="boldfont">FontAwesome</div>
    <hr />
    <img src="http://demo.rockettheme.com/live/wordpress/sirocco/wp-content/rockettheme/rt_sirocco_wp/home/fp-sidebar/img-01.jpg" alt="" />
    <div><span class="rt-title-tag">Extra</span></div>  
</div>

<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Responsive Multi-Media Modals</h2>
    <div class="boldfont">RokBox</div>
    <hr />
    <img src="http://demo.rockettheme.com/live/wordpress/sirocco/wp-content/rockettheme/rt_sirocco_wp/home/fp-sidebar/img-02.jpg" alt="" />
    <div><span class="rt-title-tag">System Plugin</span></div>  
</div>

<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Simple Macros to Complex HTML</h2>
    <div class="boldfont">Shortcodes</div>
    <hr />
    <img src="http://demo.rockettheme.com/live/wordpress/sirocco/wp-content/rockettheme/rt_sirocco_wp/home/fp-sidebar/img-03.jpg" alt="" />
    <div><span class="rt-title-tag">WP Core</span></div>    
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting                   |
| :---------------- | :---------                |
| Custom Variations | `fp-sidebar hidden-phone` |

Leaving everything else at its default setting, select **Save**.
