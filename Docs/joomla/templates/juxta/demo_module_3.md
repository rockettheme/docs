---
title: Juxta: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Juxta Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/juxta:Juxta

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Juxta -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show a featured article on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Welcome to Juxta** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<div class="floatleft png" style="background: url(images/stories/demo/frontpage/sample-tall.png);padding: 5px;"><img alt="image" src="images/stories/demo/frontpage/fp-mb1.jpg" /></div>

<p><strong>Juxta, the May 2010 Template Club release</strong>, is a design-centric theme, focusing on <em>unique</em>, <em>professional</em> and <em>fresh</em> visuals to constitute the fundamental appearance of the template. Style is very important with any theme, and Juxta intends to <strong>entice</strong> any visitor of your site.</p>

<p>The theme has a plethora of features beyond its stylistic exterior. The core is composed of the <strong>Gantry Framework</strong>, offering a mature and feature rich foundation for many advanced, flexible and <em>versatile</em> functions to make the template extremely usable, <em>modern</em> and engaging.</p>

[readon url="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108"]View More Features[/readon]
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_3.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
