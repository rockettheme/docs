---
title: Panacea: Recreating the Demo - Featured Articles
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

Featured Articles
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Panacea -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [43%, 71%, se]
    2. **Article Order** [67%, 71%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**.

Article Properties
-----

The **Panacea July Template Release** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody along with other articles assigned the same way.

Here is the **Article Text** we used:

~~~ .html
<p class="dropcap"><span class="dropcap">P</span>anacea, the <strong>July 2010</strong> Template Club release, encapsulates stylistc <strong>freedom</strong> with the inclusion of the <strong>Color Chooser</strong>, allowing for easy style customization with just a few clicks. An unconventional feature for such a design choice.</p>

<div class="demo-grid-4">
    <span class="heading1">Feature Rich Foundation</span>
    <p><strong>Panacea</strong> is built with the <strong>Gantry Framework</strong>, offering a powerful base for the template with such notable features as the <strong>960 Grid System</strong>, amongst others.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107"]Learn more[/readon2]
</div>
<div class="demo-grid-2">
    <span class="heading1">Key Features</span>
    <ul class="bullet-star">
        <li>Color Chooser</li>
        <li>Background Rotator</li>
        <li>Ajax Article Loading</li>
        <li>Smartloading</li>
    </ul>
</div>

<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_3.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
