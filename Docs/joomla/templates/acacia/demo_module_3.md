---
title: Acacia: Recreating the Demo - Page Options
description: Your Guide to Recreating Elements of the Acacia Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/acacia:Acacia

---

Page Options
-----
![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                                           |  
| :--------- | :-------------------------------------------------------------------------------- |  
| Title      | `Page Options [span class="rt-title-tag"]Multiple Layouts & Possibilities[/span]` |  
| Show Title | Show                                                                              |  
| Position   | feature-a                                                                         |  
| Status     | Published                                                                         |  
| Access     | Public                                                                            |  
| Language   | All                                                                               |  
| Note       | Blank                                                                             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-33">
	<div class="gantry-width-spacer">
		<div class="rt-center">
			<div class="canvas-graph" data-canvas-graph='{"icon":"icon-eye-open","iconSize":80,"radius":110,"size":15,"start":70}'><div class="longshadow"></div></div>
			<h3 class="title">HTML5 Charts</h3>
		</div>		
		<p>Acacia uses Chart.js and HTML5 canvas to display beautiful graphs and exquisite typography, such as the icon elements displayed in this row.</p>
		<div class="rt-center">
			<a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=112" class="readon">Read More</a>
		</div>
	</div>
</div>
<div class="gantry-width-33">
	<div class="gantry-width-spacer">
		<div class="rt-center">
			<div class="canvas-graph" data-canvas-graph='{"icon":"icon-inbox","iconSize":80,"radius":110,"size":15,"start":50}'><div class="longshadow"></div></div>
			<h3 class="title">Coming Soon</h3>
		</div>		
		<p>The template also supports a simple coming soon or offline style page with a time counter. It has been specifically styled to match Acacia.</p>
		<div class="rt-center">
			<a href="index.php?tmpl=comingsoon" class="readon">Read More</a>
		</div>
	</div>
</div>
<div class="gantry-width-33">
	<div class="gantry-width-spacer">
		<div class="rt-center">
			<div class="canvas-graph" data-canvas-graph='{"icon":"icon-camera","iconSize":80,"radius":110,"size":15,"start":35}'><div class="longshadow"></div></div>
			<h3 class="title">Flexible Layouts</h3>
		</div>		
		<p>The frontpage is just one example of how Acacia can be configured. See many different simple and complex examples on the link below.</p>
		<div class="rt-center">
			<a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=112" class="readon">Read More</a>
		</div>
	</div>
</div>
<div class="clear"></div>
~~~

You can find more information about the circular charts seen in this section by visiting our [Charts][charts] tutorial.

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `title1 dashed-title` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/page_1.jpeg
[demo3]: assets/page_2.jpeg
[demo4]: assets/page_3.jpeg
[charts]: charts.md