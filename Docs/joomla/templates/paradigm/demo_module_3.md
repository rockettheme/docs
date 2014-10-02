---
title: Paradigm: Recreating the Demo - Template Features
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Template Features
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below. Due to the `hidden-phone` Module Class Suffix setting, this module will not appear on mobiles.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Template Features` |  
| Show Title | Hide                |  
| Position   | feature-a           |  
| Status     | Published           |  
| Access     | Public              |  
| Language   | All                 |  
| Note       | Blank               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="module-title">
  <h2 class="title">Template Features<span class="rt-title-tag">Paradigm provides the tools you need to setup your website with ease.</span></h2>
</div>

<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer">
		<div class="rt-feature-item">
			<div class="rt-arrow-right"></div>
			<h4 class="rt-uppercase">Dropdown Menu</h4>
			<p>A CSS based dropdown menu system<span class="hidden-tablet">, with numerous advanced features such as inline modules and multiple columns</span>.</p>
		</div>

		<div class="rt-feature-item">
			<div class="rt-arrow-right"></div>
			<h4 class="rt-uppercase">Module Variations</h4>
			<p>There are eight stylistic suffixes<span class="hidden-tablet">, to provide individual module styling, as well as several structural suffixes</span>.</p>
		</div>

		<div class="rt-feature-item">
			<div class="rt-arrow-right"></div>
			<h4 class="rt-uppercase">Module Positions</h4>
			<p>There are over 80 module positions<span class="hidden-tablet">, most split into rows of 6, each with adjustable widths, globally or per menu item</span>.</p>
		</div>	

		<div class="rt-feature-item visible-large">
			<div class="rt-arrow-right"></div>
			<h4 class="rt-uppercase">SplitMenu</h4>
			<p>SplitMenu is a static menu option that displays parents in the header and children in the sidebar, as configurable.</p>
		</div>						
	</div>
</div>
<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer rt-center nomarginbottom">
		<img src="images/rocketlauncher/frontpage/feature/img1.png" alt="image" />
	</div>
</div>
<div class="gantry-width-block gantry-width-33">
	<div class="gantry-width-spacer">
		<div class="rt-feature-item">
			<div class="rt-arrow-left"></div>
			<h4 class="rt-uppercase">Preset Styles</h4>
			<p>Choose from eight preset style variations<span class="hidden-tablet">, with configurable options for text, link, accent, and background colors.</span></p>
		</div>

		<div class="rt-feature-item">
			<div class="rt-arrow-left"></div>
			<h4 class="rt-uppercase">RokSprocket</h4>
			<p>A versatile content display extension<span class="hidden-tablet">, with integrated styling in Paradigm, including the Features layout option</span>.</p>
		</div>

		<div class="rt-feature-item">
			<div class="rt-arrow-left"></div>
			<h4 class="rt-uppercase">RocketLauncher</h4>
			<p>A custom Joomla installation package<span class="hidden-tablet"> that installs a near equivalent of the demo onto your server</span>.</p>
		</div>
		
		<div class="rt-feature-item visible-large">
			<div class="rt-arrow-left"></div>
			<h4 class="rt-uppercase">Typography</h4>
			<p>A beautiful and rich selection of typography, based on Boostrap, to emphasise and embellish the content elements.</p>
		</div>
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

| Option              | Setting                                          |  
| :------------------ | :----------------------------------------------- |  
| Module Class Suffix | `fp-feature rt-big-title rt-center hidden-phone` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/template_1.jpeg
[demo3]: assets/template_2.jpeg
[demo4]: assets/template_3.jpeg
