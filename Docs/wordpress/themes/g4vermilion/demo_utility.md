---
title: Vermilion: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Vermilion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/vermilion:Vermilion

---

Utility Section
-----

![][demo]

:   1. **Text** [30%, 6%, se]
    2. **Gantry Social Buttons** [30%, 70%, se]

Here is the widget breakdown for the Utility section:

* Text
* Gantry Divider
* Gantry Social Buttons

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<h2 class="title"><a href="#">Animate &amp; Innovate</a></h2>
<p><span>Vermilion is bursting with animation extras to add <span class="hidden-tablet">character and </span>depth<span class="visible-large"> to your site</span></span>.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `fp-utility rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Social Buttons

The Gantry Social Buttons widget creates a set of social buttons on the top of the page. Filling this out is fairly straightforward. Once you have clicked and dragged the **Gantry Social Buttons** widget in place, you will want to add your various social URLs to their respective fields. Once this is done, simply hit **Save** and check the site. 

Here is a Breakdown of the settings used in this widget:

| Field       | Setting                                        |
| :---------- | :----------                                    |
| Icon 1      | fa fa-facebook                                 |
| Text 1      | Facebook                                       |
| Link 1      | https://www.facebook.com/RocketTheme           |
| Icon 2      | fa fa-twitter                                  |
| Text 2      | Twitter                                        |
| Link 2      | https://twitter.com/rockettheme                |
| Icon 3      | fa fa-google-plus                              |
| Text 3      | Google +                                       |
| Link 3      | https://plus.google.com/+rockettheme           |
| Icon 4      | fa fa-rss                                      |
| Text 4      | RSS                                            |
| Link 4      | http://www.rockettheme.com/product-updates?rss |

[demo]: assets/demo_2.jpeg
