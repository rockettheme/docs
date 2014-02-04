---
title: Camber: Recreating the Demo - Demo Information
description: Your Guide to Recreating Elements of the Camber Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Camber:Camber

---

Demo Information
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                    |  
| :--------- | :------------------------- |  
| Title      | `Demo Information`         |  
| Show Title | Show                       |  
| Position   | footer-b                   |  
| Status     | Published                  |  
| Access     | Public                     |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom">
<em class="bold">DEMO NOTICE:</em> All demo content is for sample purposes only, intended to represent a live site. RokGallery images are licensed from <a target="_blank" href="http://www.bigstockphoto.com/">BigStockPhoto</a> and are for use on THIS DEMO SITE ONLY.
</p>
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
| Module Class Suffix | `nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg