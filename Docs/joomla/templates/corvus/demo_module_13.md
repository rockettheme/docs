---
title: Corvus: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Corvus Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Contact Us
----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting      |  
| :--------- | :----------- |  
| Title      | `Contact Us` |  
| Show Title | Show         |  
| Position   | footer-c     |  
| Status     | Published    |  
| Language   | All          |  
| Note       | Blank        |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="largemargintop largepaddingtop">
	<div class="gantry-width-10 gantry-width-block hidden-phone">
	    <span class="icon-phone"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
	    <strong><span>+1 (555) 555-555-5555</span></strong><br />
	    <span>+1 (555) 555-555-5556</span>
	</div>

	<div class="clear largemarginbottom"></div>

	<div class="gantry-width-10 gantry-width-block hidden-phone">
	    <span class="icon-home"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
		<strong><span>Corvus Theme, LLC</span></strong><br />
	    <span>123 Joomla! Boulevard</span><br />
	    <span>Seattle, WA 00000, USA</span> 
	</div>

	<div class="clear largemarginbottom"></div>

	<div class="gantry-width-10 gantry-width-block hidden-phone">
	    <span class="icon-envelope-alt"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
	    <strong><span><a href="#">noreply@domain.com</a></span></strong>
	</div>

	<div class="clear largemarginbottom"></div>	
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

| Option              | Setting                         |  
| :------------------ | :------------------------------ |  
| Module Class Suffix | `fp-footer-c box6 hidden-phone` |  

[demo]: assets/demo_13.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg