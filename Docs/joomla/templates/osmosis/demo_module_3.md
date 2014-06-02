---
title: Osmosis: Recreating the Demo - FP Content Top A 01
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

FP Content Top A 01
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `FP Content Top A 01` |
| Show Title  | Hide         |
| Position    | content-top-a    |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="fp-content-top-animate">
	<div class="gantry-width-container">
		<div class="gantry-width-66">
			<div class="fp-content-top-image-block">
				<img class="fp-content-top-image-01" src="images/rocketlauncher/home/fp-content-top/img-01.jpg" alt="image" />
				<div class="rt-top-content"><span class="readon">Alignment Options</span></div>
				<div class="rt-desc-overlay">
					<div class="rt-bottom-content">
						<h3 class="smallmarginbottom visible-desktop"><a href="#">Alignment Options</a></h3>
						<p class="rt-text-small"><span>Osmosis benefits from a fluid alignment option<span class="visible-desktop">, focussing in the left hand side bar, as well as a centered/more fixed responsive option</span></span>.</p>
					</div>
				</div>
			</div>
		</div>
		<div class="gantry-width-33">
			<div class="gantry-width-spacer">
				<p class="rt-text-small largepaddingtop nomarginbottom">Sidepanel Position</p>
				<h2 class="title">Dynamically revealed<span class="hidden-tablet"> modular content</span></h2>
				<p class="hidden-tablet"><strong><span>Scroll to unveil the modules in the sidepanel position<span class="visible-large">, situated to the side of the mainbody area</span></span>.</strong></p>
				<p class="rt-text-small"><span>Several sidepanel templates options are also available<span class="visible-large">, such as a logo and a horizontal dropdown menu</span></span>.</p>
				<a href="#" class="readon4">Read More</a>
			</div>
		</div>
	</div>
	<div class="clear"></div>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                   |
| :----------         | :----------               |
| Module Class Suffix | `fp-content-top-a1` |

[demo]: assets/demo_3.jpg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
