---
title: Alerion: Recreating the Demo - Floating widget Bottom
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/alerion:Alerion

---

Floating widget Bottom Section
-----

![][demo]

:	1. **Text** [68%, 16%, se]

The lower half of the floating widget set is a standard **Text** widget. The upper half, which remains in place, is found in the **Floating Module Top** widget position.

>> This widget will not appear unless the **Alerion Floating Module** is placed in a regular widget position. On the front page of our demo, we placed that widget in the **Showcase** position.

### Text

You'll need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~ .html
<div class="gantry-width-30 gantry-width-block rt-center">
    <em><strong>Who's Going</strong></em>
</div>

<div class="gantry-width-70 gantry-width-block">
  <div class="rt-floatright">
    <button class="btn btn-inverse rt-large-button"><span class="icon-facebook"></span> <span class="hidden-tablet">Connect with </span>Facebook</button>
  </div>    
</div>

<div class="clear largemarginbottom largepaddingbottom">&nbsp;</div>

<div class="gantry-width-30 gantry-width-block rt-center">
  <span class="rt-price-alt"><span class="rt-currency">$</span> 129</span>
</div>

<div class="gantry-width-70 gantry-width-block">
  <div class="rt-floatright">
    <a href="#" class="btn btn-large btn-primary rt-large-button"><span class="visible-tablet">Signup</span><span class="hidden-tablet">Register Today</span> <span class="icon-arrow-right"></span></a>
  </div>    
</div>

<div class="clear"></div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Box Variation** to **Box 1**.
* Enter `fp-feature-b jaggedtop largemarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg