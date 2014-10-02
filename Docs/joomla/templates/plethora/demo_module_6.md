---
title: Plethora: Recreating the Demo - FP Feature A
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

FP Feature A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP Feature A` |
| Show Title  | Hide           |
| Position    | feature-a      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-image-group">
	<div class="rt-image-block">
		<div class="rt-image-item">
			<img src="images/rocketlauncher/home/fp-feature-a/img-01.jpg" alt="image" />
		</div>
		<div class="rt-image-tag">
			<span>Free Extension</span>
		</div>
		<div class="rt-image-content">
			<div class="rt-image-title">
				<span>RokSprocket<span class="hidden-tablet"> is a powerful, switchblade content extension</span>.</span>
			</div>		
			<div class="rt-image-desc">
				<p>RokSprocket is a multi-purposes content extension, with a custom, advanced and intuitive user interface<span class="hidden-tablet">, as well as several layout modes with numerous themes</span>.</p>
				<a href="#">Read the whole story <i class="fa fa-angle-double-right"></i></a>
			</div>				
		</div>	
	</div>	
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

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `fp-feature-a` |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
