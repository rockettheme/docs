---
title: Alerion: Recreating the Demo - Floating Module Top
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/alerion:Alerion

---

Floating Module Top Section
-----

![][demo]

:	1. **Text** [10%, 16%, se]

The upper half of the floating widget set is a standard **Text** widget. The lower half, which remains in place, is found in the **Floating Module Bottom** widget position.

>> This widget will not appear unless the **Alerion Floating Widget** is placed in a regular widget position. On the front page of our demo, we placed that widget in the **Showcase** position.

### Text

You will need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~ .html
<div class="rt-eventlist">
    <div class="gantry-width-70 gantry-width-block">
    <span><strong>Space Needle</strong></span><br>
    <span><em class="hidden-tablet">Brooklyn</em> <strong>FRI, FEB 29</strong>, 2013</span>
  </div>
  <div class="gantry-width-30 gantry-width-block">
    <div class="rt-floatright">
      <span class="rt-price"><span class="rt-currency">$</span>75</span>
    </div>  
  </div>
  <div class="clear"></div>
  <div class="rt-dotted-divider"></div>
  <div class="gantry-width-70 gantry-width-block">
    <span><strong>New York</strong></span><br>
    <span><em class="hidden-tablet">NY</em> <strong>MON, MAR 04</strong>, 2013</span>
  </div>
  <div class="gantry-width-30 gantry-width-block">
    <div class="rt-floatright">
      <span class="rt-price"><span class="rt-currency">$</span>85</span>
    </div>  
  </div>
  <div class="clear"></div>
  <div class="rt-dotted-divider"></div>
  <div class="gantry-width-70 gantry-width-block">
    <span><strong>Brooklyn</strong></span><br>
    <span><em class="hidden-tablet">Brooklyn</em> <strong>THU, MAR 21</strong>, 2013</span>
  </div>
  <div class="gantry-width-30 gantry-width-block">
    <div class="rt-floatright">
      <span class="rt-price"><span class="rt-currency">$</span>95</span>
    </div>  
  </div>
  <div class="clear"></div>
</div>
<div class="rt-order">
  <div class="gantry-width-50 gantry-width-block rt-center">
    <img alt="image" src="http://demo.rockettheme.com/wordpress-themes/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/showcase/cards.jpg" class="largemargintop">
  </div>
  <div class="gantry-width-50 gantry-width-block">
    <div class="rt-floatright">
      <script>
      window.addEvent('domready', function(){
          var x = new Fx.Scroll(window, {
              wheelStop: false, 
              duration: 8000, 
              transition: 'quad:in:out',
              onComplete: function(){
                  if (window.getScroll().y > 0) x.start(0, 0);
              }
          });
          $('rt-quicktour').addEvent('click', function(){
              x.start(0, window.getScrollSize().y);
          });
      });
      </script>     
      <a id="rt-quicktour" class="btn btn-large btn-primary rt-large-button" href="#"><span class="hidden-tablet">Quick </span>Tour</a>
    </div>    
  </div>
  <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `[span class=\"icon-tags\"][/span] Your Tickets[span class=\"hidden-tablet\"] Here[/span]`.
* Set the **Box Variation** to **Box 1**.
* Set the **Title Variation** to **Title 3**.
* Enter `jagged fp-floating-top` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
