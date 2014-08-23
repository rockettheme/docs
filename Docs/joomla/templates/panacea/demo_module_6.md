---
title: Panacea: Recreating the Demo - Template Optimization
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

Template Optimization
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                 |
| :--------- | :---------------        |
| Title      | `Template Optimization` |
| Show Title | Show                    |
| Position   | mainbottom-b            |
| Status     | Published               |
| Access     | Public                  |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>Template <strong>performance</strong> is a key part of the development process, to ensure that the theme is as <strong>optimized</strong> as possible.</p>

<div class="rt-grid-2">
    <ul class="bullet-check">
        <li>Valid XHTML</li>
        <li>Valid CSS 3</li>
        <li>Low Image Count</li>
    </ul>
</div>
<div class="rt-grid-2">
    <ul class="bullet-check">
        <li>Compressed CSS</li>
        <li>Optimized Images</li>
        <li>Inbuilt Caching</li>
    </ul>
</div>
<div class="clear"></div>

[readon2 url="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107"]Learn More[/readon2]
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | Yes         |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `box1`      |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
