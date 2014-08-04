---
title: Tessellate: Recreating the Demo - About Tessellate
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

About Tessellate
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting            |
| :---------- | :----------        |
| Title       | `About Tessellate` |
| Show Title  | Show               |
| Position    | showcase-a         |
| Status      | Published          |
| Access      | Public             |

### Custom Output

~~~ .html
<img src="images/rocketlauncher/home/fp-showcase-a/img-01.jpg" alt="image" />

<h3>Configurable HTML5 Animated Header</h3>

<p class="hidden-tablet"><span><span class="visible-large">No videos, no flash, no animated GIFs... no nonsense.</span> Using <span class="visible-large">the power of </span>HTML5 Canvas and WebGL (browser dependent), the animated header can be created dynamically<span class="visible-large"> through a script</span> with configurable colors<span class="visible-large"> and styles</span></span>.</p>

<p class="visible-tablet">HTML5 Canvas powered animated header.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a> 
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                |
| :----------         | :----------            |
| Module Class Suffix | `fp-showcase-a title1` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
