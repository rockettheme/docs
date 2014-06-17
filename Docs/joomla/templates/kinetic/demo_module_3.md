---
title: Kinetic: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Kinetic Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kinetic:Kinetic

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Kinetic -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]

In order to show a featured article on the front page, we placed a `2` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Kinetic February 2010** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody. It makes up the first of four articles that appear on the front page of our demo in the section.

Here is the **Article Text** we used:

~~~ .html
<p><strong>Kinetic</strong> is the February 2010 Joomla Template release, sporting a rich, versatile and selective conservative design, founded on the powerful and flexible Gantry Framework v2.0.</p>
<div class="demo-mb">
    <img src="images/stories/demo/frontpage/mb0.jpg" alt="Main Content 0" class="mb-image" />
    <span class="demo-title">Eight Preset Styles</span>
    <p>An array of stunning, unique and professionally designed style variations, in 3 detail levels: High, Med and Low.<br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=48&amp;Itemid=174">Read More</a></p>
</div>
<div class="demo-mb">
    <img src="images/stories/demo/frontpage/mb1.jpg" alt="Main Content 1" class="mb-image" />
    <span class="demo-title">Triple Level Splitmenu</span>
    <p>Splitmenu displays its 2nd level items horizontally, in the navigation position, and the rest in the sidebar.<br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=59&amp;Itemid=166">Read More</a></p>
</div>
<div class="demo-mb">
    <img src="images/stories/demo/frontpage/mb2.jpg" alt="Main Content 2" class="mb-image" />
    <span class="demo-title">Module Variations</span>
    <p>Choose from 8 Ribbon and 8 Box styles to diversify and enhance your modular content beyond simple default styling.<br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=49&amp;Itemid=156">Read More</a></p>
</div>
[readon2 url="index.php?option=com_content&amp;view=article&amp;id=46&amp;Itemid=153"]Learn More[/readon2]
~~~

Here is the **Article Text** used on the second article, **Powered by Gantry**.

~~~ .html
<span class="demo-title">Version 2.0</span>
<p><a href="#"><em class="bold">A powerful, feature rich framework used for assembling, building and maintaining a RocketTheme template</em></a></p>
<p>Gantry 2.0 has a plethora of powerful features, such as the 960 grid system, RTL support, and an extensive administrative interface. <a href="index.php?option=com_content&amp;view=article&amp;id=47&amp;Itemid=154">Read More</a></p>
<div class="quote" style="margin-bottom: 0;"><div class="quote-l"><div class="quote-r">We're pleased to say that our new Gantry Framework checks all the boxes and we feel it is a real game-changer when it comes to developing templates for platforms such as Joomla.</div><span class="demo-author">Andy Miller - RocketTheme</span></div></div>
~~~

Once this articles are created and set to **Featured**, they should appear on the front page.

[demo]: assets/demo_3.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
