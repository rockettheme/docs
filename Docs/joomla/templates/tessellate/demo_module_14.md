---
title: Tessellate: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Osmosis -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

In order to show a featured article on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. As there is only one featured article, only one appears on the front page.

Article Properties
-----

The **Featured Article** is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

>> NOTE: Any articles are best handled using either RokPad or no editor as other editors (especially WYSIWYG) can cause unwanted code stripping.

Here is the **Article Text** we used:

~~~ .html
<div class="rt-center">
    <h3 class="fp-article-feature">"Tessellate is a sharp, elegant and refined template. It is designed to not only enrich your content, but also to provide an overall artistic base, with animated extras, to impress your visitors, and best reflect the focus of your site." - <a href="index.php?option=com_content&view=article&amp;id=1&amp;Itemid=111">Read More</a></h3>
</div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_14.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
