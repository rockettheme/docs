---
title: Afterburner2: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Contact Us
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Contact Us`        |  
| Show Title | Show                |  
| Position   | bottom-b            |  
| Status     | Published           |  
| Access     | Public              |  
| Language   | All                 |  
| Note       | Blank               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-15 gantry-width-block">
	<h4><span class="icon-phone"></span></h4>	
</div>
<div class="gantry-width-85 gantry-width-block">
	<strong>+1 (555) 555-555-5555</strong>
	<br/>
	<span>+1 (555) 555-555-5556</span>
</div>

<div class="clear"></div>

<div class="gantry-width-15 gantry-width-block">
	<h4><span class="icon-home"></span></h4>	
</div>
<div class="gantry-width-85 gantry-width-block">
	<span>123 Joomla! Boulevard</span>
	<br />
	<span>Seattle, WA 00000, USA</span> 
</div>

<div class="clear"></div>

<div class="gantry-width-15 gantry-width-block">
	<h4 class="nomargintop"><span class="icon-envelope-alt"></span></h4>	
</div>
<div class="gantry-width-85 gantry-width-block">
	<span>noreply@domain.com</span>
</div>

<div class="clear"></div>

~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg