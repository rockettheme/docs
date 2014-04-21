---
title: Syndicate: Recreating the Demo - World Map
description: Your Guide to Recreating Elements of the Syndicate Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/syndicate:Syndicate

---

World Map
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting       |
| :--------- | :------------ |
| Title      | `World Map`   |
| Show Title | Show          |
| Position   | footer-c      |
| Status     | Published     |
| Access     | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="worldmap">
<a href="#" class="location one"><span>N. America</span></a>
<a href="#" class="location two"><span>S. America</span></a>
<a href="#" class="location three"><span>Europe</span></a>
<a href="#" class="location four"><span>Asia</span></a>
<a href="#" class="location five"><span>Africa</span></a>
<a href="#" class="location six"><span>Australia</span></a>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting    |
| :------------------ | :--------- |
| Module Class Suffix |            |

[demo]: assets/demo_11.jpeg
[demo2]: assets/demo_11a.jpeg
[demo3]: assets/demo_11b.jpeg
[demo4]: assets/demo_11c.jpeg
