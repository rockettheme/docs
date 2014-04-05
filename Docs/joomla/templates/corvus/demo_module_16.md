---
title: Corvus: Recreating the Demo - Featured Articles
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Featured Articles
----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Reflex -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [46%, 72%, se]

In order to show three featured articles on the front page, we placed a `3` in the **Intro Articles** setting within the **Layout Options** menu. 

Article Properties
-----

The **RokSprocket Strips** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<div class="gantry-width-30 gantry-width-block">
    <img class="rt-image-a" src="images/rocketlauncher/frontpage/featured/img2.jpg" alt="image">
</div>

<div class="gantry-width-60 gantry-width-block">
    <div class="largemarginleft">
        <p>Strips is a layout mode for RokSprocket <span class="hidden-tablet">that displays<span class="visible-large"> and rotates through</span> horizontal content <span class="visible-large">and image</span> blocks<span class="visible-large">, perfect for highlighting content</span></span>.</p>
    </div>
</div>

<div class="clear"></div>

<span class="rt-tags">
    <span class="rt-tag">Games</span>
    <span class="rt-tag">Action</span>
</span>

<a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113" class="readon2 rt-floatright">+</a>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_14.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg