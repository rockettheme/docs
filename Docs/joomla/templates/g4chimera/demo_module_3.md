
---
title: Chimera: Recreating the Demo - FP Utility A
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP Utility A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `FP Utility A` |  
| Show Title | Hide           |  
| Position   | utility-a      |  
| Status     | Published      |  
| Access     | Public         |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<span class="rt-icon-left rt-hero-icon wow bounceInLeft">
  <i class="fa fa-laptop"></i>
</span>
<h3><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Fully Responsive and Mobile Minded</a></h3>
<p>Chimera features a fully responsive layout and design built from the ground up to ensure perfect presentation of your content from the smallest mobile devices to the largest desktop displays.</p>

<div class="clear"></div><br />

<span class="rt-icon-left rt-hero-icon wow bounceInLeft" data-wow-delay="0.2s">
  <i class="fa fa-tasks"></i>
</span>
<h3><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Colorfully Stylish Presets</a></h3>
<p>The perfect blend of whitespace and splashes of contrasting color create a smorgasbord of possibilities for giving your site the look and feel you are after.</p>

<div class="clear"></div><br />

<span class="rt-icon-left rt-hero-icon wow bounceInLeft" data-wow-delay="0.4s">
  <i class="fa fa-text-height"></i>
</span>
<h3><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Rich Typography and Iconic Elements</a></h3>
<p>Chimera helps you say more with less, utilizing clean and subtle fonts that are easy to read with contrasting bold rich titles and icon elements to draw attention to the most important messages.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting      |  
| :------------------ | :----------- |  
| Module Class Suffix | `fp-utility` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
