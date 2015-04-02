---
title: Cygnet: Recreating the Demo - Content
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

Content
-----

![](assets/demo_14.jpg)

This area of the front page is the MainBody. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Cygnet -> Advanced**.

![](assets/setadvanced.jpeg)

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![](assets/demo_15a.jpeg)

In order to show three featured articles on the front page, we placed a `3` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**.

Article Properties
-----

The **The RocketLauncher installs a demo equivalent onto your site** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p>A default Joomla package with custom sample data, images, extensions and the template from the demo. The content images are replaced with sample tiled substitutes due to avoid potential copyright issues.</p>
<a class="readon2" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Read More</a>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.