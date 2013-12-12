---
title: Oculus: Recreating the Demo - Oculus Demo
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

Oculus Demo
-----

![][demo1]

We used a **mod_custom** module to make up the content in the **footer-b** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                          |  
| :--------- | :----------------------------------------------- |  
| Title      | `[span class="hidden-tablet"]Oculus [/span]Demo` |  
| Show Title | Show                                             |  
| Position   | sidebar-b                                        |  
| Status     | Published                                        |  
| Access     | Public                                           |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>RocketLauncher installs a replica of the demo.</p>

<p class="fp-sidebar-b-img"><img class="rt-image" src="images/rocketlauncher/frontpage/sidebar/img7.jpg" alt="image" /></p>

<a class="readon" href="#">Read More</a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |  

### Advanced
![][demo4]

| Option              | Setting                                                            |  
| :------------------ | :----------------------------------------------------------------- |  
| Module Class Suffix | `box4 icon-copy rt-horizontal-gradient nomarginright hidden-phone` |  

[demo2]: assets/oculusdemo_1.jpeg
[demo3]: assets/oculusdemo_2.jpeg
[demo4]: assets/oculusdemo_3.jpeg
[demo1]: assets/demo_module_8.jpeg
