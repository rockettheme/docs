---
title: Fracture: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Fracture Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/fracture:Fracture

---

Utility Section
-----
![][demo4]

Here's the widget breakdown for the Utility section:

* Text
* RokSprocket

### Text
The Text widget in the section has an empty text field. All of the magic happens in the title field, which contains multiple title tags.

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `[title1]Popular Features.[/title1][title2]RokSprocket and RokGallery[/title2]`.
* Set the **Widget Style** to **Flush**.
* Set the **Title Variation** to **Title 1**.
* Set the **Margin Variation** to **No Margin Bottom**.
* Set the **Padding Variation** to **No Padding Buttom**.
* Set the **Custom Variations** to `icon-star no-margin-top no-padding-top`.
* Leaving everything else at its default setting, select **Save**.

### RokSprocket
The lower widget is a Mosiac widget used to display the various features featured in the Fracture theme.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Mosaic Layout Options** for this widget.

| Option          |                      Setting |  
| :-------------- | ---------------------------: |  
| Theme           |                      Default |  
| Display Limit   |                            ∞ |  
| Columns         |                            4 |  
| Preview Length  |                           20 |  
| Strip HTML Tags |                          Yes |  
| Blocks Per View |                            4 |  
| Article Details |         Hide author and date |  
| Block Animation |          Fade, Scale, Rotate |  
| Ordering        | Default, Title, Date, Random |  
| Image Resize    |                      Disable |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Set the **Title** to `Gantry Extras`
* Select your RokSprocket Mosaic widget in the **Choose Widget** field.
* Set the Title Variation field to **Title 1**.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo4]: assets/wp_fracture_demo_4.jpeg
[roksprocket]: ../../plugins/roksprocket