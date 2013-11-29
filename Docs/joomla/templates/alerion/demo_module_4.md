---
title: Alerion: Recreating the Demo - Who's Going
description: Your Guide to Recreating Elements of the Alerion Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Who's Going
-----
![][demo]

:   1. **mod_custom** [70%, 20%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting               |  
| :--------- | :-------------------- |  
| Title      | Who's Going           |  
| Show Title | Hide                  |  
| Position   | floatingmodule-bottom |  
| Status     | Published             |  
| Access     | Public                |  
| Language   | All                   |  
| Note       | Blank                 |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-30 gantry-width-block rt-center">
    <em><strong>Who's Going</strong></em>
</div>

<div class="gantry-width-70 gantry-width-block">
	<div class="rt-floatright">
		<button class="btn btn-inverse rt-large-button"><span class="icon-facebook"></span> <span class="hidden-tablet">Connect with </span>Facebook</button>
	</div>		
</div>

<div class="clear largemarginbottom largepaddingbottom">&nbsp;</div>

<div class="gantry-width-30 gantry-width-block rt-center">
	<span class="rt-price-alt"><span class="rt-currency">$</span> 129</span>
</div>

<div class="gantry-width-70 gantry-width-block">
	<div class="rt-floatright">
		<a href="#" class="btn btn-large btn-primary rt-large-button"><span class="visible-tablet">Signup</span><span class="hidden-tablet">Register Today</span> <span class="icon-arrow-right"></span></a>
	</div>		
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

| Option              | Setting                       |  
| :------------------ | :---------------------------- |  
| Module Class Suffix | `box1 fp-feature-b jaggedtop` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/going_1.jpeg
[demo3]: assets/going_2.jpeg
[demo4]: assets/going_3.jpeg
[recreate]: demo.md#rokcandy