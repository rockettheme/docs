---
title: Acacia: Recreating the Demo - Demo Info
description: Your Guide to Recreating Elements of the Acacia Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/acacia:Acacia

---

Demo Info
-----

![][demo]

:	1. **mod_custom** [35%, 8%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Demo Info` |  
| Show Title | Show        |  
| Position   | footer-a    |  
| Status     | Published   |  
| Language   | All         |  
| Note       | Blank       |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p class="rt-intro-text">All demo content is for sample purpose only, intended to show a live site. Use the <a href="#">Acacia RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
<p>Acacia is only available as part of the Club Subscription.</p>

<div class="gantry-width-40">
	<div class="gantry-width-spacer">
		<span id="rt-footer-logo"></span>
	</div>
</div>

<div class="gantry-width-60">
	<div class="gantry-width-spacer">
		<span class="rt-intro-text">+1(123)456-5555-555</span><br />
		<span>Acacia Theme, LLC</span><br />
		<span>123 Joomla! Boulevard</span><br />
		<span>Seattle, WA 00000, USA</span><br />
		<span><a href="#">noreply/@domain.com</a></span>
	</div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg