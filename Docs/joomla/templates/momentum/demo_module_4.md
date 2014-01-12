---
title: Momentum: Recreating the Demo - Color Chooser Controls
description: Your Guide to Recreating Elements of the Momentum Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/momentum:Momentum

---

Color Chooser Controls
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `Color Chooser Controls` |  
| Show Title | Show                     |  
| Position   | sidebar-a                |  
| Status     | Published                |  
| Access     | Public                   |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=116">Customize</a> the template's <strong>color scheme</strong> via the Gantry administrator. Control various style elements such as <strong>link, text and background color</strong>, of the current or new <strong>presets</strong>.</p>
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
| Module Class Suffix | `title2` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/color_1.jpeg
[demo3]: assets/color_2.jpeg
[demo4]: assets/color_3.jpeg