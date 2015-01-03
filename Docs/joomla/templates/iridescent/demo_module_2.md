---
title: Iridescent: Recreating the Demo - FP Top A
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

FP Top A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |  Setting   |
| :--------- | :--------- |
| Title      | `FP Top A` |
| Show Title | Hide       |
| Position   | top-a      |
| Status     | Published  |
| Access     | Public     |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-effect-slide rt-effect-slide-top">
    <img src="images/rocketlauncher/home/fp-top/img-01.jpg" alt="image"/>
    <div class="rt-effect-slide-content">
        <h2 class="rt-uppercase"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=118" class="fp-demo-url">Example Pages</a></h2>
        <p><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=118" class="fp-demo-url">Sample layouts available <span class="hidden-tablet">for replication</span></a></p>
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

|        Option       |  Setting   |
| :------------------ | :--------- |
| Module Class Suffix | `fp-top-a` |

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
