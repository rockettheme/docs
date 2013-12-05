---
title: Afterburner2: Recreating the Demo - Module Variations
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Module Variations
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Module Variations` |  
| Show Title | Show                |  
| Position   | sidebar-a           |  
| Status     | Published           |  
| Access     | Public              |  
| Language   | All                 |  
| Note       | Blank               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>Several module class suffixes come with the template. box1 is the singular style suffix, which is applied to the current module. Others are structural, that allow you to change the margins/paddings of the module.</p>
<a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=104" class="readon"><span>Read More</span></a>
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
| Module Class Suffix | `box1`  |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/variations_1.jpeg
[demo3]: assets/variations_2.jpeg
[demo4]: assets/variations_3.jpeg