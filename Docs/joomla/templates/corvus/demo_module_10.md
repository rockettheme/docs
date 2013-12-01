---
title: Corvus: Recreating the Demo - Popular Templates
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Popular Templates
----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                |  
| :--------- | :----------------------------------------------------- |  
| Title      | `Popular [span class="hidden-tablet"]Templates[/span]` |  
| Show Title | Show                                                   |  
| Position   | extension-a                                            |  
| Status     | Published                                              |  
| Language   | All                                                    |  
| Note       | Blank                                                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="hidden-phone">
	<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img1.png" />
	</div></div>

	<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img2.png" />
	</div></div>

	<div class="gantry-width-25 gantry-width-block"><div class="largemarginright">
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img3.png" />
	</div></div>

	<div class="gantry-width-25 gantry-width-block"><div class="largemarginleft">
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img4.png" />
	</div></div>
	<div class="clear"></div>
</div>

<div class="visible-phone">
	<div class="largemargintop largemarginbottom largemarginright largepaddingtop">
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img1.png" /><br />
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img2.png" /><br />
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img3.png" /><br />
		<img class="rt-extension-img" alt="image" src="images/rocketlauncher/frontpage/extension/img4.png" />
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

| Option              | Setting                        |  
| :------------------ | :----------------------------- |  
| Module Class Suffix | `fp-extension horiztitle box6` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/templates_1.jpeg
[demo3]: assets/templates_2.jpeg
[demo4]: assets/templates_3.jpeg