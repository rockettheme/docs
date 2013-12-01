---
title: Paradigm: Recreating the Demo - Build Your Own Site
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Build Your Own Site
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                     |  
| :--------- | :------------------------------------------ |  
| Title      | `Build Your Own Site Using Paradigm Today.` |  
| Show Title | Hide                                        |  
| Position   | extension-a                                 |  
| Status     | Published                                   |  
| Access     | Public                                      |  
| Language   | All                                         |  
| Note       | Blank                                       |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="largemargintop largepaddingtop">
	<a href="#" class="readon rt-uppercase">Purchase Theme</a>
</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-extension rt-center`   |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/build_1.jpeg
[demo3]: assets/build_2.jpeg
[demo4]: assets/build_3.jpeg