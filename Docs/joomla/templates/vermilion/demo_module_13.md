---
title: Vermilion: Recreating the Demo - Sample Pages
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

Sample Pages
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `Sample Pages` |
| Show Title  | Hide           |
| Position    | footer-b       |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-icon-badge rt-badge-left"><a href="#"><span class="fa fa-copy"></span></a></div>
<h2 class="title"><a href="#">Sample Pages</a></h2>
<p>See a range of example pages and layouts, that are possible with the Vermilion template.</p>
<div class="clear"></div>
<div class="gantry-row">
	<div class="gantry-width-100">
		<div class="gantry-width-spacer">
			<form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
				<input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
				<input type="hidden" value="rocketthemeblog" name="uri" />
				<input type="hidden" name="loc" value="en_US" />
				<input type="submit" name="Submit" class="readon" value="Join" />
			</form>
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

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `fp-footer-b` |

[demo]: assets/demo_13.jpeg
[demo2]: assets/demo_13a.jpeg
[demo3]: assets/demo_13b.jpeg
[demo4]: assets/demo_13c.jpeg
