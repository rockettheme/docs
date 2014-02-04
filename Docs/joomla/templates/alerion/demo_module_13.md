---
title: Alerion: Recreating the Demo - Floating
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Floating
-----

![][demo]

:	1. **mod_custom** [40%, 37%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Floating`  |  
| Show Title | Show        |  
| Position   | extension-b |  
| Status     | Published   |  
| Access     | Public      |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Configure floating modules to 'bounce' between the template sections. Choose an end position in the template manager. The QuickNav feature also 'bounces' between all sections.</p>

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `title2 largemargintop hidden-phone` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/float_1.jpeg
[demo3]: assets/float_2.jpeg
[demo4]: assets/float_3.jpeg