---
title: Dominion: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Dominion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/dominion:Dominion

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Dominion -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]

In order to show a featured article on the front page, we placed a `4` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Other Featured Characteristics** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody. It makes up the first of four articles that appear on the front page of our demo in the section.

Here is the **Article Text** we used:

~~~ .html
<div class="demo-mb">
	<img src="images/stories/demo/frontpage/mb1.jpg" alt="Mar10 Demo Image" class="demo-fp-img img-left"/>
	<p><em class="bold2">Native Right-To-Left (RTL) Support for both Gantry and independent template elements such as module styling.</em></p>
	<p>The Gantry grid system will automatically invert the placement of module positions inside a given row when RTL mode is detected from Joomla. The template is prebuilt with CSS styles and Images that are peculiar to RTL.</p>
	<p><a href="images/stories/demo/general/rtl-preview-full.jpg" class="readon" rel="rokbox[715 1687]" title="Preview of the Demo Frontpage in RTL mode"><span>Preview RTL</span></a></p>
</div>
~~~

Here is the **Article Text** used on the second article, **Other Featured Stuff Continued**.

~~~ .html
<div class="demo-mb">
    <img src="images/stories/demo/frontpage/mb2.jpg" alt="Mar10 Demo Image" class="demo-fp-img img-left"/>
    <p><em class="bold2">Built with the Gantry Framework v2 with the 960 grid system and an intuitive, extensive administrative interface.</em></p>
    <p>Gantry is the framework that rests at the foundation of our latest RocketTheme templates, providing an extensive and powerful core to extend the feature set and functions of our themes exponentially, making them even more flexible.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=47&amp;Itemid=154"]Learn More[/readon2]
</div>
~~~

Here is the **Article Text** used on the second article, **Other Featured Stuff Continued...**.

~~~ .html
<div class="demo-mb">
    <img src="images/stories/demo/frontpage/mb3.jpg" alt="Mar10 Demo Image" class="demo-fp-img img-left"/>
    <p><em class="bold2">Fourteen Module Variations, ranging from color styles to structural variants, allowing for individual module control.</em></p>
    <p>14 module hilites to provide variations, color and/or structural, in your site for your modular content, these are: <strong>bg1-5</strong>, <strong>title1-5</strong>, <strong>flush</strong>, <strong>flushtop</strong>, <strong>flushbottom</strong> &amp; <strong>basic</strong>. All can be previewed by following the internal link below.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=49&amp;Itemid=156"]More Details[/readon2]
</div>
~~~

Here is the **Article Text** for the last article on this front page, **Template Extras**.

~~~ .html 
<h4 class="demo-mb-btm-title"><a href="#">Template Extras</a></h4>
<div class="demo-mb-btm demo-mb-btm-first">
    <p><img src="images/stories/demo/frontpage/cb1.jpg" alt="Mar10 Demo Image" class="demo-fp-img"/></p>
    <p><em class="bold">Over 65 Module Positions.</em></p>
    <p>The template has 68 collapsible positions, allowing for a multitude of many different layout options.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=157"]Read More[/readon2]
</div>
<div class="demo-mb-btm">
    <p><img src="images/stories/demo/frontpage/cb2.jpg" alt="Mar10 Demo Image" class="demo-fp-img"/></p>
    <p><em class="bold">Styled Joomla Extensions.</em></p>
    <p>A series of RocketTheme modules have been styled, perfect for using them with the Dominion theme.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=54&amp;Itemid=161"]Read More[/readon2]
</div>
<div class="demo-mb-btm">
    <p><img src="images/stories/demo/frontpage/cb3.jpg" alt="Mar10 Demo Image" class="demo-fp-img"/></p>
    <p><em class="bold">Adobe Fireworks Sources.</em></p>
    <p>We provide Adobe Fireworks PNG image sources with every template, allowing for quick customization.</p>
    [readon2 url="index.php?option=com_content&amp;view=article&amp;id=60&amp;Itemid=167"]Read More[/readon2]
</div>
<div class="clear"></div>
~~~

Once this articles are created and set to **Featured**, they should appear on the front page.

[demo]: assets/demo_10.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
