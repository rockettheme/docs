---
title: Chapelco: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Chapelco Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/chapelco:Chapelco

---

Utility Section
-----

Here's the widget breakdown for the Utility section:

* Text
* RokSprocket

### Text

![][demo]

The Text widget in the section requires RokCandy to display the title properly. The `[span]` tags are used to add the `hidden-phone` CSS override to the title so the word `Popular` is hidden on smaller screens.

The following should be entered in the main text field.

~~~
<div class="rt-center">
<p>RokSprocket is a powerful and multi-faceted content display plugin, that combines many different layout modes; with a custom built user interface. The UI has AJAX support, for easy and efficient control, such as dynamic filters.</p>
</div>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `[span class=\"hidden-phone\"]Popular [/span]Features`.
* Set the **Title Variation** to **Title 5**.
* Set the **Margin Variation** to **No Margin Bottom**.
* Set the **Padding Variation** to **No Padding Buttom**.
* Set the **Custom Variations** to `icon-star featuretitle`.
* Leaving everything else at its default setting, select **Save**.

### RokSprocket

![][demo2]

The lower widget is a Mosiac widget used to display the various features featured in the Chapelco theme.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Mosaic Layout Options** for this widget.

| Option          |                      Setting |  
| :-------------- | ---------------------------: |  
| Theme           |                      Default |  
| Display Limit   |                            ∞ |  
| Columns         |                            3 |  
| Preview Length  |                           14 |  
| Strip HTML Tags |                          Yes |  
| Blocks Per View |                            3 |  
| Article Details |         Hide author and date |  
| Block Animation |          Fade, Scale, Rotate |  
| Ordering        | Default, Title, Date, Random |  
| Image Resize    |                      Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Set the **Corner Variation** to **Basic**.
* Enter `fp-mosaic` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_4.jpeg