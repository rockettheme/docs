---
title: Hybrid: Recreating the Demo - 10 Preset Styles
description: Your Guide to Recreating Elements of the Hybrid Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hybrid:Hybrid

---

10 Preset Styles
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Sliding Panel

![][demo5]

This particular module is part of a sliding module position enabled via the template settings. To enable a sliding panel, navigate to **Admin -> Template Manager -> Hybrid -> Features** and set either the **Feature Panel** or **Lower Panel** settings. 

Since this particular module is in a **Feature** position, the sliding panel can be toggled using the **Feature Panel** option.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `10 Preset Styles` |  
| Show Title | Show               |  
| Position   | feature-a          |  
| Status     | Published          |  
| Access     | Public             |  
| Language   | All                |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>A selection of varying <strong>colorings</strong> and <strong>shades</strong>, to demonstrate the <a href="index.php?option=com_content&amp;view=article&amp;id=15&amp;Itemid=152">stylistic diversity</a> and potential of the <strong>Hybrid</strong> template.</p>
<a href="index.php?option=com_content&amp;view=article&amp;id=15&amp;Itemid=152" class="readon"><span>Read More</span></a>
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
| Module Class Suffix | `title1 flushbottom`     |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
[demo5]: assets/demo_1d.jpeg
