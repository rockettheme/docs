---
title: Panacea: Recreating the Demo - Background Rotator
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

Background Rotator
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |
| :--------- | :------------------  |
| Title      | `Background Rotator` |
| Show Title | Show                 |
| Position   | feature-a            |
| Status     | Published            |
| Access     | Public               |

### Custom Output

~~~ .html
<img src="images/stories/demo/frontpage/feature1.jpg" alt="image" class="feature-img" width="101" height="69" />
<p>A Gantry controlled backgorund image and content rotator, for the sub-header area.</p>
[readon2 url="index.php?option=com_content&amp;view=article&amp;id=35&amp;Itemid=108"]Learn More[/readon2]
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |
| :------------------ | :------ |
| Module Class Suffix | `box1`  |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
