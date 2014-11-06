---
title: Somaxiom: Recreating the Demo - Two Menu Systems
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

Two Menu Systems
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |      Setting       |
| :--------- | :----------------- |
| Title      | `Two Menu Systems` |
| Show Title | Show               |
| Position   | feature-a          |
| Status     | Published          |
| Access     | Public             |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="fp-feature">
  <img src="images/stories/demo/frontpage/feature-a1.jpg" width="80" height="75" alt="Feature Image" class="floatleft fp-image" />
  <p>
    <strong>Fusion:</strong> advanced mootools / javascript powered CSS dropdown menu system.
    [readon2 url="index.php?option=com_content&view=article&id=13&Itemid=162"]Read More[/readon2]
    <span class="clear"></span>
  </p>
  
  <img src="images/stories/demo/frontpage/feature-a2.jpg" width="80" height="75" alt="Feature Image" class="floatleft fp-image" />
  <p>
    <strong>Splitmenu:</strong> places children below the main menu bar, then others in the side column.
    [readon2 url="index.php?option=com_content&view=article&id=13&Itemid=162"]Read More[/readon2]
    <span class="clear"></span>
  </p>
</div>

~~~

### Options

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       | Setting |
| :------------------ | :------ |
| Module Class Suffix | `tab1`  |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg