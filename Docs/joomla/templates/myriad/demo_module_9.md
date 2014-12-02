---
title: Myriad: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

MainBody
-----

![][demo]

This area of the front page is an article. Articles appear within the **MainBody** area of the front page.

Turning on MainBody Content
-----

This content appears on the front page because the **Display MainBody** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Myriad -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [32%, 25%, se]

In order to show one featured article on the front page, we placed a `1` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Blast Off with RocketLauncher!** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p>We have Myriad RocketLauncher packages which are provided as an additional option with the purchase of the template or membership.</p>

<p>RocketLauncher will install both Joomla! and all of the sample content seen here on our Myriad demo site.</p>

<p>This provides you with a way to get started quicker with Myriad, as our demos feature a lot of custom content examples and configuration that can help to give you ideas for using the template to its maximum effectiveness.
</p>

<a class="readon3" href="http://www.rockettheme.com/docs/joomla/platform/rocketlauncher_3x.md">Read the Whole Story</a>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_10.jpeg
[menu]: assets/demo_9a.jpeg
[advanced]: assets/setadvanced.jpeg
