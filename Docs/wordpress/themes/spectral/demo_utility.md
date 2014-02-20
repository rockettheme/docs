---
title: Spectral: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Utility Section
-----

![][demo]

:   1. **RokSprocket** [28%, 5%, se]
    2. **RokAjaxSearch** [28%, 50%, se]

Here is the widget breakdown for the Utility section:

* RokSprocket - Headlines
* Gantry Divider 
* RokAjaxSearch

#### RokSprocket - Headlines

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Headlines** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

We also went with the **Simple** content provider in order to create custom items that aren't referenced from a specific post. To create these items, we gave each one a custom link and **Description**. Below is an example of a description used in this instance.

~~~ .html
<span class="h5-title">Dropdown Menu</span><span>CSS based <span class="hidden-desktop">menu</span><span class="visible-desktop"> with advanced <span class="visible-large">layout </span>features</span></span>
~~~

Here is a look at the **Headlines Layout Options** for this widget.

| Option           | Setting |  
| :--------------- | :------ |  
| Theme            | Default |  
| Label Text       |         |  
| Display Limit    | ∞       |  
| Preview Length   | 20      |  
| Strip HTML Tags  | No      |  
| Arrow Navigation | Show    |  
| Animation        | Fade    |  
| Autoplay         | Disable |  
| Autoplay Delay   | 5       |  
| Image Resize     | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Set the **Box Variation** to **Box 4**.
* Enter `fp-roksprocket-headlines` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `fp-rokajaxsearch` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg
[roksprocket]: ../../plugins/roksprocket/