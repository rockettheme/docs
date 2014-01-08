---
title: Enigma: Recreating the Demo - Template Features
description: Your Guide to Recreating Elements of the Enigma Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/enigma:Enigma

---

Template Features
-----
![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `Template Features` |  
| Show Title | Show           |  
| Position   | sidebar-a      |  
| Status     | Published      |  
| Access     | Public         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="smallmarginbottom">Listed are the top template features for Enigma:</p>
<ul class="menu demo-list medmarginbottom">
    <li>
        <span class="item subtext">
            <span>
                Integrated Extensions
                <em><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112">A selection of styled RocketTheme addons.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Versatile &amp; Flexible Layouts
                <em><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Over 60 Gantry controlled grid row positions.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Eight Style Variations
                <em><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117">An array of diverse, rich preset styles.</a></em>
            </span>
        </span>
    </li>
    <li>
        <span class="item subtext">
            <span>
                Two Menu Systems
                <em><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115">Choose between Fusion and Splitmenu.</a></em>
            </span>
        </span>
    </li>
</ul>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108" class="readon"><span>View More Features</span></a>
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
| Module Class Suffix | `title1 nomargintop` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/features_1.jpeg
[demo3]: assets/features_2.jpeg
[demo4]: assets/features_3.jpeg