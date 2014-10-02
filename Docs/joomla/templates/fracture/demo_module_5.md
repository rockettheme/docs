---
title: Fracture: Recreating the Demo - Top Features
description: Your Guide to Recreating Elements of the Fracture Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fracture:Fracture

---

Top Features
-----
![][demo]

:   1. **mod_custom** [20%, 36%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Top Features.`  |  
| Show Title | Show             |  
| Position   | footer-b         |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113"><em class="bold">Responsive Layout:</em></a> Based on Twitter's Bootstrap Framework, with its collection of utility classes, to provide a flexible structure.</p>

<p><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113"><em class="bold">More with LESS.</em></a> Built-in LESS CSS compilation increased performance whilst making CSS development easier and intuitive.</p>

<a class="readon" href="http://www.gantry-framework.org/documentation/joomla/basics/key-features" target="_blank"><span>More Features</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                          |  
| :------------------ | :------------------------------- |  
| Module Class Suffix | `title2 icon-heart hidden-phone` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/top_1.jpeg
[demo3]: assets/top_2.jpeg
[demo4]: assets/top_3.jpeg