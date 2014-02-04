---
title: Visage: Recreating the Demo - Module Suffixes
description: Your Guide to Recreating Elements of the Visage Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/visage:Visage

---

Module Suffixes
-----

![][demo]

:   1. **mod_custom** [50%, 15%, se]

This area of the front page is a series of two **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the second module in this set, **Module Suffixes**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                              |  
| :--------- | :------------------------------------------------------------------- |  
| Title      | `[title1]Module Suffixes[/title1][title2]Unique Variations[/title2]` |  
| Show Title | Show                                                                 |  
| Position   | sidebar-a                                                            |  
| Status     | Published                                                            |  
| Access     | Public                                                               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="nomarginbottom">A combination of <a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=109">28 module variations</a>, both <strong>stylistic</strong> and structural, to provide a unique and <strong>individual</strong> approach to specific modules.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `title2 nopaddingbottom` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/module_1.jpeg
[demo3]: assets/module_2.jpeg
[demo4]: assets/module_3.jpeg