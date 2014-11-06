---
title: Somaxiom: Recreating the Demo - Demo Information
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

Demo Information
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |      Setting       |
| :--------- | :----------------- |
| Title      | `Demo Information` |
| Show Title | Show               |
| Position   | footer-a           |
| Status     | Published          |
| Access     | Public             |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>All demo content is for demo <strong>purposes</strong> only, to show an example of a <strong>live site</strong>. All images are the copyright of their respective owners.</p>
[readon url="index.php?option=com_content&view=article&id=1&Itemid=110"]More Information[/readon]
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

[demo]: assets/demo_10.jpeg
[demo2]: assets/demo_9a.jpeg
[demo3]: assets/demo_9b.jpeg
[demo4]: assets/demo_9c.jpeg