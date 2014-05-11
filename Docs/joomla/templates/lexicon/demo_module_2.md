---
title: Lexicon: Recreating the Demo - Inside Lexicon
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Inside Lexicon
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Inside Lexicon` |  
| Show Title | Show             |  
| Position   | sidebar-a        |  
| Status     | Published        |  
| Access     | Public           |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul class="menu">
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Gantry<span class="hidden-tablet"> Framework</span></a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115">Dropdown<span class="hidden-tablet"> Menu</span></a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=113"><span class="hidden-tablet">Module </span>Variations</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=112"><span class="hidden-tablet">Module </span>Positions</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114"><span class="hidden-tablet">Custom </span>Typography</a></li>
    <li><a href="#"><span class="hidden-tablet">Multiple </span>Presets</a></li>
</ul>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                     |  
| :------------------ | :-------------------------- |  
| Module Class Suffix | `box1 title1 fp-sidebar-01` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
