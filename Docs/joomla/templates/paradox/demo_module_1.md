---
title: Paradox: Recreating the Demo - Introducing Paradox for December 2010
description: Your Guide to Recreating Elements of the Paradox Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradox:Paradox

---

Introducing Paradox for December 2010
-----

![][demo]

:   1. **mod_custom** [20%, 10%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Scrolling Modules

![][demo5]

This particular module is part of a scrolling module position enabled via the template settings. To enable scrolling modules (allowing you to place multiple modules in the same positions, scrollable using a controller present on the frontend), navigate to **Admin -> Template Manager -> Paradox -> Features** and toggle the **Scroller** options to enable them. 

Since this particular module is in a **Showcase** position, the scroller can be toggled using the **Showcase Scroller** option. There has to be at least two modules in the same position for this feature to work.

### Details

![][demo2]

| Option     | Setting                                 |  
| :--------- | :-------------------------------------- |  
| Title      | `Introducing Paradox for December 2010` |  
| Show Title | Show                                    |  
| Position   | showcase-a                              |  
| Status     | Published                               |  
| Access     | Public                                  |  
| Language   | All                                     |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<img src="images/stories/demo/frontpage/fp1.jpg" alt="image" class="rt-image floatleft" width="225" height="150"/>

<p><strong>Paradox</strong>, the <strong>December</strong> 2010 release, combines an dynamic, <strong>interactive</strong> arsenal with style and <strong>beauty</strong>.</p>

<p>Achieved with the functional <strong>scrolling</strong> modules features, and a <strong>diverse</strong> array of Preset Styles.</p>

<a href="index.php?option=com_content&view=article&id=2&Itemid=106" class="readon" target="_blank"><span>More Information</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
[demo5]: assets/demo_1d.jpeg
