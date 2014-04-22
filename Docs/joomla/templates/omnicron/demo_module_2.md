---
title: Omnicron: Recreating the Demo - System Requirements
description: Your Guide to Recreating Elements of the Omnicron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

System Requirements
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting               |
| :--------- | :-----------------    |
| Title      | `System Requirements` |
| Show Title | Show                  |
| Position   | sidebar-a             |
| Status     | Published             |
| Access     | Public                |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>The following are required for Omnicron to operate fully:</p>

<ul class="bullet-check">
  <li>Joomla 1.5.x <em>(latest version)</em></li>  
  <li>Gantry v3.0.10 <em>or higher</em></li>
  <li>PHP 5.2 <em>or higher</em></li>  
  <li>RokNavMenu Module</li>
</ul>
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
| Module Class Suffix | `box2 title2`  |

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
