---
title: Afterburner2: Recreating the Demo - Frontpage Showcase
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Frontpage Showcase
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Frontpage Showcase` |  
| Show Title | Hide                 |  
| Position   | header-a             |  
| Status     | Published            |  
| Access     | Public               |  
| Language   | All                  |  
| Note       | Blank                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center largemargintop largemarginbottom smallpaddingbottom">
	<h1 class="largemargintop largemarginbottom medpaddingbottom">Fast, Responsive &amp; Free!</h1>
	<h4 class="nobold"><em>Afterburner2 is a streamlined Gantry template, focused on speed and performance.</em></h4>
</div>	    

<div class="gantry-width-33 gantry-width-block hidden-phone">
    <div class="gantry-width-spacer">
		<div class="gantry-width-30 gantry-width-block">        
			<div class="largemarginright">
				<div class="rt-num">1.0</div>
			</div>				
	 	</div>   
		<div class="gantry-width-70 gantry-width-block">
        	<h5>Gantry 4 Core</h5>
			<span>Built on the Gantry 4 Framework, Afterburner2 benefits from its rich<span class="visible-large">, powerful</span> core.</span>
			<br />
        	<a href="http://www.gantry-framework.org" class="readon largemargintop"><span>Read More</span></a>
		</div>
		<div class="clear"></div>
    </div>
</div>

<div class="gantry-width-33 gantry-width-block hidden-phone">
    <div class="gantry-width-spacer">
		<div class="gantry-width-30 gantry-width-block">        
			<div class="largemarginright">
				<div class="rt-num">2.0</div>
			</div>				
	 	</div>   
		<div class="gantry-width-70 gantry-width-block">
        	<h5>Performance</h5>  
			<span>An optimized amount of features and extras are used in this template to focus on speed.</span>
			<br />
        	<a href="#" class="readon largemargintop"><span>Read More</span></a>
		</div>
		<div class="clear"></div>
    </div>
</div>

<div class="gantry-width-33 gantry-width-block hidden-phone">
    <div class="gantry-width-spacer">
		<div class="gantry-width-30 gantry-width-block">        
			<div class="largemarginright">
				<div class="rt-num">3.0</div>
			</div>				
	 	</div>   
		<div class="gantry-width-70 gantry-width-block">
        	<h5>RokBooster<span class="hidden-tablet"> Ready</span></h5>  
			<span>Compress CSS/scripts/images <span class="hidden-tablet">with RokBooster </span>to increase speed even further.</span>
			<br />
        	<a href="http://www.rockettheme.com/joomla/extensions/rokbooster" class="readon largemargintop"><span>Read More</span></a>
		</div>
		<div class="clear"></div>
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

| Option              | Setting                                                          |  
| :------------------ | :--------------------------------------------------------------- |  
| Module Class Suffix | ` promo nomargintop nopaddingtop nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/showcase_1.jpeg
[demo3]: assets/showcase_2.jpeg
[demo4]: assets/showcase_3.jpeg