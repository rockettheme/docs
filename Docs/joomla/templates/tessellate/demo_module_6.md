---
title: Tessellate: Recreating the Demo - FP Showcase C
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

FP Showcase C
-----

![][demo]

:	1. **Custom HTML** [8%, 15%, se]

The image that appears at the top of this section of the front page is a **Custom HTML** module. The smaller images and text box that overlaps this picture are part of a separate **RokSprocket Tabs** module. In order to recreate the effect you see here, you will need to insert the `fp-showcase-c` module class suffix in this module's **Advanced** settings. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting         |
| :---------- | :----------     |
| Title       | `FP Showcase C` |
| Show Title  | Hide            |
| Position    | showcase-c      |
| Status      | Published       |
| Access      | Public          |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<img src="images/rocketlauncher/home/fp-showcase-c/img-01.jpg" alt="image" />
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                                  |
| :----------         | :----------                              |
| Module Class Suffix | `fp-showcase-c nomarginall nopaddingall` |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
