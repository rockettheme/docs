---
title: Ionosphere: Recreating the Demo - Contact Details
description: Your Guide to Recreating Elements of the Ionosphere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ionosphere:Ionosphere

---

Contact Details
-----
![][demo]

:   1. **mod_custom** [20%, 67%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `Contact Details` |  
| Show Title | Show              |  
| Position   | footer-c          |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="feature">
<img src="images/stories/demo/frontpage/fp-footer-icon1.png" alt="image" class="largepaddingleft floatleft smallpaddingright medpaddingtop" />
<a><em class="bold2 nobold">+1 (555) 555-555-5555</em></a><br />
<a><em class="bold2 nobold">+1 (555) 555-555-5556</em></a>
<div class="clear largemarginbottom">&nbsp;</div>
<img src="images/stories/demo/frontpage/fp-footer-icon3.png" alt="image" class="largepaddingleft floatleft smallpaddingright largemarginbottom largepaddingbottom" />
<em class="bold2 nobold">
	Ionosphere Theme LLC<br />
	123 Joomla! Boulevard<br />
	Seattle, WA 00000, USA
</em>
<div class="clear largemarginbottom">&nbsp;</div>
<img src="images/stories/demo/frontpage/fp-footer-icon4.png" alt="image" class="largepaddingleft floatleft smallpaddingright" />
<em class="bold2 nobold">noreply&#64;domain.com</em>
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

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `title1 promo` |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg