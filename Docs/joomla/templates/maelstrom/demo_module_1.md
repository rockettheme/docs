---
title: Maelstrom: Recreating the Demo - FP Showcase A
description: Your Guide to Recreating Elements of the Maelstrom Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/maelstrom:Maelstrom

---

FP Showcase A
-----

![][demo]

:   1. **mod_custom** [20%, 10%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Scrolling Modules

![][demo5]

This particular module is part of a scrolling module position enabled via the template settings. To enable scrolling modules (allowing you to place multiple modules in the same positions, scrollable using a controller present on the frontend), navigate to **Admin -> Template Manager -> Maelstrom -> Features** and toggle the **Scroller** options to enable them. 

Since this particular module is in a **Showcase** position, the scroller can be toggled using the **Showcase Scroller** option. There has to be at least two modules in the same position for this feature to work.

### Details

![][demo2]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `FP Showcase A` |  
| Show Title | Hide            |  
| Position   | showcase-a      |  
| Status     | Published       |  
| Access     | Public          |  
| Language   | All             |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p><img src="images/stories/demo/frontpage/showcase1.jpg" alt="image" width="190" height="75" class="rt-image" /></p>
<p class="rt-justify"><strong>Preset 1:</strong> Uses 3 waves images which cross fade subtly to create a horizontal movement effect.</p>
<a href="?presets=preset1" class="readon fp-readon"><span>Live Preview</span></a>
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
| Module Class Suffix | `button3 nomarginbottom` |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
[demo5]: assets/demo_1d.jpeg
