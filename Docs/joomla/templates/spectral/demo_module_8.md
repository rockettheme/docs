---
title: Spectral: Recreating the Demo - FP Footer Demo
description: Your Guide to Recreating Elements of the Spectral Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/spectral:Spectral

---

FP Footer Demo
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `FP Footer Demo Info` |  
| Show Title | Hide        |  
| Position   | footer-a    |  
| Status     | Published   |  
| Language   | All         |  
| Note       | Blank       |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-footer-logo"></div>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="#">Spectral RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `fp-footer-demo-info` |  

[demo]: assets/demo_14.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg