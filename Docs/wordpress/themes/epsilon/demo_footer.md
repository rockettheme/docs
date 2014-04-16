---
title: Epsilon: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Epsilon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/epsilon:Epsilon

---

Footer Section
-----

![][demo]

:   1. **Text** [20%, 5%, se]
    2. **Text** [20%, 35%, se]
    3. **RokSprocket** [20%, 67%, se]

Here is the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* RokSprocket

#### Text 1

You will need to enter the following in the main text field.

~~~ .html
<p class="rt-small-text">Sign up to receive information about updates, upcoming themes, and great deals!</p>
<form onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify" class="fp-newsletter-form">
    <input type="text" name="email" class="inputbox" placeholder="your@email.com" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="button" name="Submit" />
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Join Our Newsletter` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

You will need to enter the following in the main text field.

~~~ .html
<p class="rt-small-text">We are always open for a quick chat! Give us a call or email us any time and we will respond shortly.</p>
<p>
    <span><span class="icon-phone"></span>&nbsp;&nbsp;(123)456-789</span><br />
    <span><span class="icon-envelope"></span>&nbsp;&nbsp;noreply@epsilon-theme.com</span>
</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Contact Us` in the **Title** field.
* Leaving everything else at its default setting, select **Save**.

#### RokSprocket

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Tabs** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

**Simple Content Provider**

We used the **Simple** Content Provider to allow us to make custom tabs without having to build posts on the back-end. In this case, the **Tab Label** and **Description** are custom, while the other options are left at default or **None** settings. You will find the settings used in one of these items below.

*Tab Label*

~~~ .html
Info
~~~

*Description*

~~~ .html
<ul>
    <li><a href=
    "http://(your site URL)/about-us/">About
    <span class="hidden-tablet">Us</span></a></li>
    <li><a href=
    "http://(your site URL)/team/">Team</a></li>
    <li><a href=
    "http://(your site URL)/services/">Services</a></li>
</ul>
~~~

Here is a look at the **Tabs Layout Options** for this widget.

| Option          | Setting        |
| :-------------- | :------------  |
| Theme           | Default        |
| Display Limit   | ∞              |
| Tabs Position   | Left           |
| Animation       | Slide and Fade |
| Autoplay        | Disable        |
| Autoplay Delay  | 5              |
| Image Resize    | Disable        |
| Preview Length  | 0              |
| Strip HTML Tags | No             |

You can set the RokSprocket filters to include any category, specific articles, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Select your RokSprocket Tabs widget in the **Choose Widget** field.
* Enter `Links` in the **Title** field.
* Enter `fp-footer-tabs` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_9.jpeg
[roksprocket]: ../../plugins/roksprocket/
