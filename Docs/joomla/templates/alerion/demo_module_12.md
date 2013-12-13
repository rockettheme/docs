---
title: Alerion: Recreating the Demo - Parallax
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Parallax
-----

![][demo]

:	1. **mod_custom** [40%, 7%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Parallax`  |  
| Show Title | Show        |  
| Position   | extension-a |  
| Status     | Published   |  
| Access     | Public      |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Parallax is apparent motion of a 3D object depending on your perspective. This effect has been transposed into the template, allowing configurable areas to move based on scroll position.</p>

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=10amp;Itemid=117">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                 |  
| :------------------ | :---------------------- |  
| Module Class Suffix | `title2 largemargintop` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/para_1.jpeg
[demo3]: assets/para_2.jpeg
[demo4]: assets/para_3.jpeg