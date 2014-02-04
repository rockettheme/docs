---
title: Halcyon: Recreating the Demo - Individual Module Styling
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Individual Module Styling
-----

![][demo]

:   1. **mod_custom** [25%, 7%, se]

This area of the front page is a series of three **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the first module in this set, **Individual Module Styling**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                     |  
| :--------- | :-------------------------- |  
| Title      | `Individual Module Styling` |  
| Show Title | Show                        |  
| Position   | mainbottom-a                |  
| Status     | Published                   |  
| Access     | Public                      |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p>An assortment of over <strong>50</strong> module class suffixes, both structural and <strong>stylistic</strong>, to create an individual <strong>module</strong> appearance.</p>
<a href="index.php?option=com_content&amp;id=2&amp;Itemid=108" class="readon"><span>More Information</span></a>
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
| Module Class Suffix |          |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/ims_1.jpeg
[demo3]: assets/ims_2.jpeg
[demo4]: assets/ims_3.jpeg