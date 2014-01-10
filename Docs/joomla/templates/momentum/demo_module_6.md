---
title: Momentum: Recreating the Demo - Integrated Extensions
description: Your Guide to Recreating Elements of the Momentum Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/momentum:Momentum

---

Integrated Extensions
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                 |  
| :--------- | :---------------------- |  
| Title      | `Integrated Extensions` |  
| Show Title | Show                    |  
| Position   | content-bottom-a        |  
| Status     | Published               |  
| Access     | Public                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>Choose from an array of <strong>RocketTheme Extensions</strong>, which have integrated template styling support, such as <em>RokNewsPager</em>, <em>RokStories</em> or <em>RokTabs</em>.</p>
<a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=111" class="readon"><span>Read More</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix | `box1`  |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/integrated_1.jpeg
[demo3]: assets/integrated_2.jpeg
[demo4]: assets/integrated_3.jpeg