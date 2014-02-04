---
title: Visage: Recreating the Demo - 12 Preset Styles
description: Your Guide to Recreating Elements of the Visage Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/visage:Visage

---

12 Preset Styles
-----

![][demo]

This area of the front page is a series of four **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the first module in this set, **FP Feature A**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `12 Preset Styles` |  
| Show Title | Show               |  
| Position   | sidebar-a          |  
| Status     | Published          |  
| Access     | Public             |  
| Language   | All                |  
| Note       | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>A selection of twelve configurable style variations, each with stunning, sophisticated and refined graphics.</p>
<a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117" class="readon"><span>More Information</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting          |  
| :------------------ | :--------------- |  
| Module Class Suffix | `box1 rt-center` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/twelve_1.jpeg
[demo3]: assets/twelve_2.jpeg
[demo4]: assets/twelve_3.jpeg