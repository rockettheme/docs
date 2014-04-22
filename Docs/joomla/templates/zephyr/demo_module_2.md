---
title: Zephyr: Recreating the Demo - Popular Features
description: Your Guide to Recreating Elements of the Zephyr Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/zephyr:Zephyr

---

Popular Features
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |
| :--------- | :----------------- |
| Title      | `Popular Features` |
| Show Title | Show               |
| Position   | sidebar-a          |
| Status     | Published          |
| Access     | Public             |

### Custom Output

~~~ .html
<ul class="menu">
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=128">New RokStories Style</a></li>  
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=45&amp;Itemid=121">RTL Support</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=45&amp;Itemid=121">iPhone Compatible</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=45&amp;Itemid=121">Smart Loading</a></li> 
</ul>
<br />
<a href="index.php?option=com_content&amp;view=article&amp;id=44&amp;Itemid=111" class="readon"><span>More Features</span></a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `box12 title3` |   

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
