---
title: Praxis: Recreating the Demo - FP Feature
description: Your Guide to Recreating Elements of the Praxis Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/praxis:Praxis

---

FP Feature
-----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | FP Feature         |  
| Show Title        | Hide               |  
| Position          | feature-a          |  
| Status            | Published          |  
| Access            | Public             |  
| Ordering          | 1. FP Feature      |  
| Start Publishing  | 0000-00-00 00:00:0 |  
| Finish Publishing | 0000-00-00 00:00:0 |  
| Language          | All                |  
| Note              | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-block box2 rt-shadow rt-square fp-sidenav-spacing nomarginleft nomarginright">
	<p class="largepaddingall nomarginbottom"><span class="promo2"><strong><a href="#">About Praxis:</a></strong> An elegant visual platform with powerful interactive tools<span class="visible-large"> and versatile features</span>.</span></p>
</div>

<div class="fp-sidenav-spacing">	
	<div class="rt-center">
		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="images/rocketlauncher/frontpage/feature/img1.jpg" /></p>
				<h3 class="rt-dark-text">Fusion <strong>Menu</strong></h3>
				<p><strong>Fusion</strong> is a CSS powered dropdown menu system with advanced features such as multiple columns.</p>
			</div>
		</div>

		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="images/rocketlauncher/frontpage/feature/img2.jpg" /></p>
				<h3 class="rt-dark-text">Template  <strong>Speed</strong></h3>
				<p><strong>RokBooster</strong> offers compression, consolidation and compilation to improve <span class="hidden-tablet">CSS/JS/Image/Font </span>loading time.</p>
			</div>
		</div>

		<div class="gantry-width-33 gantry-width-block rt-dark-text">
			<div class="gantry-width-spacer">
				<p><img class="rt-img-rounded" alt="image" src="images/rocketlauncher/frontpage/feature/img3.jpg" /></p>
				<h3 class="rt-dark-text">Addon <strong>Styling</strong></h3>
				<p><strong>Praxis</strong> has styled integration for a variety of RocketTheme extensions as well as the third party CCK, K2.</p>
			</div>
		</div>

		<div class="clear"></div>
	</div>	
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
| Module Class Suffix | `nomarginleft` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/feature_1.jpeg
[demo3]: assets/feature_3.jpeg
[demo4]: assets/feature_4.jpeg