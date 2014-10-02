---
title: Tessellate: Recreating the Demo - FP Showcase B
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

FP Showcase B
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting         |
| :---------- | :----------     |
| Title       | `FP Showcase B` |
| Show Title  | Hide            |
| Position    | showcase-b      |
| Status      | Published       |
| Access      | Public          |

### Custom Output

~~~ .html
<div class="hidden-tablet">
    <h6><span>CSS-based <span class="visible-large">multi-column </span>dropdown menu system</span></h6>
    <p class="smallmarginbottom hidden-tablet">Features include multiple columns, inline modules and positions, and more.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon4">Read More</a>

    <h6 class="largemargintop largepaddingtop"><span>A static horizontal menu <span class="hidden-large">option</span><span class="visible-large"> with separated child items</span></span></h6>
    <p class="smallmarginbottom hidden-tablet">Parent and subsequent child items are placed in different, configurable positions.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon4">Read More</a>
</div>

<div class="visible-large">
    <h6 class="largemargintop largepaddingtop">Sidepanel or selectbox format for mobile menu</h6>
    <p class="smallmarginbottom">Smartphones viewing Tessellate benefit from a mobile specific menu, for easier browsing.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon4">Read More</a>
</div>

<div class="visible-tablet">
    <h6>CSS-based multi-column dropdown menu system</h6>
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon4">Read More</a>

    <h6 class="largemargintop largepaddingtop">A static horizontal menu with separated child items</h6> 
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon4">Read More</a>   
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

| Option              | Setting         |
| :----------         | :----------     |
| Module Class Suffix | `fp-showcase-b` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
