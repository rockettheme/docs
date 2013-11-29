---
title: Praxis: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Praxis Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/praxis:Praxis

---

FP Footer A
-----
![][demo]

:   1. **FP Footer A** [35%, 6%, se]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | FP Footer A        |  
| Show Title        | Hide               |  
| Position          | footer-a           |  
| Status            | Published          |  
| Access            | Public             |   
| Language          | All                |  
| Note              | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-footer-logo rt-floatleft largepaddingright largemarginbottom"></div>

<p class="largemarginleft"><span class="hidden-tablet">All demo content is for sample purposes only, intended to show a live site. </span>All images are licensed from <strong><a href="http://www.shutterstock.com">ShutterStock</a></strong> for exclusive use on this demo site. <span class="visible-large">To replicate a near equivalent copy of the demo onto your server, use the RocketLauncher package.</span></p>

<div class="clear"></div><br />

<div class="hidden-phone">
	<p class="promo3">+1 (123) 456-5555-555</p>
	<p class="medmarginbottom">Praxis Theme, LLC</p>
	<p class="medmarginbottom">123 Joomla! Boulevard</p>
	<p class="medmarginbottom">Seattle, WA 00000, USA</p>
	<p><a href="#">noreply/@domain.com</a></p>	
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

| Option              | Setting          |  
| :------------------ | :--------------- |  
| Module Class Suffix | box5 fp-footer-b |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/footer_1.jpeg
[demo3]: assets/footer_2.jpeg
[demo4]: assets/footer_3.jpeg