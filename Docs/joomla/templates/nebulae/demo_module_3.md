---
title: Nebulae: Recreating the Demo - Site Map
description: Your Guide to Recreating Elements of the Nebulae Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nebulae:Nebulae

---

Site Map
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Site Map`         |  
| Show Title | Show               |  
| Position   | footer-a           |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-grid-2 rt-demo-grid-omega">
    <a href="index.php" class="mod-var-link">Home</a><br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=103" class="mod-var-link">Features</a><br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=107" class="mod-var-link">Extensions</a>
</div>
<div class="floatright">
    <a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=108" class="mod-var-link">Tutorials</a><br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=112" class="mod-var-link">Styles</a><br />
    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=103" class="mod-var-link">J! Stuff</a>
</div>
<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                             |  
| :------------------ | :---------------------------------- |  
| Module Class Suffix | `title7 flushbottom nomarginbottom` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/sitemap_1.jpeg
[demo3]: assets/sitemap_2.jpeg
[demo4]: assets/sitemap_3.jpeg
