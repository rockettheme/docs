---
title: Hexeris: Adding Widget Instances
description: Your Guide to Using the Hexeris Theme for Magento
tags: [Hexeris, widget, instances, how-to, guide]
breadcrumb: /magento:Magento/!themes:Themes/hexeris:Hexeris

---

Introduction
-----

There are two CMS blocks used in Hexeris, both of which are added via **Widget Instances**. 

![][demo_1]

:   1. **Home Page Block** [67%, 10%, se]
    2. **Social Links Block** [49%, 91%, se]

The first is the long bar with the text reading: `A multi-faceted content display module...` and a **Read More** button, as seen on the demo homepage. 

The second is the floating social links box, visible on all pages on the demo. 

### Home Page Block

The first step to making a new CMS static block is to navigate to **CMS -> Static Blocks** and click the **Add New Block** button.

For the Home Page block, use the following settings:

![][widget_1]

| Option      | Setting                  |  
| :---------- | :----------------------- |  
| Block Title | `Hexeris Homepage Block` |  
| Identifier  | `hexeris_homepage_block` |  
| Store View  | Style 1                  |  
| Status      | Enabled                  |  


To replicate the block as it appears in our demo, enter the following as the Content (disabling the WYSIWYG editor before pasting):

~~~ .html
<div class="homepage-block hidden-phone">
    <p>A multi-faceted content display module...</p><button class="button"
    onclick="setLocation('http://rockettheme.com')"><span>Read More</span></button>
</div>
~~~

>> NOTE: The `setLocation('http://rockettheme.com')` area of the code sets the link visitors will go to when they click the button. Replace the URL with a link of your choice.

Once this is done, select **Save**.

Next, you need to create a widget instance to add the block to the frontend. 

To do this, go to **CMS -> Widgets** and click the **Add New Widget Instance** button.

Set the **Type** to **CMS Static Block**, select the **hexeris / default** package, and add the following settings:

![][widget_3]

| Option                | Setting                           |  
| :-------------------- | :-------------------------------- |  
| Widget Instance Title | `Hexeris Homepage Block`          |  
| Assign to Store Views | All Store Views                   |  
| Sort Order            | 0                                 |  
| Display On            | Specified Page                    |  
| Page                  | CMS Home Page                     |  
| Block Reference       | After Homepage ContentSlider      |  
| Template              | CMS Static Block Default Template |  

Then, choose your CMS block `Hexeris Homepage Block` under the **Widget Options** tab, and save.

### Social Links Block

As with the previous block, you will need to navigate to **CMS -> Static Blocks** and click the **Add New Block** button to initiate the creation of the CMS static block.

For the Social Links Box, we used the following settings:

![][widget_2]

| Option      | Setting                  |  
| :---------- | :----------------------- |  
| Block Title | `Hexeris Social Links`   |  
| Identifier  | `hexeris_social_links`   |  
| Store View  | Style 1                  |  
| Status      | Enabled                  |  

To replicate the block as it appears in our demo, enter the following as the Content (disabling the WYSIWYG editor before pasting):

~~~ .html
<div class="rt-social-buttons">
    <span class="social-button icon-random">&nbsp;</span> <span class=
    "rt-social-text">Follow</span> <a class="social-button rt-facebook-btn"
    href="http://www.facebook.com/RocketTheme"><span class=
    "icon-facebook">&nbsp;</span></a> <a class="social-button rt-twitter-btn"
    href="https://twitter.com/rockettheme"><span class=
    "icon-twitter">&nbsp;</span></a> <a class="social-button rt-google-btn"
    href="https://plus.google.com/114430407008695950828/posts"><span class=
    "icon-google-plus">&nbsp;</span></a> <a class="social-button rt-rss-btn"
    href=
    "http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span class="icon-rss">
    &nbsp;</span></a>
    <div class="clear">
        &nbsp;
    </div>
</div>
~~~

Once this is done, select **Save**.

Next, you need to create a widget instance to add the block to the frontend. 

To do this, go to **CMS -> Widgets** and click the **Add New Widget Instance** button.

Set the **Type** to **CMS Static Block**, select the **hexeris / default** package, and add the following settings:

![][widget_4]

| Option                | Setting                           |  
| :-------------------- | :-------------------------------- |  
| Widget Instance Title | `Hexeris Social Links`            |  
| Assign to Store Views | All Store Views                   |  
| Sort Order            | 0                                 |  
| Display On            | All Pages                         |  
| Block Reference       | Before Header                     |  
| Template              | CMS Static Block Default Template |  

Then, choose your CMS block `Hexeris Social Links` under the **Widget Options** tab, and save.

The blocks should now appear on your frontend (remember to flush your Magento cache first).

[widget_1]: assets/widget_1.jpeg
[widget_2]: assets/widget_2.jpeg
[widget_3]: assets/widget_3.jpeg
[widget_4]: assets/widget_4.jpeg
[demo_1]: assets/demo_1.jpg
