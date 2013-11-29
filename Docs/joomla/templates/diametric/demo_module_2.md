---
title: Diametric: Recreating the Demo - RokGallery Gallery Extension
description: Your Guide to Recreating Elements of the Diametric Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/diametric:Diametric

---

RokGallery Gallery Extension
-----
![][demo]

:   1. **mod_custom** [20%, 10%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                        |  
| :--------- | :----------------------------- |  
| Title      | `RokGallery Gallery Extension` |  
| Show Title | Show                           |  
| Position   | sidebar-a                      |  
| Status     | Published                      |  
| Access     | Public                         |  
| Language   | All                            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center">
	<p class="nopaddingtop">A gallery solution that uses a custom-tag based architecture and non-destructive editing.</p>
	<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=111"><span>Read More</span></a>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                   |  
| :------------------ | :---------------------------------------- |  
| Module Class Suffix | `title5 icon1 nomargintop nomarginbottom` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/rokgallery_1.jpeg
[demo3]: assets/rokgallery_2.jpeg
[demo4]: assets/rokgallery_3.jpeg