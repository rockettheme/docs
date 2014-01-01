---
title: Visage: Recreating the Demo - Content Bottom A
description: Your Guide to Recreating Elements of the Visage Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/visage:Visage

---

Content Bottom A
-----

![][demo]

:   1. **mod_custom** [19%, 8%, se]

This area of the front page is a series of two **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the first module in this set.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                     |  
| :--------- | :-------------------------- |  
| Title      | `FP CTB A`                  |  
| Show Title | Hide                        |  
| Position   | content-bottom-a            |  
| Status     | Published                   |  
| Access     | Public                      |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p><strong>Fusion with MegaMenu</strong>, is a javascript enhanced CSS <strong>dropdown</strong> menu, with configurable features such as <strong>menu icons</strong>.</p>
<a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115" class="readon"><span>Read More</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting      |  
| :------------------ | :----------- |  
| Module Class Suffix | `box2 icon1` |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/ctba_1.jpeg
[demo3]: assets/ctba_2.jpeg
[demo4]: assets/ctba_3.jpeg