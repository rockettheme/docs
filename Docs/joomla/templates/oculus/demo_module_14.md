---
title: Oculus: Recreating the Demo - Top Features
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

Top Features
-----

![][demo]

:	1. **mod_custom** [17%, 51%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `Top Features` |  
| Show Title | Show           |  
| Position   | footer-c       |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">RokSprocket</a> is a powerful, switchblade content display extension.</p>
<p class="rt-tag">Multiple Layouts</p>

<p class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">RokNavMenu</a> is the core menu extension behind Dropdown Menu.</p>
<p class="rt-tag">Core Navigation</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `fp-footer hidden-phone` |  

[demo]: assets/demo_module_9.jpeg
[demo2]: assets/top_1.jpeg
[demo3]: assets/top_2.jpeg
[demo4]: assets/top_3.jpeg