---
title: Corvus: Recreating the Demo - The Big Story
description: Your Guide to Recreating Elements of the Corvus Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

The Big Story
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting         |  
| :---------------- | :-------------- |  
| Title             | `The Big Story` |  
| Show Title        | Show            |  
| Position          | feature-a       |  
| Status            | Published       |  
| Access            | Public          |  
| Language          | All             |  
| Note              | Blank           |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span class="rt-expanded-1"><span>The Big <a href="#">Story</a></span></span>
<span class="rt-expanded-2"><span>Multiple Layouts<span class="hidden-tablet">, Powered by RokSprocket</span></span></span>
<span class="rt-expanded-3"><a class="readon" href="#">Read More</a></span>
<div class="clear"></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                |  
| :------------------ | :--------------------- |  
| Module Class Suffix | `feature hidden-phone` |

[demo]: assets/demo_3.jpeg
[demo2]: assets/story_1.jpeg
[demo3]: assets/story_2.jpeg
[demo4]: assets/story_3.jpeg