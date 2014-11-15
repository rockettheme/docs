---
title: Chimera: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Chimera Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chimera:Chimera

---

Extension Section
-----

![Extension](assets/demo_8.jpeg)

:   1. **RokSprocket (Tables)** [13%, 5%, se]
    2. **Text 2** [13%, 59%, se]

Here is the widget breakdown for the Extension section:

* RokSprocket (Tables)
* Gantry Divider
* Text

#### RokSprocket (Tables)

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tables** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

### Simple Item Example

| Option      | Setting                           |  
| :---------- | :-------------------------------- |  
| Title       | `Free`                            |  
| Description | None                              |  
| Image       | None                              |  
| Feature 1   | `<strong>Limited</strong> Access` |  
| Feature 2   | `X`                               |  
| Feature 3   | `X`                               |  
| Feature 4   | `X`                               |  
| Link        | `#`                               |  
| Link Text   | `Sign Up`                         |  

#### Price

~~~ .html
<span class="sprocket-tables-price-amount">$0<span class="hidden-tablet hidden-large hidden-phone">&nbsp;&nbsp;</span></span><span class="sprocket-tables-price-period">/mon</span>
~~~

Here is a look at the **Tables Layout Options** for this widget.

| Option            | Setting     |
| :----------       | :---------- |
| Theme             | Product     |
| Display Limit     | `∞`         |
| Preview Length    | `∞`         |
| Strip HTML Tags   | No          |
| Previews Per Page | `3`         |
| Items Per Row     | `3`         |
| Arrow Navigation  | Show        |
| Pagination        | Show        |
| Animation         | Randomize   |
| Autoplay          | Disable     |
| Autoplay Delay    | 5           |
| Image Resize      | Disable     |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tables widget in the **Choose Widget** field.
* Enter `fp-roksprocket-tables wow fadeInLeftBig` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h3 class="wow pulse"><strong>Looking for the perfect plan?</strong> Learn more about our various options and what works for you.</h3>

<p class="wow pulse">We offer a wide range of products and membership plans, custom tailored to your needs. Browse our selection of products to find the perfect one for your project, or select a membership to gain access to everything.</p>

<br />

<div class="rt-white-box wow bounceInUp">
    <span class="rt-icon-left rt-hero-icon hidden-tablet">
        <i class="fa fa-puzzle-piece"></i>
    </span>
    <h3><strong><span class="hidden-tablet">Link up multiple memberships</span><span class="visible-tablet">Multiple packages</span></strong></h3>
    <p>Buy multiple packages to gain access to different product types and extras, with unlimited options.</p>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-extension-b` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
