---
title: Nuance: Recreating the Demo - FP Header C
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

FP Header C
-----


![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting       |
| :---------- | :----------   |
| Title       | `FP Header C` |
| Show Title  | Hide          |
| Position    | header-c      |
| Status      | Published     |
| Access      | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<span class="rt-floatleft"><img src="images/rocketlauncher/home/fp-header/img-01.jpg" alt="image"></span>
<span class="rt-floatright hidden-tablet"><i class="fa fa-chevron-down"></i></span>
<span>
    <small><span class="hidden-tablet">Template by</span><span class="visible-tablet">By</span></small><br />
    <span>RocketTheme<span class="hidden-tablet"> LLC</span></span>
</span> 
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
| Module Class Suffix | `fp-header-c` |

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_5b.jpg
[demo4]: assets/demo_2b.jpeg