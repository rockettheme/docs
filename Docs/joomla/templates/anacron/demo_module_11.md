---
title: Anacron: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Anacron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Anacron:Anacron

---

FP Footer A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `FP Footer A`  |  
| Show Title | Hide           |  
| Position   | footer-a       |  
| Status     | Published      |  
| Access     | Public         |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<span class="rt-icon"><span class="icon-info-sign"></span></span>
<span class="rt-footer-logo"></span>
<p>All demo content is for sample purposes only, intended to show a live site. All images are licensed from ShutterStock for exclusive use on this demo site only. Use the Anacron RocketLauncher for demo replication.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `fp-footer-a rt-center`  |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/client_1.jpeg
[demo3]: assets/client_2.jpeg
[demo4]: assets/client_3.jpeg