---
title: Juxta: Recreating the Demo - Six Style Variations
description: Your Guide to Recreating Elements of the Juxta Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/juxta:Juxta

---

Six Style Variations
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |
| :--------- | :-----------------     |
| Title      | `Six Style Variations` |
| Show Title | Show                   |
| Position   | showcase-a             |
| Status     | Published              |
| Access     | Public                 |

### Custom Output

~~~ .html
<div class="showcase-image-surround"><img src="images/stories/demo/frontpage/showcase1.jpg" alt="image" /><div class="showcase-image"></div></div>
<p>An array for <strong>six diverse</strong>, professionally created style variations. Chose from different graphic <strong>levels</strong> to radically change the template visuals.</p>
[readon url="index.php?option=com_content&amp;view=article&amp;id=16&amp;Itemid=135"]Learn More[/readon]
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting        |
| :------------------ | :------------- |
| Module Class Suffix | `flag1`        |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
