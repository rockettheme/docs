---
title: Spectral: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Spectral Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/spectral:Spectral

---

Main Top Section
-----

![][demo]

Here is the widget breakdown for the Main Top section:

* RokSprocket - Strips

#### RokSprocket

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Strips** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Title**, **Image**, **Link**, and **Description** is customized for our needs. The images are simple image files hosted on the local server and linked in the **Image** field. The **Link** field has a URL in place we want the particular item to lead to. You will find the other settings used in one of these items below.

**Title**

~~~ .html
HTML5 Charts
~~~

**Description**

~~~ .html
<span>Display graphs with Chart.js and HTML5 canvas. This feature only works on modern browsers and IE9+.</span><span class="visible-desktop largemargintop">It's based on Chart.js. Chart.js is an easy, object oriented client side graphs for designers and developers.</span>
~~~

Here is a look at the **Strips Layout Options** for this widget.

| Option            | Setting      |  
| :---------------- | :----------- |  
| Display Limit     | ∞            |  
| Theme             | Default      |  
| Preview Length    | 50           |  
| Strip HTML Tags   | No           |  
| Previews Per Page | 4            |  
| Items Per Row     | 4            |  
| Arrow Navigation  | Show         |  
| Pagination        | Hide         |  
| Animation         | Fade Delayed |  
| Autoplay          | Disable      |  
| Autoplay Delay    | 5            |  
| Image Resize      | Disable      |  

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Strips widget in the **Choose Widget** field.
* Enter `fp-roksprocket-strips` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/