---
title: Leviathan: Recreating the Demo - Top Features
description: Your Guide to Recreating Elements of the Leviathan Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/leviathan:Leviathan

---

Top Features
-----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                                                        |  
| :--------- | :--------------------------------------------------------------------------------------------- |  
| Title      | `[span class="hidden-large"]Top Feature[/span][span class="visible-large"]Top Features[/span]` |  
| Show Title | Show                                                                                           |  
| Position   | showcase-a                                                                                     |  
| Status     | Published                                                                                      |  
| Access     | Public                                                                                         |  
| Language   | All                                                                                            |  
| Note       | Blank                                                                                          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="visible-large">
    <div class="gantry-width-25 gantry-width-block">
	  <span class="rt-image"><img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img1.jpg" /></span>
	</div>

	<div class="gantry-width-75 gantry-width-block rt-condensed-text">
	  <div class="largemarginleft">
	    <h4 class="normalfont nomargintop nomarginbottom">Responsive Layout</h4>
	    <small>Multiple device support, for mobile, tablet or desktop displays, that are automatically adjusted to.</small>
	  </div>
	</div>
	<div class="clear"></div>	
	<div class="gantry-width-25 gantry-width-block largemargintop">
	  <span class="rt-image"><img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img2.jpg" /></span>
	</div>

	<div class="gantry-width-75 gantry-width-block rt-condensed-text largemargintop">
	  <div class="largemarginleft">
	    <h4 class="normalfont nomargintop nomarginbottom">Integrated Extensions</h4>
	    <small>Template specific styling for several extensions such as RokSprocket and K2.</small>
	  </div>
	</div>	

</div>

<div class="visible-desktop">
	<div class="gantry-width-30 gantry-width-block">
	  <span class="rt-image"><img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img1.jpg" /></span>
	</div>

	<div class="gantry-width-70 gantry-width-block rt-condensed-text">
	  <div class="largemarginleft">
	    <h4 class="normalfont nomargintop nomarginbottom">Responsive</h4>
	    <small>Multiple device support, for mobile, tablet or desktop displays.</small>
	  </div>
	</div>	
</div>                            
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                                                                                                                              |  
| :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Module Class Suffix | `fp-topfeature icon-star hidden-tablet hidden-phone smallpaddingtop nopaddingbottom medpaddingleft medpaddingright smallmarginleft smallmarginright` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/top_1.jpeg
[demo3]: assets/top_2.jpeg
[demo4]: assets/top_3.jpeg