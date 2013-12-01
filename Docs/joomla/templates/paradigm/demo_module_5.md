---
title: Paradigm: Recreating the Demo - Gantry Framework
description: Your Guide to Recreating Elements of the Paradigm Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Gantry Framework
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Gantry Framework`  |  
| Show Title | Hide                |  
| Position   | maintop-a           |  
| Status     | Published           |  
| Access     | Public              |  
| Language   | All                 |  
| Note       | Blank               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-block gantry-width-50">
	<div class="gantry-width-spacer">
		<div class="rt-maintop-desc">
			<div class="module-title">
			  <h2 class="title">Gantry <span class="hidden-tablet">Framework</span></h2>
			</div>	
			<p class="rt-large-text">
				A powerful core framework that offers a standard set of<span class="hidden-tablet"> intuitive and expandable</span> features<span class="hidden-tablet">, for easy administration through an advanced user interface</span>.
			</p>			
		</div>
	</div>
</div>

<div class="gantry-width-block gantry-width-50">
	<div class="gantry-width-spacer">
		<img src="images/rocketlauncher/frontpage/maintop/img1.png" alt="img" />
	</div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-maintop1 rt-big-title` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/gantry_1.jpeg
[demo3]: assets/gantry_2.jpeg
[demo4]: assets/gantry_3.jpeg