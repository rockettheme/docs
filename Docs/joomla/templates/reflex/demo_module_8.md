---
title: Reflex: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Reflex Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reflex:Reflex

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Reflex -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**.

Article Properties
-----

The **RokSprocket Layouts** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><b>Reflex</b> is an elegant, professional and highly flexible template. It is the first to debut <b>RokGallery</b>, an advanced new <b>multiple tagging gallery</b> solution for Joomla, with integrated styling and accompanying documentation, instructing you on using its simple, but <b>powerful feature</b> set.</p>

<div class="rt-demo-grid-4 nomarginleft">
    <ul class="checkmark normalfont nomarginbottom">
        <li><b>Gantry Framework:</b> The template's core, providing extensive and scalable features such as the 960 Grid System.</li>
        <li><b>Preset Styles:</b> A selection of six style variations, as configurable int the user friendly template manager interface.</li>
    </ul>
</div>
<div class="rt-demo-grid-4 rt-demo-grid-4 nomarginleft nomarginright">
    <ul class="checkmark normalfont nomarginbottom">
        <li><b>Fusion Menu:</b> A javascript enhanced CSS dropdown menu, with multi-column support, plus much more.</li>
        <li><b>Extensions:</b> Reflex has styled support for RokTabs, RokTwittie, RokGallery, RokNewsPager and RokAjaxSearch.</li>
    </ul>
</div>
<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_12.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg