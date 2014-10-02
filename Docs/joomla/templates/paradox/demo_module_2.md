---
title: Paradox: Recreating the Demo - Style Variation
description: Your Guide to Recreating Elements of the Paradox Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradox:Paradox

---

Style Variation
-----

![][demo]

:   1. **mod_custom** [20%, 65%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Scrolling Modules

![][demo5]

This particular module is part of a scrolling module position enabled via the template settings. To enable scrolling modules (allowing you to place multiple modules in the same positions, scrollable using a controller present on the frontend), navigate to **Admin -> Template Manager -> Paradox -> Features** and toggle the **Scroller** options to enable them. 

Since this particular module is in a **Showcase** position, the scroller can be toggled using the **Showcase Scroller** option. There has to be at least two modules in the same position for this feature to work.

### Details

![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `Style Variation` |  
| Show Title | Show              |  
| Position   | showcase-b        |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<ul class="bullet-monitor">
  <li><strong>Presets:</strong> 8 preset configurations of varying color schemes.</li>
  <li><strong>Background:</strong> 3 levels of detail for the main background: High, Med and Low.</li>
  <li><strong>Body:</strong> 2 levels of detailing for the body of the theme: High and Low</li>  
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

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
[demo5]: assets/demo_1d.jpeg
