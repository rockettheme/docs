---
title: Plethora: Recreating the Demo - About Plethora
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

About Plethora
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting          |
| :---------- | :----------      |
| Title       | `About Plethora` |
| Show Title  | Show             |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">RocketLauncher<span class="hidden-tablet"> Package</span></a></h4>
<p class="rt-text-small nomarginbottom">Quickly demo replication</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">Editable <span class="hidden-tablet">PNG </span>Sources</a></h4>
<p class="rt-text-small nomarginbottom">Adobe&reg; Fireworks PNG Sources</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#"><span class="hidden-tablet">Free </span>Documentation</a></h4>
<p class="rt-text-small nomarginbottom">Online and publicly available</p>
<hr class="clear" />

<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">Integrated Addons</a></h4>
<p class="rt-text-small nomarginbottom">Free &amp; GPL RokExtensions</p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting              |
| :----------         | :----------          |
| Module Class Suffix | `title1 fp-footer-a` |

[demo]: assets/demo_13.jpeg
[demo2]: assets/demo_13a.jpeg
[demo3]: assets/demo_13b.jpeg
[demo4]: assets/demo_13c.jpeg
