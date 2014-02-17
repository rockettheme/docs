---
title: Reflex: Recreating the Demo - FP Sidebar A
description: Your Guide to Recreating Elements of the Reflex Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reflex:Reflex

---

FP Sidebar A
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP Sidebar A`     |  
| Show Title | Hide               |  
| Position   | sidebar-a          |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<h2 class="title largemargintop">Video Documentation</h2>
<span class="desc">Introduction to RokGallery.</span>
<img src="images/stories/launcher/video1.jpg" alt="image" />
<p><strong>RokGallery</strong>, is a new gallery extension, with flexible, <strong>modern</strong> and powerful features. Introduce yourself to the basics with this <strong>short video</strong>.</p>
<a href="http://www.rockettheme.com/extensions-joomla/rokgallery" class="readon"><span>Learn More</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                     |  
| :------------------ | :------------------------------------------ |  
| Module Class Suffix | `fp-feature nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/sidebara_1.jpeg
[demo3]: assets/sidebara_2.jpeg
[demo4]: assets/sidebara_3.jpeg
