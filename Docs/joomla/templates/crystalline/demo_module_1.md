---
title: Crystalline: Recreating the Demo - Color Chooser
description: Your Guide to Recreating Elements of the Crystalline Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/crystalline:Crystalline

---

Color Chooser
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |
| :--------- | :------------------ |
| Title      | `Color Chooser`     |
| Show Title | Show                |
| Position   | feature-a           |
| Status     | Published           |
| Access     | Public              |

### Custom Output

~~~ .html
<p><img src="images/stories/demo/frontpage/ft-a.jpg" alt="Mar10 Demo Image" class="demo-fp-img" /></p>
<p>
    <em class="bold">Customize the theme live with the Color Chooser.</em>
    <br />
    Save your custom presets by logging in as a Super Admin.
</p>
[readon2 url="index.php?option=com_content&amp;view=article&amp;id=48&amp;Itemid=155"]Read More[/readon2]
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting       |
| :------------------ | :------       |
| Module Class Suffix | `flushbottom` |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
