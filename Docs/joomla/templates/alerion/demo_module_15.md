---
title: Alerion: Recreating the Demo - RokSprocket Layouts
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

RokSprocket Layouts
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Alerion -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:	1. **Leading Articles** [42%, 72%, se]
	2. **Article Order** [68%, 72%, se]

In order to show two featured articles on the front page, we placed a `2` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**.

Article Properties
-----

The **RokSprocket Layouts** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<h2 class="largemarginbottom"><span>RokSprocket <span class="hidden-phone">Layouts.</span></span></h2>
<div class="subline smallmarginleft">Powerful Content Extension</div>

<div class="clear medmarginbottom"></div>

<div class="gantry-width-50 gantry-width-block">
    <div class="largemarginright">
	    <div class="rt-image nomargintop">
	    	<img src="images/rocketlauncher/frontpage/featured-articles/img1.jpg" alt="image" />
	    </div>
	</div>	    
</div>
<div class="gantry-width-50 gantry-width-block">
	<div class="largemarginleft">
		<p><strong>RokSprocket</strong> is a powerful content display extension with multiple <strong>layout</strong> modes<span class="hidden-tablet">: Mosaic, Tabs, Headlines, Lists and Features;</span> and an advanced, custom administrator.<span class="hidden-tablet"> Alerion has RokSprocket styling for seamless <strong>integration</strong>.</span></p>
		<a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113" class="readon">Read More</a>		
	</div>
</div>
<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_12.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg