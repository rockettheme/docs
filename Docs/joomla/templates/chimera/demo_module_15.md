---
title: Chimera: Recreating the Demo - About Us
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

About Us
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting    |  
| :--------- | :--------- |  
| Title      | `About Us` |  
| Show Title | Show       |  
| Position   | footer-c   |  
| Status     | Published  |  
| Access     | Public     |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>
	<span><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=120">Team</a></span><br />
	<span><a href="index.php?option=com_content&amp;view=article&amp;id=9&amp;Itemid=121">Services</a></span><br />
	<span><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=122">Pricing Table</a></span><br />
	<span><a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=123">Portfolio</a></span><br />
	<span><a href="index.php?option=com_content&amp;view=category&amp;layout=blog&amp;id=13&amp;Itemid=124">Blog</a></span><br />
	<span><a href="index.php?option=com_content&amp;view=article&amp;id=12&amp;Itemid=125">FAQ</a></span><br />
	<span><a href="http://www.rockettheme.com/docs/joomla/templates/chimera">Tutorial</a></span>
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

[demo]: assets/demo_15.jpeg
[demo2]: assets/demo_15a.jpeg
[demo3]: assets/demo_15b.jpeg
[demo4]: assets/demo_15c.jpeg
