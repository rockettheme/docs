---
title: Alerion: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/alerion:Alerion

---

Utility Section
-----

![][demo]

:	1. **Text** [40%, 30%, se]
	2. **Text** [12%, 68%, se]

Here is the widget breakdown for the Utility section:

* Text
* Gantry Divider
* Text

### Text

You will need to enter the following in the main text field to create this text widget as it appears in our demo. This widget creates the map with its associated pins.

~~~
<img class="rt-map rt-img-circle hidden-phone" src="http://demo.rockettheme.com/wordpress-themes/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/utility/img1.jpg" alt="image" />
<img class="rt-map-phone visible-phone" src="http://demo.rockettheme.com/wordpress-themes/wp_alerion/wp-content/rockettheme/rt_alerion_wp/frontpage/utility/img2.png" alt="image" />

[span class="rt-map-pins hidden-phone"]
    [pin top="-30px" left="-50px"]1[/pin]
  [pin top="60px" left="60px"]2[/pin]
  [pin top="50px" left="-335px"]3[/pin]
[/span]
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-utility-a` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Text

The Text widget in the section requires RokCandy to display the title properly. The `[span]` tags are used to add the `hidden-tablet` CSS override to the title so the word `Detail` is hidden on smaller screens.

The following should be entered in the main text field.

~~~
[eventlocation no="2" name="/TECHNOEVENT" place1="East 27 Street and Campus Road," place2="Brooklyn, NY 11210" date1="Monday, April 1, 2013 at 1:00 PM" date2="Tuesday, April 30, 2013 at 4:00 PM"][/eventlocation]
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Location[span class="hidden-tablet"] Detail[/span]`.
* Set the **Title Variation** to **Title 4**.
* Set the **Box Variation** to **Box 4**.
* Set the **Custom Variations** to `jagged fp-utility-b`.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_4.jpeg