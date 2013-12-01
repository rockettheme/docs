---
title: Hexeris: Recreating the Demo - FP Utility
description: Your Guide to Recreating Elements of the Hexeris Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

FP Utility
-----
![][demo]

:   1. **FP Utility** [70%, 20%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | FP Utility         |  
| Show Title        | Hide               |  
| Position          | utility-a          |  
| Status            | Published          |  
| Access            | Public             |  
| Language          | All                |  
| Note              | Blank              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span>A multi-faceted content display module...</span>
<a href="#" class="readon">Read More</a>
<div class="clear"></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                    |  
| :------------------ | :----------------------------------------- |  
| Module Class Suffix | `box6 fp-utility nomargintop hidden-phone` |

[demo]: assets/demo_2.jpeg
[demo2]: assets/utility_1.jpeg
[demo3]: assets/utility_2.jpeg
[demo4]: assets/utility_3.jpeg