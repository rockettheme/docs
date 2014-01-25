---
title: Camber: Recreating the Demo - Gantry Framework
description: Your Guide to Recreating Elements of the Camber Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Camber:Camber

---

Gantry Framework
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Gantry Framework` |  
| Show Title | Show               |  
| Position   | mainbottom-b       |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>Gantry is a powerful framework at the core of the template, providing a rich array of features:</p>
<ul class="menu">
    <li><a href="#"><span>An advanced and intuitive control panel to easily configure the template.</span></a></li>
    <li><a href="#"><span>Control Gantry settings for each page with per-menu-item configuration.</span></a></li>
    <li><a href="#"><span>Mobile browsing support for the Android and iOS operating systems.</span></a></li>
    <li><a href="#"><span>Ajax article and smart image loading support for improved performance.</span></a></li>
</ul>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting       |  
| :------------------ | :------------ |  
| Module Class Suffix | `nomargintop` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/gantry_1.jpeg
[demo3]: assets/gantry_2.jpeg
[demo4]: assets/gantry_3.jpeg