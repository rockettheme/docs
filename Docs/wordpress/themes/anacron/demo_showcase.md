---
title: Anacron: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Anacron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/anacron:Anacron

---

Showcase Section
-----

![][demo]

Here is the widget breakdown for the Showcase section:

#### RokSprocket

The main feature showcase located near the top of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

In this instance, we used the **Simple** content provider in order to allow us to create custom items, without having to create posts to connect them to. The **Title** and **Description** fields of these items are custom.

**Title**

~~~ .html
Maximize Site Utility,<br />with the Dynamic Header
~~~

**Description**

~~~ .html
<span class="rt-button-group"><a href="http://ryanmpierson.no-ip.biz/wordpress/anacron_demo/features/" class="readon">Read More</a><a href="http://ryanmpierson.no-ip.biz/wordpress/anacron_demo/features/" class="readon2">Download</a></span>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting        |  
| :--------------- | :------------- |  
| Display Limit    | ∞              |  
| Theme            | Showcase       |  
| Article Titles   | Show           |  
| Article Text     | Show           |  
| Preview Length   | ∞              |  
| Strip HTML Tags  | No             |  
| Arrow Navigation | Show           |  
| Pagination       | Show           |  
| Animation        | Bottom to Top  |  
| Autoplay         | Disable        |  
| Autoplay Delay   | 5              |  
| Image Resize     | Disable        |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Features widget in the **Choose Widget** field.
* Enter `fp-roksprocket-showcase` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_2.jpeg
[roksprocket]: ../../plugins/roksprocket/
