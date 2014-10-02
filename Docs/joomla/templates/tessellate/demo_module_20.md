---
title: Tessellate: Recreating the Demo - Newsletter
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Newsletter
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `Newsletter` |
| Show Title  | Show         |
| Position    | bottom-d     |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Subscribe to our newsletter in order to receive the latest news &amp; articles. We promise we won't spam your inbox!</p>

<form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" class="rt-form-horizontal">
    <input type="text" placeholder="Your Email" class="inputbox" name="email" />
    <input type="hidden" value="rocketthemeblog" name="uri" />
    <input type="hidden" name="loc" value="en_US" />
    <input type="submit" name="Submit" class="readon2" value="Join">
</form>
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
| Module Class Suffix | `fp-bottom-d title2` |

[demo]: assets/demo_20.jpeg
[demo2]: assets/demo_20a.jpeg
[demo3]: assets/demo_20b.jpeg
[demo4]: assets/demo_20c.jpeg
