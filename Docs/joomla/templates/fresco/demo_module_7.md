---
title: Fresco: Recreating the Demo - Top Features
description: Your Guide to Recreating Elements of the Fresco Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fresco:Fresco

---

Top Features
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `Top Features` |  
| Show Title | Show           |  
| Position   | sidebar-a      |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div>
  <h4 class="nomarginbottom">Beautifully Styled</h4>
  <p class="nomarginbottom">Ten stunning preset styles and a selection of elegant, stylistic module variations.</p>
</div>

<div>
  <h4 class="nomarginbottom medmargintop">Fusion</h4>
  <p>A Mootools-enhanced CSS dropdown menu system, with multi-column support.</p>
</div>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=102" class="readon"><span>See More</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Custom  |

### Advanced
![][demo4]

| Option              | Setting            |  
| :------------------ | :----------------- |  
| Module Class Suffix | `bg3 mediumheader` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/features_1.jpeg
[demo3]: assets/features_2.jpeg
[demo4]: assets/features_3.jpeg