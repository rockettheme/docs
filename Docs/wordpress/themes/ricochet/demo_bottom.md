---
title: Ricochet: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Ricochet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ricochet:Ricochet

---

Bottom Section
-----

![Bottom](assets/demo_12.jpeg)

Here is the widget breakdown for the Bottom section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row">
  <div class="gantry-width-container">
    <div class="gantry-width-50">
      <div class="rt-image-promo">
        <div class="rt-image-overlay">
          <img src="http://(Your Site URL)/wp-content/rockettheme/rt_ricochet_wp/home/fp-bottom/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-content-wrapper">
          <div class="rt-image-content">
            <span class="rt-label">Anticipation</span>
            <h2 class="title">Ricochet supports a simple Coming Soon page<span class="hidden-tablet"> with time counter</span></h2>
            <ul class="rt-tags">
              <li>Excitement</li>
              <li>Suspense</li>
            </ul>           
          </div>
        </div>      
      </div>
    </div>  
    <div class="gantry-width-50">
      <div class="rt-image-promo">
        <div class="rt-image-overlay">
          <img src="http://(Your Site URL)/wp-content/rockettheme/rt_ricochet_wp/home/fp-bottom/img-02.jpg" alt="image" />
        </div>
        <div class="rt-image-content-wrapper">
          <div class="rt-image-content">
            <span class="rt-label">Malfunction</span>
            <h2 class="title">Custom 404 page for Ricochet when page is not found</h2>
            <ul class="rt-tags">
              <li>Error</li>
              <li>Glitch</li>
            </ul>           
          </div>
        </div>      
      </div>
    </div>      
  </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-bottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
