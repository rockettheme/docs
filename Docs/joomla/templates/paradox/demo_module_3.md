---
title: Paradox: Recreating the Demo - FP Feature A
description: Your Guide to Recreating Elements of the Paradox Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradox:Paradox

---

FP Feature A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Scrolling Modules

![][demo5]

This particular module is part of a scrolling module position enabled via the template settings. To enable scrolling modules (allowing you to place multiple modules in the same positions, scrollable using a controller present on the frontend), navigate to **Admin -> Template Manager -> Paradox -> Features** and toggle the **Scroller** options to enable them. 

Since this particular module is in a **Feature** position, the scroller can be toggled using the **Feature Scroller** option. There has to be at least two modules in the same position for this feature to work.

### Details

![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `FP Feature A`    |  
| Show Title | Hide              |  
| Position   | feature-a         |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom">Control the scrolling feature on a <strong>per module row</strong>, and even a per-menu item basis. There are settings to <strong>enable/disable</strong> the feature, as well as set the <strong>duration</strong> time, <strong>animation</strong> effect, <strong>delay</strong> time and <strong>manual/automatic</strong> rotation.</p>
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

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
[demo5]: assets/demo_1d.jpeg
