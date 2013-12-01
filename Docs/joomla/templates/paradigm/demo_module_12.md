---
title: Paradigm: Recreating the Demo - FP Footer Menu
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

FP Footer Menu
-----

![][demo]

:	1. **mod_custom** [30%, 69%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `FP Footer Menu` |  
| Show Title | Show             |  
| Position   | footer-c         |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer">
		<h2 class="title">Info</h2>
		<p class="nomarginbottom"><a href="#">About</a></p>
		<p class="nomarginbottom"><a href="#">Blog</a></p>
		<p class="nomarginbottom"><a href="#">Team</a></p>
	</div>
</div>

<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer">
		<h2 class="title">Work</h2>
		<p class="nomarginbottom"><a href="#">Portfolio</a></p>
		<p class="nomarginbottom"><a href="#">Services</a></p>
	</div>
</div>

<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer">
		<h2 class="title">Support</h2>	
		<p class="nomarginbottom"><a href="#">Help</a></p>
		<p class="nomarginbottom"><a href="#">Contact</a></p>
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

| Option              | Setting          |  
| :------------------ | :--------------- |  
| Module Class Suffix | `fp-footer-menu` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/footermenu_1.jpeg
[demo3]: assets/footermenu_2.jpeg
[demo4]: assets/footermenu_3.jpeg