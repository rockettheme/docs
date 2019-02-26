---
title: Vermilion: Recreating the Demo - Demo Info
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

Demo Info
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Demo Info` |
| Show Title  | Hide        |
| Position    | footer-a    |
| Status      | Published   |
| Access      | Public      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-icon-badge rt-badge-left"><a href="#"><span class="fa fa-edit"></span></a></div>
<h2 class="title"><a href="#">Demo Info</a></h2>
<p>All demo content is for sample purpose only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.</p>
<p>Please use the <a href="http://www.rockettheme.com/joomla/templates/vermilion">Vermilion RocketLauncher</a> to install an equivalent of the demo.</p>
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

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `fp-footer-a` |

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_12a.jpeg
[demo3]: assets/demo_12b.jpeg
[demo4]: assets/demo_12c.jpeg
