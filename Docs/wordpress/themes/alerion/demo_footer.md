---
title: Alerion: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Alerion Theme for WordPress
breadcrumb: /wordpress:WordPress/themes:Themes/alerion:Alerion

---

Footer Section
-----
![][demo]

:   1. **Text** [13%, 8%, se]
    2. **RokSprocket** [13%, 40%, se]

Here's the widget breakdown for the Footer section:

* Text
* RokSprocket

### Text

You'll need to enter the following in the main text field to create this text widget as it appears in our demo.

~~~
<span class="rt-footer-logo"></span>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Enter `fp-footer-logo visible-desktop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

### RokSprocket

You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Tabs Layout Options** for this widget.

| Option          |        Setting |  
| :-------------- | -------------: |  
| Theme           |        Default |  
| Tabs Position   |            Top |  
| Display Limit   |              ∞ |  
| Animation       | Slide and Fade |  
| Autoplay        |        Disable |  
| Autoplay Delay  |              5 |  
| Image Resize    |        Disable |  
| Preview Length  |              0 |  
| Strip HTML Tags |             No |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `fp-footer` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_10.jpeg