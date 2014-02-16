---
title: Modulus: Recreating the Demo - FP Footer C
description: Your Guide to Recreating Elements of the Modulus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/modulus:Modulus

---

FP Footer C
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                 |  
| :--------- | :---------------------- |  
| Title      | `FP Footer C`           |  
| Show Title | Hide                    |  
| Position   | footer-c                |  
| Status     | Published               |  
| Access     | Public                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="attention nomarginbottom">
    <em class="bold">DEMO NOTICE:</em> All demo content is for sample purposes only, intended to represent a live site. Download a launcher pack to copy the demo.
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

| Option              | Setting                                |  
| :------------------ | :------------------------------------- |  
| Module Class Suffix | `flushbottom nomarginbottom fp-notice` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/footerc_1.jpeg
[demo3]: assets/footerc_2.jpeg
[demo4]: assets/footerc_3.jpeg