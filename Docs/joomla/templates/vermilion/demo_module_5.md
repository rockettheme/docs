---
title: Vermilion: Recreating the Demo - FP MainTop
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

FP MainTop
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `FP MainTop` |
| Show Title  | Hide         |
| Position    | maintop-a    |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-icon-badge"><span class="fa fa-volume-up"></span></div>
<p class="promo2 nomarginbottom">Use over 350 built-in icons for your site content and design</p>
<p class="rt-text-small nomarginbottom">Powered by Font Awesome 4</p>
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
| Module Class Suffix | `fp-maintop rt-center` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
