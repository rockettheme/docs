---
title: Syndicate: Recreating the Demo - Most Popular Articles
description: Your Guide to Recreating Elements of the Syndicate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/syndicate:Syndicate

---

Most Popular Articles
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                 |
| :--------- | :---------------------- |
| Title      | `Most Popular Articles` |
| Show Title | Show                    |
| Position   | footer-c                |
| Status     | Published               |
| Access     | Public                  |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<ul class="latestnews">
    <li><a href="#">Syndicate is the first template to use the 16 Grid Layout</a></li>
    <li><a href="#">Multiple Logos to choose, in both Light and Dark versions</a></li>
    <li><a href="#">Triple Level Splitmenu for multi-tier site Navigation</a></li>
    <li><a href="#">Fusion with MegaMenu offers many advanced Menu features</a></li>
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

| Option              | Setting    |
| :------------------ | :--------- |
| Module Class Suffix |            |

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_12a.jpeg
[demo3]: assets/demo_12b.jpeg
[demo4]: assets/demo_12c.jpeg
