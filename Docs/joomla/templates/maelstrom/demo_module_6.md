---
title: Maelstrom: Recreating the Demo - Portfolio Series
description: Your Guide to Recreating Elements of the Maelstrom Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/maelstrom:Maelstrom

---

Portfolio Series
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Afterburner2 -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Portfolio Series** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<img src="images/stories/demo/frontpage/main1.jpg" alt="image" width="140" height="98" class="rt-image floatleft"/>

<span class="rt-author">Individually <a href="index.php?option=com_content&view=article&id=2&Itemid=107"><em class="normal nobold">style</em></a> your modular content.</span>

<p class="smallmarginbottom"><em class="bold">Over 250 possible Module style combinations.</em></p>

<p class="smallmarginbottom">Combine the 31 style suffixes together to create diverse module styling, style the titles, module backgrounds and read more.</p>

<span class="rt-author">Highlights: <a href="index.php?option=com_content&view=article&id=2&Itemid=107"><em class="normal nobold">Icons</em></a>, <a href="index.php?option=com_content&view=article&id=2&Itemid=107"><em class="normal nobold">Combos</em></a>, <a href="index.php?option=com_content&view=article&id=2&Itemid=107"><em class="normal nobold">Layout Suffixes</em></a></span>

<a class="readon floatright" href="index.php?option=com_content&view=article&id=2&Itemid=107"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="images/stories/demo/frontpage/main2.jpg" alt="image" width="140" height="98" class="rt-image floatleft"/>

<span class="rt-author">Powered by the <a href="index.php?option=com_content&view=article&id=8&Itemid=140"><em class="normal nobold">RokNavMenu</em></a> module.</span>

<p class="smallmarginbottom"><em class="bold">Featuring Fusion with MegaMenu abilities.</em></p>

<p class="smallmarginbottom">Fusion is a Mootools enhanced CSS dropdown menu system, that is fully crawlable by search engines, and packed with advanced features.</p>

<span class="rt-author">Highlights: <a href="index.php?option=com_content&view=article&id=8&Itemid=140"><em class="normal nobold">Multi-Columns</em></a>, <a href="index.php?option=com_content&view=article&id=8&Itemid=140"><em class="normal nobold">Inline Modules</em></a>, <a href="index.php?option=com_content&view=article&id=8&Itemid=140"><em class="normal nobold">Menu Icons</em></a></span>

<a class="readon floatright" href="index.php?option=com_content&view=article&id=8&Itemid=140"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="images/stories/demo/frontpage/main3.jpg" alt="image" width="140" height="98" class="rt-image floatleft"/>

<span class="rt-author">Condense <a href="index.php?option=com_content&amp;view=article&amp;id=48&amp;Itemid=55"><em class="normal nobold">positions</em></a> for more window real estate.</span>

<p class="smallmarginbottom"><em class="bold">Scrollable module positions and rows.</em></p>

<p class="smallmarginbottom">Stacked modules published to the configured Module rows will load this feature; this places stacked modules inside a rotation element.</p>

<span class="rt-author">Highlights: <a href="index.php?option=com_content&view=article&id=3&Itemid=126"><em class="normal nobold">Smooth</em></a>, <a href="index.php?option=com_content&view=article&id=3&Itemid=126"><em class="normal nobold">Configurable</em></a>, <a href="index.php?option=com_content&view=article&id=3&Itemid=126"><em class="normal nobold">Automated</em></a></span>

<a class="readon floatright" href="index.php?option=com_content&view=article&id=3&Itemid=126"><span>Read More...</span></a>

<div class="clear"></div>

<div class="title8 medmargintop medmarginbottom"><div class="title-highlight"><div class="title-highlight2"></div></div></div>

<img src="images/stories/demo/frontpage/main4.jpg" alt="image" width="140" height="98" class="rt-image floatleft"/>

<span class="rt-author">Versatile content <a href="index.php?option=com_content&view=article&id=5&Itemid=127"><em class="normal nobold">rotator</em></a> extension.</span>

<p class="smallmarginbottom"><em class="bold">A new RokStories layout mode.</em></p>

<p class="smallmarginbottom">The new Scroller Showcase layout, showcasing large images in an intuitive and elegant manner, perfect for any portfolio site.</p>

<span class="rt-author">Highlights: <a href="index.php?option=com_content&view=article&id=5&Itemid=127"><em class="normal nobold">Multiple Layouts</em></a>, <a href="index.php?option=com_content&view=article&id=5&Itemid=127"><em class="normal nobold">Advanced Controls</em></a></span>

<a class="readon floatright" href="index.php?option=com_content&view=article&id=5&Itemid=127"><span>Read More...</span></a>

<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_6.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
