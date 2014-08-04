---
title: Tessellate: Recreating the Demo - FP Feature A
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

FP Feature A
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP Feature A` |
| Show Title  | hide           |
| Position    | feature-a      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

~~~ .html
<h3>Multiple layout options: An adapted responsive layout, or fixed layouts at 960px or 1200px wide</h3>

<p class="smallmarginbottom">A responsive layout adapts automatically to the viewing device's width, such as mobile, tablet or desktop, without the need for a separate layout or content. Mobile modes have a unique menu to aid usability. 960px and 1200px fixed layout options are also available.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a>

<h3 class="largemargintop largepaddingtop">Configure the style options of Tessellate, quickly and easily, in the template manager settings</h3>

<p class="smallmarginbottom">Tessellate has an extensive Color Chooser in the template manager to provide intricate controls for each section, inclusive of overlay type, text color, background color, as well as accent colors. Edit preexisting or create new presets.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a>

<h3 class="largemargintop largepaddingtop">A web font based solution for adding icons, allowing them to be extensively styled via CSS</h3>

<p class="smallmarginbottom">The template features an updated library for Font Awesome with version 4+. This offers over 350 icons, which are fully scalable and easy to integrate into the design of the template and/or content, from module titles to inside content items themselves.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114" class="readon4">Read More</a>
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

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
