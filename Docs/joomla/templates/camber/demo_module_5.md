---
title: Camber: Recreating the Demo - RokGallery Extension
description: Your Guide to Recreating Elements of the Camber Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Camber:Camber

---

RokGallery Extension
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `RokGallery Extension` |  
| Show Title | Show                   |  
| Position   | mainbottom-b           |  
| Status     | Published              |  
| Access     | Public                 |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="smallmarginbottom"><strong>Custom Tag-Based Architecture</strong></p>
<div class="rt-articleinfo smallmarginbottom"></div>
<p>RokGallery is an advanced gallery, with non-destructive slice editing, and other features typically associated with native apps.</p>
<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112"><span>Read More</span></a>
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
| Module Class Suffix | `box1 title1 rt-center` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/extension_1.jpeg
[demo3]: assets/extension_2.jpeg
[demo4]: assets/extension_3.jpeg