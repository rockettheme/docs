---
title: Reflex: Recreating the Demo - About the Photography
description: Your Guide to Recreating Elements of the Reflex Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reflex:Reflex

---

About the Photography
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                 |  
| :--------- | :---------------------- |  
| Title      | `About the Photography` |  
| Show Title | Show                    |  
| Position   | footer-a                |  
| Status     | Published               |  
| Access     | Public                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rg-gm-slice floatleft"><img width="96" height="96" src="images/stories/launcher/photo1.jpg" alt="Image" /></div>
<p>My galleries mainly feature images from my favourite destinations in <a href="#">the Americas and Europe</a>, featuring spectacular landscapes.</p>
<a href="#" class="readon"><span>Contact Details</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                                        |  
| :------------------ | :--------------------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom nopaddingleft` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/footera_1.jpeg
[demo3]: assets/footera_2.jpeg
[demo4]: assets/footera_3.jpeg