---
title: Chimera: Recreating the Demo - Company Details
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Company Details
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `Company Details` |  
| Show Title | Show              |  
| Position   | footer-b          |  
| Status     | Published         |  
| Access     | Public            |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>
	<span>Chimera Theme, LLC</span><br />
	<span>123 Themes Boulevard</span><br />
	<span>Suite 10</span><br />
	<span>Anywhere, USA</span>
</p>

<p>
	<span>+1(555)555-5555</span><br />
	<span>me@chimera.com</span>
</p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                       |  
| :------------------ | :---------------------------- |  
| Module Class Suffix | `wow fadeInDown hidden-phone` |  

[demo]: assets/demo_14.jpeg
[demo2]: assets/demo_14a.jpeg
[demo3]: assets/demo_14b.jpeg
[demo4]: assets/demo_14c.jpeg
