---
title: Kirigami: Recreating the Demo - Inside Kirigami
description: Your Guide to Recreating Elements of the Kirigami Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kirigami:Kirigami

---

Inside Kirigami
-----
![][demo]

:   1. **mod_custom** [20%, 36%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Inside Kirigami`  |  
| Show Title | Show               |  
| Position   | footer-b           |  
| Status     | Published          |  
| Language   | All                |  
| Note       | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=102"><em class="bold">Features</em></a></div>
<div class="smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=103"><em class="bold">Module Positions</em></a></div>
<div class="smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=104"><em class="bold">Module Variations</em></a></div>
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
| Module Class Suffix |         |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/inside_1.jpeg
[demo3]: assets/inside_2.jpeg
[demo4]: assets/inside_3.jpeg