---
title: Osmosis: Recreating the Demo - FP Content Top A 02
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

FP Content Top A 02
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting               |
| :---------- | :----------           |
| Title       | `FP Content Top A 02` |
| Show Title  | Hide                  |
| Position    | content-top-a         |
| Status      | Published             |
| Access      | Public                |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container">
	<div class="gantry-width-25 box1">
		<div class="gantry-width-spacer">
			<p class="rt-text-small largepaddingtop medmarginbottom">Menu Systems</p>
			<h4 class="rt-text-white nomargintop">Dropdown Menu or SplitMenu</h4>
			<p class="rt-text-small">Choose between two configurable menus.</p>
		</div>
	</div>

	<div class="gantry-width-25 box2">
		<div class="gantry-width-spacer">
			<p class="rt-text-small largepaddingtop medmarginbottom">Integration</p>
			<h4 class="rt-text-white nomargintop">Selection of Styled Extensions</h4>
			<p class="rt-text-small">Styling for RokSprocket, K2 and others.</p>
		</div>
	</div>

	<div class="gantry-width-25 box3">
		<div class="gantry-width-spacer">
			<p class="rt-text-small largepaddingtop medmarginbottom">Gantry</p>
			<h4 class="rt-text-white nomargintop">A Powerful Core Framework</h4>
			<p class="rt-text-small">Standard array of features and capabilities.</p>
		</div>
	</div>

	<div class="gantry-width-25 box4">
		<div class="gantry-width-spacer">
			<p class="rt-text-small largepaddingtop medmarginbottom">Module Suffixes</p>
			<h4 class="rt-text-white nomargintop">Individualize Modular Content</h4>
			<p class="rt-text-small">Diverse selection of stylistic module suffixes.</p>
		</div>
	</div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting             |
| :----------         | :----------         |
| Module Class Suffix | `fp-content-top-a2` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
