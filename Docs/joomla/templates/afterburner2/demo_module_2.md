---
title: Afterburner2: Recreating the Demo - Popular Features
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Popular Features
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Afterburner2 -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:	1. **Leading Articles** [42%, 72%, se]
	2. **Article Order** [68%, 72%, se]

In order to show two featured articles on the front page, we placed a `2` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Popular Features** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<div class="rt-relative largemarginbottom largepaddingtop largepaddingbottom largepaddingright rt-border-right rt-border-bottom">
	<div class="rt-big-icon rt-blue icon-cogs"></div>
	<h5 class="smallmarginbottom nomargintop">Framework</h5>
	<p class="smallmarginbottom"><em><small>Advanced Features</small></em></p>
	<p>Gantry provides the template foundation, with its standard set of features, such as the advanced template manager.</p>
	<a href="http://gantry.org" class="readon"><span>Read More</span></a>
	<div class="clear"></div>
</div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_2.jpeg
[demo2]: assets/rokajaxsearch_1.jpeg
[demo3]: assets/rokajaxsearch_2.jpeg
[demo4]: assets/rokajaxsearch_3.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg