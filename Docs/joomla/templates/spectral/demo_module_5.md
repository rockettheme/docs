---
title: Spectral: Recreating the Demo - About Spectral
description: Your Guide to Recreating Elements of the Spectral Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/spectral:Spectral

---

About Spectral
-----

![][demo]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `About Spectral`     |  
| Show Title | Show                 |  
| Position   | feature-b            |  
| Status     | Published            |  
| Access     | Public               |  
| Language   | All                  |  
| Note       | Blank                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="fp-about-spectral-image-container">
	<div class="gantry-width-50">
		<div class="rt-image-container">
			<img src="images/rocketlauncher/frontpage/about-spectral/img1.jpg" alt="image" />
			<div class="rt-image-description rt-hover1">
				<div class="rt-image-content">
					<span class="icon-heart"></span>
					<span class="rt-image-text">Elegant</span>					
				</div>
			</div>			
		</div>
	</div>
	<div class="gantry-width-50">
		<div class="rt-image-container">
			<img src="images/rocketlauncher/frontpage/about-spectral/img2.jpg" alt="image" />
			<div class="rt-image-description rt-hover2">
				<div class="rt-image-content">
					<span class="icon-camera"></span>
					<span class="rt-image-text">Modern</span>					
				</div>
			</div>			
		</div>
	</div>	
	<div class="clear"></div>
</div>

<h2 class="title">About Spectral<span class="rt-title-tag">RocketTheme Template</span></h2>

<p>A template design inspired by recent visual trends, blending subtle backgrounds and overlays, with text set by custom fonts, to create an alluring experience for your visitors, whilst maintaining an professional and functional look.</p>
<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107">Read More</a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `box4 fp-about-spectral` |  

[demo]: assets/demo_13.jpeg
[demo2]: assets/about_1.jpeg
[demo3]: assets/about_2.jpeg
[demo4]: assets/about_3.jpeg