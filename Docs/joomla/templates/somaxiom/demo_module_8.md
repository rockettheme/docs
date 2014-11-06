---
title: Somaxiom: Recreating the Demo - FP Bottom A
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

FP Bottom A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting    |
| :--------- | :------------ |
| Title      | `FP Bottom A` |
| Show Title | Hide          |
| Position   | bottom-a      |
| Status     | Published     |
| Access     | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="content-mask-surround">
  <img src="images/stories/demo/frontpage/circle1.jpg" alt="image" width="79" height="77" />
  <div class="content-mask"></div>
</div>
<p class="rt-upper rt-center"><a href="index.php?option=com_content&view=article&id=14&Itemid=163"><em class="bold2">PNG Sources</em></a></p>
<p>Adobe&reg; Fireworks PNG <strong>Sources</strong> for <strong>customizing</strong> the template such as the logo or background images.</p>
[readon url="index.php?option=com_content&view=article&id=14&Itemid=163"]Tell Me More[/readon]
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       | Setting |
| :------------------ | :------ |
| Module Class Suffix |         |

[demo]: assets/demo_9.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg