---
title: Radiance: Recreating the Demo - Swift Customizing with Color Chooser
description: Your Guide to Recreating Elements of the Radiance Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Radiance:Radiance

---

Swift Customizing with Color Chooser
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                |  
| :--------- | :------------------------------------- |  
| Title      | `Swift Customizing with Color Chooser` |  
| Show Title | Show                                   |  
| Position   | content-top-a                          |  
| Status     | Published                              |  
| Access     | Public                                 |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<img src="images/stories/demo/frontpage/content1.jpg" alt="image" width="220" height="134" class="rt-fimg1 floatleft"/>
 
<h4 class="nomargintop"><a href="#">A user friendly administrator making preset modification simple.</a></h4>
 
<p>The Color Chooser is a set of template parameters that control the theme's style, varying from text colors, to background colors, overlay types. Additionally, the Radiance release allows you to determine the background image.</p>
 
<a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117" class="readon"><span>Continue Reading</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting   |  
| :------------------ | :-------- |  
| Module Class Suffix | `title1`  |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/contenta_1.jpeg
[demo3]: assets/contenta_2.jpeg
[demo4]: assets/contenta_3.jpeg