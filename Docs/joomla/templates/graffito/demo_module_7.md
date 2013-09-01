---
title: Graffito: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Graffito Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/graffito:Graffito

---

Contact Us
-----
![][demo]

:   1. **mod_custom** [20%, 36%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting       |  
| :--------- | :------------ |  
| Title      | `Contact Us.` |  
| Show Title | Show          |  
| Position   | footer-b      |  
| Status     | Published     |  
| Access     | Public        |  
| Language   | All           |  
| Note       | Blank         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-10 gantry-width-block">
    <span class="icon-phone largemarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold">+1 (555) 555-555-5555</em></a><br />
    <span><em class="bold nobold">+1 (555) 555-555-5556</em></span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block">
    <span class="icon-home largemarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold"><strong>Graffito Template LLC</strong></em></a><br />
	<em class="bold nobold">
	  123 Joomla! Boulevard<br />
	  Seattle, WA 00000, USA 
	</em>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block hidden-tablet">
	<span class="icon-envelope-alt largemarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block hidden-tablet">
	<p><em class="bold">noreply@domain.com</em></p>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `title1 hidden-phone` |   

[demo]: assets/demo_6.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg