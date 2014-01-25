---
title: Kirigami: Recreating the Demo - Help Desk
description: Your Guide to Recreating Elements of the Kirigami Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kirigami:Kirigami

---

Help Desk
-----
![][demo]

:   1. **mod_custom** [55%, 36%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Help Desk` |  
| Show Title | Show        |  
| Position   | footer-b    |  
| Status     | Published   |  
| Language   | All         |  
| Note       | Blank       |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=108"><em class="bold">Tutorials &amp; Guides</em></a></div>
<div class="smallmarginbottom"><a href="http://www.rockettheme.com/forum/joomla-template-kirigami&amp;rb_v=viewforum"><em class="bold">Forum Support</em></a></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                     |  
| :------------------ | :-------------------------- |  
| Module Class Suffix | `nopaddingtop hidden-phone` |   

[demo]: assets/demo_6.jpeg
[demo2]: assets/inside_1.jpeg
[demo3]: assets/inside_2.jpeg
[demo4]: assets/inside_3.jpeg