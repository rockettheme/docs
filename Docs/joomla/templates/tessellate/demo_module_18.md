---
title: Tessellate: Recreating the Demo - Info
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Info
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Info`      |
| Show Title  | Show        |
| Position    | bottom-b    |
| Status      | Published   |
| Access      | Public      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">About</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=112">Modules</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=113">Variations</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115">Menu</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Typography</a></li>
</ul>
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
| Module Class Suffix | `fp-bottom-b title2` |

[demo]: assets/demo_18.jpeg
[demo2]: assets/demo_18a.jpeg
[demo3]: assets/demo_18b.jpeg
[demo4]: assets/demo_18c.jpeg
