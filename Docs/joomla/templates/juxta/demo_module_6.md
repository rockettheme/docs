---
title: Juxta: Recreating the Demo - Demonstrative Site
description: Your Guide to Recreating Elements of the Juxta Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/juxta:Juxta

---

Demonstrative Site
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting                                                               |
| :---------- | :----------                                                           |
| Title       | `Demonstrative Site for the Theme which Intends to Mimic a Live Site` |
| Show Title  | Show                                                                  |
| Position    | footer-a                                                              |
| Status      | Published                                                             |
| Access      | Public                                                                |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>All demo content is for demo <strong>purposes</strong> only, to show an example of a <strong>live site</strong>. All images are the copyright of their respective owners.</p>
[readon url="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108"]More Information[/readon]
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
| Module Class Suffix | `title1`    |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
