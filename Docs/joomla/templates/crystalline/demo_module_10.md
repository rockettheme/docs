---
title: Crystalline: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Crystalline Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/crystalline:Crystalline

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Crystalline -> Advanced**.

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

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_10.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
