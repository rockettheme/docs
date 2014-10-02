---
title: Oculus: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

FP Footer A
-----

![][demo]

:	1. **mod_custom** [17%, 6%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting       |  
| :--------- | :------------ |  
| Title      | `FP Footer A` |  
| Show Title | Hide          |  
| Position   | footer-a      |  
| Status     | Published     |  
| Access     | Public        |  
| Language   | All           |  
| Note       | Blank         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-footer-logo"></div>

<span>All demo content is for <strong>sample</strong> purposes only<span class="visible-large">, intended to show a live site</span>. <span class="hidden-tablet">Use the <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115"><strong>RocketLauncher</strong></a> for demo replication.</span> All images are copyrighted to their respective owners.</span>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_module_9.jpeg
[demo2]: assets/footer_1.jpeg
[demo3]: assets/footer_2.jpeg
[demo4]: assets/footer_3.jpeg