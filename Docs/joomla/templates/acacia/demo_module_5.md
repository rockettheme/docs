---
title: Acacia: Recreating the Demo - FP Expanded Top
description: Your Guide to Recreating Elements of the Acacia Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/acacia:Acacia

---

FP Expanded Top
-----

![][demo]

:	1. **mod_custom** [80%, 18%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `FP Expanded Top`    |  
| Show Title | Show                 |  
| Position   | expandedtop-a        |  
| Status     | Published            |  
| Access     | Public               |  
| Language   | All                  |  
| Note       | Blank                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center rds-details">
	<span class="rds-detail">
		<span class="icon-angle-down"></span> <span>Gantry</span> <strong>-378</strong>
	</span>
	<span class="rds-detail">
		<span class="icon-angle-up"></span> <span>Framework</span> <strong>+1,036</strong>
	</span>
	<span class="rds-detail">
		<span class="icon-angle-up"></span> <span>Responsive</span> <strong>+612</strong>
	</span>
	<span class="rds-detail">
		<span class="icon-angle-down"></span> <span>Layouts</span> <strong>-1,078</strong>
	</span>
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

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `medmarginall` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/expanded_1.jpeg
[demo3]: assets/expanded_2.jpeg
[demo4]: assets/expanded_3.jpeg