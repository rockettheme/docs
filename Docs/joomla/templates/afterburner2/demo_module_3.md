---
title: Afterburner2: Recreating the Demo - Template Extras
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Template Extras
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
<div class="gantry-width-50 gantry-width-block"><div class="gantry-width-spacer">
<div class="rt-relative largemarginbottom  largepaddingbottom largepaddingright rt-border-right rt-border-bottom">
	<span>Afterburner2 is an experiment in how streamlined a Gantry template can be whilst still being stunning and usable. Many extras have been removed, but still contains styling for major elements.</span>
	<div class="clear"></div>
</div>
</div></div>

<div class="gantry-width-50 gantry-width-block"><div class="gantry-width-spacer">
<div class="rt-relative largemarginbottom  largepaddingbottom largepaddingright rt-border-right rt-border-bottom">
	<div class="rt-small-icon rt-red icon-tasks"></div>
	<h5 class="smallmarginbottom nomargintop">Dropdowns</h5>
	<span>A CSS based dropdown menu system.</span>
	<div class="clear"></div>
</div>
</div></div>

<div class="clear"></div>

<div class="gantry-width-50 gantry-width-block"><div class="gantry-width-spacer">
<div class="rt-relative largemarginbottom  largepaddingbottom largepaddingright rt-border-right">
	<div class="rt-small-icon rt-grey icon-list"></div>
	<h5 class="smallmarginbottom nomargintop">Typography</h5>
	<span>Elements are styled by a streamlined version of Bootstrap.</span>
	<div class="clear"></div>
</div>
</div></div>

<div class="gantry-width-50 gantry-width-block"><div class="gantry-width-spacer">
<div class="rt-relative largemarginbottom  largepaddingbottom largepaddingright rt-border-right">
	<div class="rt-small-icon rt-blue icon-edit"></div>
	<h5 class="smallmarginbottom nomargintop">Optimized</h5>
	<span>Afterburner2 has only one image, which is 3KB in size.</span>
	<div class="clear"></div>
</div>
</div></div>

<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_3.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg