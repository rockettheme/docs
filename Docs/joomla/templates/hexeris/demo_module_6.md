---
title: Hexeris: Recreating the Demo - Demo Replica
description: Your Guide to Recreating Elements of the Hexeris Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

Demo Replica
-----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting                                                        |  
| :---------------- | :------------------------------------------------------------- |  
| Title             | `Demo Replica [span class="rt-subtitle"]RocketLauncher[/span]` |  
| Show Title        | Show                                                           |  
| Position          | extension-b                                                    |  
| Status            | Published                                                      |  
| Access            | Public                                                         |  
| Language          | All                                                            |  
| Note              | Blank                                                          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-20 gantry-width-block">
	<span class="box2 rt-med-icon">
		<span class="rokicon-profile2"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Quick Install.</h5>
		<p class="nomarginbottom">Replicate the demo easily with a custom Joomla installation package.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<div class="gantry-width-20 gantry-width-block">
	<span class="box1 rt-med-icon">
		<span class="rokicon-message"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Forum Guide.</h5>
		<p class="nomarginbottom">A forum tutorial on replicating the demo frontpage is also available.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<div class="gantry-width-20 gantry-width-block">
	<span class="box4 rt-med-icon">
		<span class="rokicon-alarm-clock"></span>
	</span>
</div>

<div class="gantry-width-80 gantry-width-block">
  <div class="smallmarginleft">
		<h5 class="smallmarginbottom">Sample Images.</h5>
		<p class="nomarginbottom">Due to copyright reasons, demo images are replaced with sample versions.</p>
  </div>
</div>

<div class="clear"></div>
<div class="rt-separator"></div> 

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115">Read More</a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                   |  
| :------------------ | :------------------------ |  
| Module Class Suffix | `box3 hidden-phone` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/replica_1.jpeg
[demo3]: assets/replica_2.jpeg
[demo4]: assets/replica_3.jpeg