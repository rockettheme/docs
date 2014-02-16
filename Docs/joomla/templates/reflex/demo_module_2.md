---
title: Reflex: Recreating the Demo - FP MainTop A
description: Your Guide to Recreating Elements of the Reflex Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reflex:Reflex

---

FP MainTop A
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP MainTop A`     |  
| Show Title | Hide               |  
| Position   | maintop-a          |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<h2 class="title">Innovative Galleries</h2>
<span class="desc">Custom tag-based architecture.</span>
<img src="images/stories/launcher/blank1.png" alt="image" />
<p><strong>Tagging</strong> allows a single image to be individualized across several <strong>galleries</strong>, by using multiple image tags, with each <strong>slice</strong> containing unique data.</p>
<a href="index.php?option=com_rokgallery&amp;view=gallery&amp;Itemid=118" class="readon"><span>Continue Reading</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting       |  
| :------------------ | :------------ |  
| Module Class Suffix | `fp-feature`  |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/maintopa_1.jpeg
[demo3]: assets/maintopa_2.jpeg
[demo4]: assets/maintopa_3.jpeg
