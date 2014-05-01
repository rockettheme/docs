---
title: Vermilion: Recreating the Demo - FP Utility
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

FP Utility
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `FP Utility` |
| Show Title  | Hide         |
| Position    | utility-a    |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<h2 class="title"><a href="#">Animate &amp; Innovate</a></h2>
<p>Vermilion is bursting with animation extras to add <span class="hidden-tablet">character and </span>depth<span class="visible-large"> to your site</span>.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                      |
| :----------         | :----------                  |
| Module Class Suffix | `fp-utility rt-phone-center` |

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
