---
title: Kirigami: Recreating the Demo - Contact Details
description: Your Guide to Recreating Elements of the Kirigami Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kirigami:Kirigami

---

Contact Details
----
![][demo]

:   1. **mod_custom** [20%, 66%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `Contact Details` |  
| Show Title | Show              |  
| Position   | footer-c          |  
| Status     | Published         |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<img class="rt-floatleft" alt="image" src="images/rocketlauncher/frontpage/general/fp-footer-icon1.png" />
<a href="#"><em class="bold">+1 (555) 555-555-5555</em></a><br />
<a href="#"><em class="bold nobold">+1 (555) 555-555-5556</em></a>

<div class="clear largemarginbottom">&nbsp;</div>

<img class="rt-floatleft" alt="image" src="images/rocketlauncher/frontpage/general/fp-footer-icon2.png" />
<em class="bold">
  <strong>Kirigami Template LLC</strong><br />
</em>
<em class="bold nobold">
  123 Joomla! Boulevard<br />
  Seattle, WA 00000<br />
  United States of America
</em>

<div class="clear largemarginbottom">&nbsp;</div>

<img class="rt-floatleft" alt="image" src="images/rocketlauncher/frontpage/general/fp-footer-icon3.png" />
<em class="bold">noreply/@domain.com</em>
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

[demo]: assets/demo_6.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg