---
title: Spectral: Recreating the Demo -  FP Footer Contact Info
description: Your Guide to Recreating Elements of the Spectral Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/spectral:Spectral

---

FP Footer Contact Info
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `FP Footer Contact Info` |  
| Show Title | Hide                     |  
| Position   | footer-b                 |  
| Status     | Published                |  
| Language   | All                      |  
| Note       | Blank                    |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="largemargintop">
	<div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
	    <span class="icon-phone"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
	    <span class="rt-intro-text">+1 (555) 555-555-5555</span><br />
	</div>
	<div class="clear largemarginbottom largepaddingbottom"></div>
	<div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
	    <span class="icon-home"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
		<span class="rt-intro-text">Spectral Theme, LLC</span><br />
	    <span>123 Joomla! Boulevard</span><br />
	    <span>Seattle, WA 00000, USA</span> 
	</div>
	<div class="clear largemarginbottom largepaddingbottom"></div>
	<div class="gantry-width-10 gantry-width-block smallpaddingtop hidden-phone">
	    <span class="icon-envelope-alt"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
	    <span class="rt-intro-text"><a href="#">noreply/@domain.com</a></span>
	</div>
	<div class="clear"></div>	
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

| Option              | Setting                               |  
| :------------------ | :------------------------------------ |  
| Module Class Suffix | `fp-footer-contact-info hidden-phone` |  

[demo]: assets/demo_15.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg