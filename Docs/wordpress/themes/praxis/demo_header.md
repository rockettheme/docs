---
title: Praxis: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Header Section
-----

![][demo]

:	1. **Gantry Logo** [30%, 5%, se]
	2. **RokSprocket** [30%, 22%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* RokSprocket

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Headlines** widget.

In this particular instance, we went with the **Simple** **Content Provider** in order to add custom information into the widget not directly tied to any posts or pages. You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

Here is a look at the **Headlines Layout Options** for this widget.

| Option           | Setting |  
| :--------------- | :------ |  
| Theme            | Default |  
| Label Text       |         |  
| Display Limit    | ∞       |  
| Preview Length   | 20      |  
| Arrow Navigation | Show    |  
| Animation        | Fade    |  
| Autoplay         | Disable |  
| Autoplay Delay   | 5       |  
| Image Resize     | Disable |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

**Simple Item Setup**

We did not do a whole lot to create the simple items in this widget. The only attribute we added was each item's description. Here is a sample of the description for the first simple item.

~~~ .html
An intricate mix of CSS animations and 3D visual effects.
~~~

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Enter `fp-roksprocket-headlines` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_2.jpeg
[faq]: faq.md