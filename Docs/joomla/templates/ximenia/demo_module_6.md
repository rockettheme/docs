---
title: Ximenia: Recreating the Demo - Demo Replica
description: Your Guide to Recreating Elements of the Ximenia Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ximenia:Ximenia

---

Demo Replica
-----
![][demo]

:   1. **mod_custom** [10%, 8%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `Fusion with MegaMenu` |  
| Show Title | Show                   |  
| Position   | content-top-a          |  
| Status     | Published              |  
| Access     | Public                 |  
| Language   | All                    |  
| Note       | Blank                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span class="icon-check fp-icon"></span>

<h4 class="nomargintop largepaddingtop"><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112"><em>A CSS based dropdown menu enhanced by Mootools</em></a></h4>

<div class="clear"></div>

<p><strong>Fusion</strong> has many features, inclusive of, but not limited to: Mootools animations, multiple columns, <strong>inline module/positions</strong>, inline subtext and icons.</p>

<p class="rt-center nomarginbottom"><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112"><span>See More</span></a></p>
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
[demo2]: assets/fusion_1.jpeg
[demo3]: assets/fusion_2.jpeg
[demo4]: assets/fusion_3.jpeg