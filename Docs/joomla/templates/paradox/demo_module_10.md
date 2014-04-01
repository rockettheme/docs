---
title: Paradox: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Paradox Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradox:Paradox

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

:   1. **Leading Articles** [42%, 73%, se]
    2. **Article Order** [68%, 73%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**.

Article Properties
-----

The **Paradox - December 2010 Template Demo** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><img src="images/stories/demo/frontpage/fp2.jpg" alt="image" class="rt-image" width="400" height="131" /></p>

<p class="nomarginbottom">The theme has <strong>styling</strong> for the popular, content extension <strong>K2</strong>. K2 is a powerful extensions to expand the default content capabilities of <strong>Joomla</strong> exponentially, allowing for <strong>advanced</strong>, individual article <strong>layouts</strong>.</p>

<div class="alert"><div class="typo-icon">Note: K2 is not included in the RocketLauncher, and therefore, the launcher has been modified to account for this change, with different content items and module assignments.</div></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_12.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
