---
title: Ximenia: Recreating the Demo - Core Gantry Framework
description: Your Guide to Recreating Elements of the Ximenia Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ximenia:Ximenia

---

Core Gantry Framework
-----
![][demo]

:   1. **mod_custom** [50%, 52%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `Core Gantry Framework`  |  
| Show Title | Show                     |  
| Position   | content-top-b            |  
| Status     | Published                |  
| Access     | Public                   |  
| Language   | All                      |  
| Note       | Blank                    |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-image rt-floatleft smallmargintop largemarginbottom">
  <img class="rt-image" src="images/rocketlauncher/frontpage/general/content-top-4.jpg" width="99" height="92" alt="image" />
</div>

<p class="smallmargintop"><strong>Gantry provides all major features and functions in the template</strong>, inclusive of the rich, user friendly administrator, the 960 Grid System, iPhone / Android support and more.</p>

<p class="rt-center nomarginbottom"><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108"><span>See More</span></a></p>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `center` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/gantry_1.jpeg
[demo3]: assets/gantry_2.jpeg
[demo4]: assets/gantry_3.jpeg