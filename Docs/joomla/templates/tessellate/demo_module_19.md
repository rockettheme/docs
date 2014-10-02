---
title: Tessellate: Recreating the Demo - Pages
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Pages
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Pages`     |
| Show Title  | Show        |
| Position    | bottom-c    |
| Status      | Published   |
| Access      | Public      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=120">Team</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=122">Pricing</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=123">Portfolio</a></li>
    <li><a href="index.php?option=com_content&amp;view=category&amp;layout=blog&amp;id=13&amp;Itemid=124">Blog</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=13&amp;Itemid=127">Maintenance</a></li>
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
| Module Class Suffix | `fp-bottom-c title2` |

[demo]: assets/demo_19.jpeg
[demo2]: assets/demo_19a.jpeg
[demo3]: assets/demo_19b.jpeg
[demo4]: assets/demo_19c.jpeg
