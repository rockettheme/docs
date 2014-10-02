---
title: Chimera: Recreating the Demo - Tags
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Tags
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting   |  
| :--------- | :-------- |  
| Title      | `Tags`    |  
| Show Title | Show      |  
| Position   | footer-d  |  
| Status     | Published |  
| Access     | Public    |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul class="rt-tags">
	<li>Clean</li>
	<li>Colorful</li>
	<li>Elegant</li>
	<li>Corporate</li>
	<li>Modern</li>
	<li>Flat</li>
	<li>Typography</li>
	<li>Photo Gallery</li>
</ul>
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
| :----------         | :----------                   |
| Module Class Suffix | `wow fadeInDown hidden-phone` |

[demo]: assets/demo_16.jpeg
[demo2]: assets/demo_16a.jpeg
[demo3]: assets/demo_16b.jpeg
[demo4]: assets/demo_16c.jpeg
