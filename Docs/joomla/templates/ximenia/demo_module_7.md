---
title: Ximenia: Recreating the Demo - RokSprocket Layouts
description: Your Guide to Recreating Elements of the Ximenia Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ximenia:Ximenia

---

RokSprocket Layouts
-----
![][demo]

:   1. **mod_custom** [10%, 52%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `RokSprocket Layouts`  |  
| Show Title | Show                   |  
| Position   | content-top-b          |  
| Status     | Published              |  
| Access     | Public                 |  
| Language   | All                    |  
| Note       | Blank                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span class="icon-th fp-icon"></span>

<h4 class="nomargintop largepaddingtop"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113"><em>RokSprocket is a revolutionary content extension</em></a></h4>

<div class="clear"></div>

<p><strong>RokSprocket</strong> has support for numerous content layout types, these as <strong>Mosaic,</strong> Headlines, Tabs and Features, as shown on this frontpage and <a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">subpages</a>.</p>

<p class="rt-center nomarginbottom"><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113"><span>See More</span></a></p>
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
| Module Class Suffix | `title1` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/layouts_1.jpeg
[demo3]: assets/layouts_2.jpeg
[demo4]: assets/layouts_3.jpeg