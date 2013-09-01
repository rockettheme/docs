---
title: Fresco: Recreating the Demo - Style Control
description: Your Guide to Recreating Elements of the Fresco Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fresco:Fresco

---

Style Control
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `Style Control` |  
| Show Title | Show            |  
| Position   | sidebar-a       |  
| Status     | Published       |  
| Access     | Public          |  
| Language   | All             |  
| Note       | Blank           |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>There are 3 background levels: low, med &amp; high; so you can flip between a rich or subtle style.</p>

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117"><span>See More</span></a>
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
| Module Class Suffix | `bg2 mediumheader` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/style_1.jpeg
[demo3]: assets/style_2.jpeg
[demo4]: assets/style_3.jpeg