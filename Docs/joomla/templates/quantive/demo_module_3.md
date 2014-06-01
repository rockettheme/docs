---
title: Quantive: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Quantive Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/quantive:Quantive

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Quantive -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show a featured article on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **More to Explore** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p>Listed below are some of the core features of the <strong>Quantive</strong> template:</p>
<div class="demo-fp-main">
	<div class="demo-fp-main1">
	<img src="images/blank.png" class="png floatleft" alt="Frontpage Image" />
	<em class="bold">Full Template / Gantry RTL Support</em><br />
	Native Right-To-Left (RTL) Support for both Gantry and independent template elements such as module styling.<br />
	<a href="images/stories/demo/general/rtl-preview-full.jpg" class="readon" rel="rokbox[715 1261]" title="RTL Preview :: Preview of the Demo Frontpage in RTL mode"><span>Preview RTL</span></a>
	<div class="module-title">&nbsp;</div></div>

	<div class="demo-fp-main2">
	<img src="images/blank.png" class="png floatleft" alt="Frontpage Image" />
	<em class="bold">Individual Module Styling</em><br />
	Thirteen Module Variations, ranging from shaded styles to structural variants, allowing for individual module control.<br />
	[readon2 url="index.php?option=com_content&amp;view=article&amp;id=49&amp;Itemid=156"]Learn More[/readon2]
	<div class="module-title">&nbsp;</div></div>

	<div class="demo-fp-main3">
	<img src="images/blank.png" class="png floatleft" alt="Frontpage Image" />
	<em class="bold">Numerous Layout Configurations</em><br />
	The template has 68 collapsible positions, allowing for a multitude of many different layout options.<br />
	[readon2 url="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=157"]Learn More[/readon2]
	<div class="module-title">&nbsp;</div></div>

	<div class="demo-fp-main4">
	<img src="images/blank.png" class="png floatleft" alt="Frontpage Image" />
	<em class="bold">Styled RocketTheme Extensions</em><br />
	A series of RocketTheme modules have been styled, perfect for using them with the Quantive theme.<br />
	[readon2 url="index.php?option=com_content&amp;view=article&amp;id=54&amp;Itemid=161"]Learn More[/readon2]
	<div class="module-title">&nbsp;</div></div>

	<div class="demo-fp-main5">
	<img src="images/blank.png" class="png floatleft" alt="Frontpage Image" />
	<em class="bold">PNG Image Sources</em><br />
	We provide Adobe&reg; Fireworks PNG image sources with every template, allowing for quick customization.<br />
	[readon2 url="index.php?option=com_content&amp;view=article&amp;id=60&amp;Itemid=167"]Learn More[/readon2]
	<div class="module-title">&nbsp;</div></div>

	[readon2 url="index.php?option=com_content&amp;view=article&amp;id=46&amp;Itemid=153"]View More Features[/readon2]
</div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_3.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
