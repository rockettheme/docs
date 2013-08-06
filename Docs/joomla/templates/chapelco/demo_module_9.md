---
title: Chapelco: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Chapelco Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chapelco:Chapelco

---

Contact Us
-----
![][demo]

:   1. **mod_custom** [20%, 35%, se]

We used a **mod_custom** module to make up the content in the **footer-b** position of the front page. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | Contact Us         |  
| Show Title        | Show               |  
| Position          | footer-b           |  
| Status            | Published          |  
| Access            | Public             |  
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-10 gantry-width-block">
    <span class="icon-phone"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <strong><span>+1 (555) 555-555-5555</span></strong><br />
    <small>+1 (555) 555-555-5556</small>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block">
    <span class="icon-home"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
	<strong><span>Chapelco Theme, LLC</span></strong><br />
    <span>123 Joomla! Boulevard</span><br />
    <small>Seattle, WA 00000, USA</small> 
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block">
    <span class="icon-envelope-alt"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>noreply/@domain.com</span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>
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

[demo]: assets/demo_8.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg