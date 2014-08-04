---
title: Tessellate: Recreating the Demo - Disclaimer
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Disclaimer
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `Disclaimer` |
| Show Title  | Show         |
| Position    | bottom-a     |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<h6>Demo Information</h6>

<p>All demo content is for sample purpose only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.</p>

<p>Please use Tessellate RocketLauncher to install a demo equivalent onto your site.</p>
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
| Module Class Suffix | `fp-bottom-a title2` |

[demo]: assets/demo_17.jpeg
[demo2]: assets/demo_17a.jpeg
[demo3]: assets/demo_17b.jpeg
[demo4]: assets/demo_17c.jpeg
