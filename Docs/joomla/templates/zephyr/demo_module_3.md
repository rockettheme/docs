---
title: Zephyr: Recreating the Demo - Fusion with MegaMenu
description: Your Guide to Recreating Elements of the Zephyr Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/zephyr:Zephyr

---

Fusion with MegaMenu
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |
| :--------- | :--------------------- |
| Title      | `Fusion with MegaMenu` |
| Show Title | Hide                   |
| Position   | content-top-a          |
| Status     | Published              |
| Access     | Public                 |

### Custom Output

~~~ .html
<div class="image-block-surround floatright">
    <img width="150" height="122" class="image-block" alt="image" src="images/stories/demo/frontpage/roktabs-example1.jpg" /><br /><br />
<a href="index.php?option=com_content&amp;view=article&amp;id=86&amp;Itemid=167" class="readon rt-fusion-readon"><span>More Information</span></a>
</div>

<div class="module-title"><h2 class="title">Fusion with MegaMenu</h2></div>

<p>In Zephyr, Fusion Menu has been extended with the following features:</p>

<ul class="bullet-check">
    <li>Triple / Quad Column Mode</li>
    <li>Child Items Menu Grouping</li>
    <li>Column Width Control</li>
    <li>Load Modules / Positions in Items</li>
</ul>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting               |
| :------------------ | :-------------        |
| Module Class Suffix | `box8 nomarginbottom` |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
