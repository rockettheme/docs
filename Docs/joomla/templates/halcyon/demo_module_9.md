---
title: Halcyon: Recreating the Demo - Tutorials
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Tutorials
-----

![][demo]

:   1. **mod_custom** [15%, 45%, se]

This area of the front page is a series of three **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the second module in this set, **Tutorials**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Tutorials`          |  
| Show Title | Show                 |  
| Position   | extension-b          |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>Instructions on how to <strong>install</strong> RocketLauncher (demo replica) and the standalone/bundled <strong>template</strong> packages.</p>
<p><a href="index.php?option=com_content&amp;id=7&amp;Itemid=113" class="readon"><span>How to Install</span></a></p>

<p>Guide on how to customize the logo using the <strong>Adobe&reg; Fireworks</strong> PNG Source images.</p>
<a href="index.php?option=com_content&amp;id=9&amp;Itemid=115" class="readon"><span>Logo Customization</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `title1` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/tutorials_1.jpeg
[demo3]: assets/tutorials_2.jpeg
[demo4]: assets/tutorials_3.jpeg