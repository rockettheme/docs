---
title: Tachyon: Recreating the Demo - New Features
description: Your Guide to Recreating Elements of the Tachyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tachyon:Tachyon

---

New Features
-----

![][demo]

:   1. **mod_custom** [33%, 52%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `New Features`   |  
| Show Title | Show             |  
| Position   | content-bottom-b |  
| Status     | Published        |  
| Access     | Public           |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<ul class="bullet-check">
  <li><strong>Splicemenu:</strong> New dropline menu option with javascript animations and enhancements.</li>
  <li><strong>RokMiniEvents:</strong> New module which syncs with your Google Calendar events.</li>
</ul>
<a href="index.php?option=com_content&view=article&id=1&Itemid=104" class="readon"><span>Read More</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                       |  
| :------------------ | :---------------------------- |  
| Module Class Suffix | `box1 button2 nomarginbottom` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
