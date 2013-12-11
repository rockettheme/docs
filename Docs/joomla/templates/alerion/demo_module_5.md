---
title: Alerion: Recreating the Demo - TechnoEvent
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

TechnoEvent
-----
![][demo]

:   1. **mod_custom** [20%, 10%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting               |  
| :--------- | :-------------------- |  
| Title      | TechnoEvent           |  
| Show Title | Hide                  |  
| Position   | feature-a |  
| Status     | Published             |  
| Access     | Public                |  
| Language   | All                   |  
| Note       | Blank                 |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-60 gantry-width-block">
    <div class="gantry-width-10 gantry-width-block hidden-phone">
	    <span class="icon-map-marker rt-large-icon"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
		<h4 class="smallmargintop hidden-phone">East 27 Street and Campus Road,</h4>
	    <h4>Brooklyn, NY 11210</h4>
	</div>
</div>

<div class="gantry-width-40 gantry-width-block">
	<div class="gantry-width-10 gantry-width-block hidden-phone">
	    <span class="icon-mobile-phone rt-large-icon"></span>
	</div>
	<div class="gantry-width-90 gantry-width-block">
		<h4 class="smallmargintop hidden-phone">555.951.5528</h4>
	    <h4>555.951.5529</h4>
	</div>
</div>

<div class="clear"></div>

<div class="rt-image fp-image">
	<img alt="image" src="images/rocketlauncher/frontpage/feature/img1.jpg">
	<div class="rt-image-desc hidden-phone">
		<span><strong>Monday, April 1,</strong> 2013 at 1:00 PM</span><br />
		<span><strong>Tuesday, April 30,</strong> 2013 at 4:00 PM (PDT)</span>
	</div>
</div>

<div class="clear"></div>

<p><strong>Alerion</strong> is a visually intense design, focusing on <strong>rich</strong> elements split into distinct sections to add depth to content. Additional design features include configurable <strong>floating</strong> modules and <strong>quicknav</strong> feature, as well as <strong>parallax</strong> background effects.</p>

<p class="hidden-phone">Click the <strong>Quick Tour</strong> button in the floating module, titled '<strong>Your Tickets Here</strong>' to the right, to preview the Parallax effect. Parallax will be active when you <strong>scroll</strong> the page, and sections which are configured to show it are published and present.</p>
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
| Module Class Suffix | `title2 fp-feature-a` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/event_1.jpeg
[demo3]: assets/event_2.jpeg
[demo4]: assets/event_3.jpeg