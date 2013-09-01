---
title: Praxis: Recreating the Demo - FP Utility
description: Your Guide to Recreating Elements of the Praxis Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/praxis:Praxis

---

FP Utility
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | FP Utility         |  
| Show Title        | Hide               |  
| Position          | utility-a          |  
| Status            | Published          |  
| Access            | Public             |  
| Ordering          | 1. FP Feature      |  
| Start Publishing  | 0000-00-00 00:00:0 |  
| Finish Publishing | 0000-00-00 00:00:0 |  
| Language          | All                |  
| Note              | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="hidden-phone">
	<p class="largemargintop"><span class="promo2"><strong><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Responsive:</a></strong> mobile, tablet &amp; desktop in one.</span></p>

	<div class="largemargintop largemarginbottom largemarginright largepaddingtop">
		<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
			<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img1.png" />
		</div></div>

		<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
			<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img2.png" />
		</div></div>

		<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
			<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img3.png" />
		</div></div>

		<div class="gantry-width-25 gantry-width-block"><div class="largemarginleft">
			<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img4.png" />
		</div></div>
		<div class="clear"></div>
	</div>	
</div>

<div class="visible-phone rt-center">
	<p class="largemargintop"><span class="promo2"><strong><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Responsive:</a></strong> mobile, tablet &amp; desktop in one.</span></p>

	<div class="largemargintop largemarginbottom largemarginright largepaddingtop">
		<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img1.png" /><br />
		<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img2.png" /><br />
		<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img3.png" /><br />
		<img class="rt-utility-img" alt="image" src="images/rocketlauncher/frontpage/utility/img4.png" />
	</div>	
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |  

### Advanced
![][demo4]

| Option              | Setting              |  
| :------------------ | :------------------- |  
| Module Class Suffix | `fp-sidenav-spacing` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/utility_1.jpeg
[demo3]: assets/utility_3.jpeg
[demo4]: assets/utility_4.jpeg