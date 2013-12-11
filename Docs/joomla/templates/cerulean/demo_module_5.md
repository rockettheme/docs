---
title: Cerulean: Recreating the Demo - About Cerulean
description: Your Guide to Recreating Elements of the Cerulean Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

About Cerulean
-----
![][demo]
We used a **mod_custom** module to make up the content in the **sidebar-b** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | About Cerulean     |  
| Show Title        | Hide               |  
| Position          | sidebar-b          |  
| Status            | Published          |  
| Access            | Public             |  
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div>
<span class="rt-image rt-floatleft">
<img src="images/rocketlauncher/frontpage/sidebar-b/img1.jpg" alt="image">
</span>
<small class="hidden-tablet">Choose between a static or a <a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=107">RokGallery</a> powered slideshow in the template <strong>header</strong><span class="visible-large">, with its standard configuration option</span>.</small>
<small class="visible-tablet">Choose between a static or a <a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=107">RokGallery</a> slideshow header.</small>
</div>

<div class="clear largemarginbottom"></div>

<div>
<span class="rt-image rt-floatleft">
<img src="images/rocketlauncher/frontpage/sidebar-b/img2.jpg" alt="image">
</span>
<small class="hidden-tablet">The <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=106">dropdown menu</a> supports multiple columns, <strong>inline icons</strong>, subtext<span class="visible-large">, inline modules and positions,</span> and much more.</small>
<small class="visible-tablet">The <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=106">dropdown menu</a> supports <strong>inline icons</strong> and much more.</small>
</div>

<div class="clear largemarginbottom"></div>

<div>
<span class="rt-image rt-floatleft">
<img src="images/rocketlauncher/frontpage/sidebar-b/img3.jpg" alt="image">
</span>
<small class="hidden-tablet">Select the custom <a href="#">Cerulean</a> article/blog layout <span class="visible-large">options in the menu manager</span> to display the overhanging <strong>ribbon date</strong>.</small>
<small class="visible-tablet">Select the <a href="#">Cerulean</a> article/blog layout for a custom <strong>ribbon date</strong>.</small>
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

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix | `box5`  |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/about_1.jpeg
[demo3]: assets/about_2.jpeg
[demo4]: assets/about_3.jpeg
