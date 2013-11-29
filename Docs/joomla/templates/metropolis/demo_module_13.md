---
title: Metropolis: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Metropolis Theme for Joomla
breadcrumb: /joomla:Joomla/templates:Templates/metropolis:Metropolis

---

Contact Us
-----
![][demo]

:   1. **mod_custom** [20%, 75%, se]

We used a **mod_custom** module to make up the content in the **footer-b** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | Contact Us        |  
| Show Title | Show              |  
| Position   | footer-c          |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-10 gantry-width-block medmarginright">
    <span class="icon-phone medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold nobold">+1 (555) 555-555-5555</em></a><br />
    <span><em class="bold nobold">+1 (555) 555-555-5556</em></span>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block medmarginright">
    <span class="icon-home medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <a href="#"><em class="bold nobold">Metropolis Template LLC</em></a><br />
    <em class="bold nobold">
      123 Joomla! Boulevard<br />
      Seattle, WA 00000, USA 
    </em>
</div>

<div class="clear medmarginbottom hidden-tablet">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block medmarginright hidden-tablet">
	<span class="icon-envelope-alt medmarginbottom largepaddingbottom"></span>
</div>
<div class="gantry-width-90 gantry-width-block hidden-tablet">
	<p><em class="bold nobold">noreply/@domain.com</em></p>
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

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `hidden-phone` |   

[demo]: assets/demo_7.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg