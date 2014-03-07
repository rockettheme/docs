---
title: Paradigm: Recreating the Demo - Feature
description: Your Guide to Recreating Elements of the Paradigm Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/Paradigm:Paradigm

---

Feature Section
-----

![][demo]

Here is the widget breakdown for the Feature section:

* Text

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<div class="module-title">
  <h2 class="title">Template Features<span class="rt-title-tag">Paradigm provides the tools you need to setup your website with ease.</span></h2>
</div>

<div class="gantry-width-block gantry-width-33">
    <div class="gantry-width-spacer">
    <div class="rt-feature-item">
      <div class="rt-arrow-right"></div>
      <h4 class="rt-uppercase">Dropdown Menu</h4>
      <p>A CSS based dropdown menu system<span class="hidden-tablet">, with numerous advanced features such as item icons and multiple columns</span>.</p>
    </div>

    <div class="rt-feature-item">
      <div class="rt-arrow-right"></div>
      <h4 class="rt-uppercase">Widget Variations</h4>
      <p>There are eight stylistic variations<span class="hidden-tablet">, to provide individual widget styling, as well as several structural variations</span>.</p>
    </div>

    <div class="rt-feature-item">
      <div class="rt-arrow-right"></div>
      <h4 class="rt-uppercase">Widget Positions</h4>
      <p>There are over 80 widget positions<span class="hidden-tablet">, most split into rows of 6, each with adjustable widths, globally or per override</span>.</p>
    </div>  

    <div class="rt-feature-item visible-large">
      <div class="rt-arrow-right"></div>
      <h4 class="rt-uppercase">SplitMenu</h4>
      <p>SplitMenu is a static menu option that displays parents in the header and children in the sidebar, as configurable.</p>
    </div>            
  </div>
</div>
<div class="gantry-width-block gantry-width-33">
  <div class="gantry-width-spacer rt-center nomarginbottom">
    <img src="http://demo.rockettheme.com/live/wordpress/paradigm/wp-content/rockettheme/rt_paradigm_wp/frontpage/feature/img1.png" alt="image" />
  </div>
</div>
<div class="gantry-width-block gantry-width-33">
  <div class="gantry-width-spacer">
    <div class="rt-feature-item">
      <div class="rt-arrow-left"></div>
      <h4 class="rt-uppercase">Preset Styles</h4>
      <p>Choose from eight preset style variations<span class="hidden-tablet">, with configurable options for text, link, accent, and background colors.</span></p>
    </div>

    <div class="rt-feature-item">
      <div class="rt-arrow-left"></div>
      <h4 class="rt-uppercase">RokSprocket</h4>
      <p>A versatile content display plugin<span class="hidden-tablet">, with integrated styling in Paradigm, including the Features layout option</span>.</p>
    </div>

    <div class="rt-feature-item">
      <div class="rt-arrow-left"></div>
      <h4 class="rt-uppercase">RocketLauncher</h4>
      <p>A custom WordPress installation package<span class="hidden-tablet"> that installs a near equivalent of the demo onto your server</span>.</p>
    </div>
    
    <div class="rt-feature-item visible-large">
      <div class="rt-arrow-left"></div>
      <h4 class="rt-uppercase">Typography</h4>
      <p>A beautiful and rich selection of typography, based on Boostrap, to emphasise and embellish the content elements.</p>
    </div>
  </div>
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Align Variation** option to **RT-Center**.
* Enter `fp-feature rt-big-title hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[roksprocket]: ../../plugins/roksprocket/