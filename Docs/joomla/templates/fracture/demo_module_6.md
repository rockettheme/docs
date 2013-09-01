---
title: Fracture: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Fracture Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fracture:Fracture

---

Contact Us
-----
![][demo]

:   1. **mod_custom** [20%, 66%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Contact Us.`    |  
| Show Title | Show             |  
| Position   | footer-c         |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-width-10">
	<span class="icon-phone largemarginbottom largepaddingbottom"></span>
</div>
<div class="rt-demo-width-90">
	<a href="#"><em class="bold">+1 (555) 555-555-5555</em></a><br />
	<span><em class="bold nobold">+1 (555) 555-555-5556</em></span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="rt-demo-width-10">
	<span class="icon-home largemarginbottom largepaddingbottom"></span>
</div>
<div class="rt-demo-width-90">
	<a href="#"><em class="bold"><strong>Fracture Template LLC</strong></em></a><br />
	<em class="bold nobold">
	  123 Joomla! Boulevard<br />
	  Seattle, WA 00000<br />
	  United States of America
	</em>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="rt-demo-width-10">
	<span class="icon-envelope-alt largemarginbottom largepaddingbottom"></span>
</div>
<div class="rt-demo-width-90">
	<em class="bold">noreply/@domain.com</em>
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

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `title2 icon-info-sign hidden-phone` |   

[demo]: assets/demo_6.jpeg
[demo2]: assets/top_1.jpeg
[demo3]: assets/top_2.jpeg
[demo4]: assets/top_3.jpeg