---
title: Omnicron: Recreating the Demo - Clients
description: Your Guide to Recreating Elements of the Omnicron Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

Clients
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Omnicron -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show a featured article on the front page, we placed a `1` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Style: the Central Focus for the Omnicron Template** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><img src="images/stories/demo/frontpage/mb1.jpg" alt="image" class="rt-image" width="660" height="128" /></p>
<p class="nomarginbottom">The theme is <strong>divided</strong> into 4 major style areas: <em>Header, Footer, Body and Body Accent</em>. These denominations control the styling for each area, as selectable from the <strong>Gantry Administrator</strong>. There are <strong>10 style</strong> variations to choose from, by default, which offer a range of color schemes, demonstrating the stylistic versatility of <strong>Omnicron</strong>.</p>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_8.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
