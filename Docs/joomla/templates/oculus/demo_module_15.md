---
title: Oculus: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

Contact Us
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Contact Us`         |  
| Show Title | Show                 |  
| Position   | footer-d             |  
| Status     | Published            |  
| Access     | Public               |  
| Language   | All                  |  
| Note       | Blank                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-10 gantry-width-block hidden-phone">
    <span class="icon-phone"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <strong><span>+1 (555) 555-555-5555</span></strong><br />
    <small>+1 (555) 555-555-5556</small>
</div>

<div class="gantry-width-10 gantry-width-block hidden-phone">
    <span class="icon-home"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
	<strong><span>Oculus Theme, LLC</span></strong><br />
    <span>123 Joomla! Boulevard</span><br />
    <small>Seattle, WA 00000, USA</small> 
</div>

<div class="gantry-width-10 gantry-width-block hidden-phone">
    <span class="icon-envelope-alt"></span>
</div>
<div class="gantry-width-90 gantry-width-block">
    <span>noreply/@domain.com</span>
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

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `fp-footer hidden-phone` |  

[demo]: assets/demo_module_7.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg