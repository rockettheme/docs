---
title: Tessellate: Recreating the Demo - RokAjaxSearch
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

RokAjaxSearch
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting         |
| :---------- | :----------     |
| Title       | `RokAjaxSearch` |
| Show Title  | Show            |
| Position    | feature-b       |
| Status      | Published       |
| Access      | Public          |

### Custom Output

~~~ .html
<h3>Full<span class="hidden-tablet"> Joomla</span> site search, powered by AJAX</h3>

<p>RokAjaxSearch uses AJAX to display Joomla site search results via a popup modal as you type, without the need for refreshing the page or being directed to a separate search page.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon5">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                     |
| :----------         | :----------                 |
| Module Class Suffix | `fp-feature-b2 title2 box4` |

[demo]: assets/demo_10.jpeg
[demo2]: assets/demo_10a.jpeg
[demo3]: assets/demo_10b.jpeg
[demo4]: assets/demo_10c.jpeg
